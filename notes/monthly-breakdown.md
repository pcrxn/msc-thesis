# Month-by-month breakdown of progress

## September

* UV spectra and mass spec of BDDA/BDTA enrichments revealed no evidence of biodegradation
* BioinfoConf 2019
  - Hosted in Lethbridge, attended remotely
  - Learned of some tools, including Snakemake

## October

* qPCR of intI1 in 2019 D30 fluoroquinolone soil
  - No difference between treated and control
* Prepared clean PCR product 16S rDNA of BDDA/BDTA soil for MiSeq sequencing
  - Product sequenced on MiSeq (along with macrolide soil)
* qPCR in BDDA/BDTA soil of: 16S, strA, strB, sul1, blaoxA20, incW, aadA, ermF
  - Most gene targets were below the limits of quantification or detection
  - intI (barely) quantifiable in DA 10, TA 10, DA 10 TA 10, DA 0.1 TA 10, BLQ for control, DA 0.1, TA 0.1
    - Compared to 2017 D30 macrolide intI1 abundance (0.003 copies per 16S), ~64X less abundant
  - sul1, strA, strB quantifiable in some microplots (but not control, TA 0.1, or DA 0.1)
  - Limit of quantification: SQ = 4 copies per rxn
* BGRF poster presentation

## November

* Analyzed 16S data of BDDA/BDTA and macrolide soil
  - BDDA: Samples did not cluster on ordination plot, scree plot revealed no large sources of variation, alpha diversity more variable between biological replicates than between treatments
  - Macrolide: Samples don't cluster well on ordination plot, scree plot revealed a potential source of variation, and alpha diversity appears to be uncorrelated with strength of treatment, but may be correlated with treatment v. no treatment
* Shifted focus to macrolide soil
  - Isolating intrinsically susceptible macrolide-resistant bacteria from soil
  - Integron sequencing of macrolide, arsenic, and BDDA/BDTA soil
* Optimized integron gene cassette PCR using high-fidelity polymerase
* Isolated 2019 D30 arsenic soil DNA
* Applied for CIHR
* qPCR of arsenic soil DNA for intI1
  - No differences between treated and control; abundance ~ same as BDDA/BDTA plots
* Worked out logistics of sequencing gene cassette PCR product on HiSeq, based upon results from Ghaly et al. (2019), and performed cost-analysis
  - Need to sequence to ~ 1M 1 x 100 bp reads per sample to reach the plateau in rarefaction curve (~ 5000 unique gene cassettes)
    - HiSeq 2500 2 x 125 bp High Output, 1 lane = $2,980 at Sick Kids' Hospital, and outputs max. 2 billion PE reads (27.7 M reads per sample, ~ 30x coverage needed to reach plateau in rarefaction)
      - 72 samples = $41 per sample
* Completed BIO9545Q

## December

* Applied for OGS
* Established enrichments for macrolide-resistant soil bacteria, using 2019 D30 HIGH Macrolide soil
  - Media: Enterobacteriaceae enrichment (EE) broth, buffered peptone water, Enterococcosel broth, brain heart infusion broth (BHI), Baumann Enrichment Broth (BEM), Cetrimide Broth
  - Targets: E. coli, Klebsiella, Staphylococci, Pseudomonads, Streptococci
  - Concs of AZM: 4, 8, 16, 32 ug/mL
  - Growth for BPW, BHI at all concs; growth for 2 of 4 EE broth at 32, all growth at 16; no growth for Enterococcosel, BEB, or Cetrimide Broth
* Plated 2019 D30 Macrolide soil on Chromocult Agar (CHR), Manitol Salt Agar (MSA), Vogel-Johnson Agar (VJA), Cetrimide Agar (CET), MacConkey Agar (MAC)
  - Plates were messy, dilutions wrong, overgrowth of off-targets
* Isolated DNA from macrolide enrichments with the highest concentration of AZM and growth
* Acquired gene cassette PCR product for coccidiostat and macrolide soil plots
* Completed BIO9546R

## January

* PCR assayed enrichment DNA for msrE, mphE, msrE+mphE, intI1, totB
  - msrE, mphE absent from DNA (no amplification)
  - No amplification of msrE+mphE and intI1 in positive controls, thus no amplification in samples
  - Good amplification of totB
* Acquired remaining gene cassette PCR product (duplicate of macrolide)
* Bioanalyzer of gene cassette PCR product LB0216-LB0226 to test removal of low bp DNA
  - Removed some DNA <200 bp, but some remaining
* PCR cleanup of gene cassette PCR product for sequencing
* Class 1 integron (C1I) gene cassette sequencing
  - Qubit samples post-PCR-cleanup
  - Dilute samples to 0.2 ng/uL
  - Tagment amplicons
  - Amplify/index libraries
  - Qubit indexed libraries
  - HighPrep cleanup of indexed libraries
  - Bioanalyzer of cleaned libraries
    - Revealed a significant amount of DNA between 0-200 bp, likely due to primer/index carryover
    - ~ 20% of library <200 bp
  - Qubit cleaned and index libraries
  - Pooled libraries into one final library and sent for sequencing

## February

* Researched bacteria that are intrinsically susceptible to macrolides
  - Obtained MICs where possible, otherwise predicted based upon information from the literature
* Prepared > 500 plates: CHR-CON, CHR + AZM 8, CHR + AZM 32, CHR + ERY 128, CHR + CLR 64, CHR + CLR 128, VJA-CON, VJA + AZM 8, VJA + ERY 8, VJA + CLR 8, CHR-AC-CON, CHR-AC + AZM 64, CHR-AC + ERY 32, CHR-AC + CLR 32, mENTER-CON, mENTER + AZM 8, mENTER + ERY 16, mENTER + CLR 16, CHR-STAPH-CON, CHR-STAPH + AZM 8, CHR-STAPH + ERY 8, CHR-STAPH + CLR 8
  - Plated at various dilutions to capture quantifiable range (20-200 CFU)
    - Erythromycin-resistant presumptive *Acinetobacter* spp., presumptive *S. aureus*, and non-*S. aureus* Staphylococci appear to be more abundant, on average, in the high treatment than other treatments, but inconclusive due to large variation between counts of biological replicates (different microplots of the same treatment)
* Established 10 mL Baumann Enrichment Broth enrichments for *Acinetobacter* spp. at 64, 128, and 256 ug/mL AZM, CLR, and ERY, inoculated with 1 mL 2019 D30 Macrolide soil suspended in Na-metaP buffer (1/10X)
  - Incubated aerobically (loose caps, taped) at 30C, 250 rpm for 2 days
    - Obvious cloudy growth in no-antibiotic controls (for all four plots)
    - Suspected growth at 64 ug/mL for all antibiotics, as indicated by soil particles that appear to be congealed together in a biofilm matrix
    - Suspected growth at 128 ug/mL for most antibiotics/plots
    - Suspected growth at 256 ug/mL for most AZM enrichments, some ERY and CLR
* PCR assayed colonies from ChromAgar Acinetobacter (CHR-AC) plates that had been spread-plated with 2019 D30 Macrolide soil for msrE, mphE, msrE+mphE, C1I gene cassettes, and totB
  - All plates positive for totB
  - Two plates positive for a single C1I gene cassette (~ 350 bp)
  - All plates negative for msrE, mphE, msrE+mphE

## March

* PCR assayed Baumann Enrichment Broth *Acinetobacter* spp. enrichments from 2019/02/27, and enrichments provided by Andrew, for msrE, mphE, C1I gene cassettes, totB
  - None of my enrichments tested positive for msrE, mphE, or C1I gene cassettes, but one of Andrew's enrichments (HR019) tested weakly positive for msrE
* Inoculated 25 mL Baumann Enrichment Broth supplemented with 128 ug/mL AZM with 5 mL each of Andrew's BEB enrichments, and incubated aerobically at 30C, 200 rpm, for 7 days, to keep enrichments viable during AAFC closure
  - Stored at 4C
