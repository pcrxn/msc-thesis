# Parnanen *et al.* (2018) as a model study for my metagenomic analysis

**Citation**: Pärnänen K, Karkman A, Hultman J, Lyra C, Bengtsson-Palme J, Larsson DGJ, Rautava S, Isolauri E, Salminen S, Kumar H, Satokari R, Virta M. 2018. Maternal gut and breast milk microbiota affect infant gut antibiotic resistome and mobile genetic elements. Nat Commun 9:3891.

* The authors find that "fecal ARG and mobile genetic element profiles of infants are more similar to those of their own mothers than to those of unrelated mothers"
  - This is essentially what I want to do: I want to ask, are the profiles of ARGs and MGEs within unexposed soil plots more similar to each other than to exposed plots?
  - How did they *statistically* support this?

## Methods

* "No quality trimming prior to further analysis was done as the quality of the reads was high"
  - It would be interesting to see how their FastQC plots compare to mine!

### Sequence depth

* The authors describe their study as "deep metagenomic sequencing"
  - "The mean sequencing depth of the non-human DNA was 1.9 Gbp for fecal samples and 160 Mbp for milk samples"

### Taxonomy

"Species level community profiling based on marker genes was done using **Metaphlan2** version 2.6.0 by running the metaphlan2.py command with the `--input_type fastq --nproc 5` options.
Merged abundance table was created using the Metaphlan2 utils script.
The merged abundance table was edited to only include taxa which were identified to species level.
Additional community profiling was done using **Metaxa2** version 2.1 for 16S rRNA read extraction in paired-end mode.
The 16S rRNA sequence reads were classified using **mothur**’s (version 1.39.5) classify.seqs command with SILVA49 v. 123 as the reference database, with the `cutoff = 60, probs = F and processors = 8` parameters.
A custom Unix script was used to create an OTU table based on the classifications.
Strain-level profiling and strain tracking analysis as done using **Strainphlan** and the extract_markers py command to extract markers for Escherichia coli, Klebsiella pneumoniae and all Streptococcus and Staphylococcus species.
The strainphlan.py command with `--relaxed_parameters2` option was used to create taxonomic trees of the strains in all samples."

* Why did the authors use two different methods for determining taxonomy?
  - Used Metaphlan2 for classifying reads
  - Used Metaxa2 for 16S rDNA analysis

### Resistome and mobilome

"Resistome and mobilome were characterized by mapping metagenomic reads to a comprehensive non-redundant database of more than 2700 mobile genetic element and 3100 antibiotic resistance genes including Comprehensive Antibiotic Resistance Database protein homolog model version 1.1.2 (**CARD**) and **ResFinder** version 2.152.
Some analyses were performed with only the Resfinder database, which has only acquired or mobile ARGs.
A custom MGE database was created by fetching CDS for genes that were annotated as IS\*, ISCR\*, intI1, int2, istA\*, istB\*, qacEdelta, tniA\*, tniB\*, tnpA\*, or Tn916 transposon ORFs or genes in the **NCBI nucleotide database** and **PlasmidFinder** database.
Redundancy in the databases was removed with **VSEARCH** `-usearch_global` command with `-—id 99` option.
In total, the MGE database consists of genes with 278 different gene name annotations and more than 2000 unique sequences excluding the sequences from **PlasmidFinder** database.
The custom MGE database is available from https://github.com/KatariinaParnanen/MobileGeneticElementDatabase.
**Bowtie2** mapping was done with options `-D 20 -R 3 -N 1 -L 20 -i S,1,0.50` and was used to map reads the ARG and MGE databases.
**SAMtools** was used to filter and count reads and if both reads mapped to the same gene the read was counted as one match and if the reads mapped to different genes, both were counted as hits to the respective gene.
DNA sequence profiles based on kmers were produced from the metagenomic reads using **sourmash** with option `-kmer 31`.
Subsets of reads mapping to ARGs and MGEs were used to produce the profiles for ARGs and MGEs."

* Two databases were used for resistome mapping: CARD and ResFinder
* The custom MGE database was created from entries in the NCBI nucleotide database and PlasmidFinder
  - No database specifically used for *intI1*
* It seems that they clustered their databases at 99% identity (i.e. sequences that are > 99% identical to an existing sequence are not retained)
* For their mapping, they created DNA sequence profiles of kmers from the metagenomic reads (indexing?), and then subsets of these reads that mapped to ARGs and MGEs were used to produce the profiles for ARGs and MGEs
  - I don't fully understand this approach, but I may need to read into how sourmash works
    - An alternative to sourmash may be KmerResistance (Clausen *et al.* 2016)
    - How does kmer mapping compare to HMM mapping?
