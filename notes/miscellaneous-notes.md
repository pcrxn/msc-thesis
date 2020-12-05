# Miscellaneous notes

---

## March 6, 2020

* Next steps:
  - Test enrichments for presence of msrE, mphE, C1I cassettes, and totB
  - Preliminary analysis of HiSeq C1I gene cassette data, using Bowtie2 to map reads to the integron database
  - Submit draft of proposal to Ed and Vera by **April 2, 2020** (four weeks from today)
    - Focus on macrolides or on integrons?
      - Would be better informed by preliminary analysis of C1I sequencing data
  - Exogenous plasmid DNA isolation from high treatment macrolide plots
    - Requirements:
      - Media:
        - Plate count agar
        - Tryptic soy broth
      - Recipient cultures: E. coli, B. subtilis
      - 5 g of soil per mating (1% of soil collected?)
* BIO9919B proposal due on **March 13, 2020**
* STATS2244B Term Test 2 proctoring at 6:10 pm on **March 13, 2020**

---

## March 8, 2020

* The *main objective* of my thesis is one of the following:
  - If focusing on the macrolides:
    - To assess the risk of long-term exposure of agricultural soil to macrolide antibiotics on AMR in soil bacteria
  - If focusing on all three microplots (macrolides, QACs, coccidiostats):
    - To assess the risk of long-term exposure of agricultural soil to antibiotics, disinfectants, and heavy metals on AMR in soil bacteria
* Each of these objectives can be investigated on at least two different levels:
  1. Phenotypic resistance.
    - Quantifiable by %R in viable plate counts, or by disk diffusion method of isolates
  2. Mobilization of ARGs.
    - Mobilization of ARGs via plasmids
      - Not directly quantifiable, but could be informative in a controlled evolution experiment, or could support other sequencing information
    - Mobilization of ARGs via integrons
      - Quantifiable by integrome sequencing
    - Mobilization of ARGs via other genetic elements
      - Transposons, insertion sequences, inverted repeats

---

## March 10, 2020

* What do we know about class 1 integrons?
  - What is the potential of class 1 integrons as invasive species across the current bacterial taxa?
    - "The host species of class 1 integrons are found to be *highly conserved within one narrow bacterial lineage in Gammaproteobacteria*, especially in three families of Enterobacteriaceae, Pseudomonadaceae, and Moraxellaceae" (Zhang et al. 2018)
    - Class 1 integrons are *significantly enriched in pathogenic bacteria*, but are also commonly distributed in non-pathogenic Gammaproteobacteria (Zhang et al. 2018)
    - Over half of all class 1 integrons in NCBI are *embedded in chromosomes* (Zhang et al. 2018)
      - Zhang et al. (2018) interpret this to mean that the dissemination of ARGs by HGT may be limited, "but critical, in terms of exchanging [gene cassettes] be-
tween non-pathogens and pathogens"
  - What is the contribution of class 1 integrons to the acquisition of antibiotic resistance?
    - "[T]he ARGs harbored on all types of integrons are surprisingly limited to only 69 genotypes from 9 phenotypes of ARGs[...] i.e., the aminoglycosides, sulfonamide, trimethoprim, beta-lactam, chloramphenicol, and rifamycin" (Zhang et al. 2018)
    - "89% of the ARG genotypes in bacterial genomes are not likely to be acquired and expressed via the integrons" (Zhang et al. 2018)
  - What do we know about class 1 integrons and macrolide resistance?
    - According to Zhang et al. (2018), macrolide resistance is known to be carried only in *Klebsiella* on clinical class 1 integrons

---

## March 16, 2020

### Protocol for exogenous plasmid DNA isolation

#### Materials

- Tryptic soy broth (TSB), 3 x 800 mL
- Plate count agar (PCA), supplemented with RIF (50 mg/L), KAN (50 mg/L), CYC (100 mg/L)
- Plate count agar (PCA), supplemented with RIF (50 mg/L), KAN (50 mg/L), CYC (100 mg/L), ERY (50 mg/L; see Gonzalez-Plaza et al. 2019)
- Plate count agar (PCA), supplemented with RIF (50 mg/L), KAN (50 mg/L), CYC (100 mg/L), AZM (16 mg/L)
- Plate count agar (PCA), supplemented with RIF (50 mg/L), KAN (50 mg/L), CYC (100 mg/L), CLR (X mg/L)
- Plate count agar (PCA), supplemented with SPT (100 mg/L), CYC (100 mg/L)
- Plate count agar (PCA), supplemented with CYC (100 mg/L)
- 0.85% NaCl, autoclaved, 4 L
- Rifampicin (RIF)
- Kanamycin (KAN)
- Cycloheximide (CYC)
- Spectinomycin (SPT)

#### Methods

##### Day 1

1. Prepare overnight cultures of the recipient strain.
Overnight culture of the recipient strain E. coli CV601 is grown in TSB, supplemented with RIF (50 mg/L) and KAN (50 mg/L) as selective agent for the recipients with 200 rpm agitation at 28 or 37C.
*Prepare extra overnight culture (+ 50 mL) for use as a no-donor control.*

2. Suspend 2x 5 g of 10 mg/kg macrolide-treated soil in 45 mL non-selective TSB or BPW, and incubate overnight at 28 or 37C with 200 rpm agitation.
*The bacterial fraction of one tube will eventually be mixed with recipient cells, while the bacterial fraction of the other tube will be used as a no-recipient control.*

##### Day 2

3. Transfer 1 ml of the overnight recipient culture into a sterile microcentrifuge tube and centrifuge at 3,100 x g for 5 min, then discard the supernatant.
Wash recipient cells twice by resuspension in 1 ml of 1/10X TSB and centrifugation at 3,100 x g for 2 min.
Resuspend the cell pellet in 1 ml of 1/10X TSB.

4. Centrifuge soil enrichment tubes at 300 x g for 5 min to collect soil particles at the bottom of the tube.
Transfer bacteria-containing supernatant to a sterile 50 mL Falcon tube.
Centrifuge bacteria-containing supernatant at 3,100 x g for 10 min to pellet bacterial cells.
Decant supernatant and resuspend in 0.85% NaCl solution, and repeat once for a total of two NaCl washes.
**Do not resuspend in NaCl solution after second wash**:
Instead, resuspend in 45 mL of 1/10X TSB.

5. **This step is for direct extraction of soil bacteria, using a very short pre-enrichment step.**
Suspend 5 g of 10 mg/kg macrolide-treated soil in 45 mL non-selective 1/10X TSB, and incubate at 28 or 37C for 2 h at 200 rpm agitation.
Centrifuge soil at 300 x g for 5 min to collect soil particles at the bottom of the tube.
Transfer bacteria-containing supernatant to a sterile 50 mL Falcon tube.
Centrifuge bacteria-containing supernatant at 3,100 x g for 10 min to pellet bacterial cells.
Decant supernatant and resuspend in 0.85% NaCl solution, and repeat once for a total of two NaCl washes.
**Do not resuspend in NaCl solution after second wash**:
Instead, resuspend in 45 mL of 1/10X TSB.

6. Prepare the following mixtures:
  - To a 50 mL Falcon tube, transfer 15-30 mL enriched soil bacterial suspension, and add 500 uL recipient cell suspension (**biparental mating using enriched donor**).
  - To a 50 mL Falcon tube, transfer ~~5 mL~~ 15-30 mL enriched soil bacterial suspension (**no-recipient control for enriched donor**).
  - To a 50 mL Falcon tube, transfer 15-30 mL non-enriched soil bacterial suspension, and add 500 uL recipient cell suspension (**biparental mating using non-enriched donor**).
  - To a 50 mL Falcon tube, transfer ~~5 mL~~ 15-30 mL enriched soil bacterial suspension (**no-recipient control for non-enriched donor**).
  - To a 50 mL Falcon tube, transfer 15-30 mL 1/10X TSB, and add 200 uL recipient cell suspension (**no-donor control for enriched and non-enriched donors**).

7. Centrifuge all mixtures at 3,100 x g for 10 min.
Resuspend the pellets in 200 uL 1/10X TSB, and pipette onto filters placed on PCA supplemented with CYC (100 mg/L) to avoid fungal growth.
Incubate filters overnight at 28 or 37C.

##### Day 3

8. Detach bacteria from the mating filters in 50 mL centrifugation tubes by adding 2-5 mL 0.85% NaCl and vortexing for 1 min.

9. Prepare serial dilutions of the detached bacterial suspensions, and plate onto PCA supplemented with RIF (50 mg/L), KAN (50 mg/L), and CYC (100 mg/L), with appropriate concentrations of other antibiotics (ERY, CLR, and AZM).
Additionally, pipette 3 x 20 uL of each serial dilution onto PCA supplemented with KAN, RIF, and CYC, for enumeration of recipient cells.

10. Apply undiluted suspensions of the filter with background controls and recipient controls onto the same media used for transconjugant screening.

11. Incubate plates at 28 or 37C for up to 3 days until sufficient growth of the transconjugants.

---

## March 20th, 2020

* On March 17th, 2020, I inoculated 25 mL of Baumann Enrichment Broth (BEB) with 5 mL of Andrew's BEB enrichments, to ensure that the bacteria remain viable during the AAFC closure
  - Stored Andrew's enrichments at 4C in the fridge in the molecular biology lab
* Ghaly et al. (2019) filtered out sequences that didn't represent real integron gene cassettes by searching for the PCR primers at the distal ends of the assembled contigs
  - For my dataset, though, I don't know that this is possible, because of the way that the transposase works

---

## April 10, 2020

* What do we know about class 1 integrons? (cont.)
  - What is the contribution of class 1 integrons to the acquisition of antibiotic resistance? (cont.)
    - There is evidence that ARGs from the environment can be captured by class 1 integrons in the mammalian microbiome [@mcdougallBatsReservoirsAntibiotic2019]
    - Class 1 integrons are prevalent in the microbiomes of raw produce [@blauTransferableResistomeProduce2018]
    - There is increasing evidence for class 1 integrons of 'atypical structure' [@blauTransferableResistomeProduce2018]
    - Class 1 integrons are abundant on inc plasmids [@blauTransferableResistomeProduce2018]
* What do we know about macrolide resistance and plasmids?
  - Azithromycin pollution from a manufacturing plant was associated with increased frequency of captured ARGs from exposed sediments [@gonzalez-plazaAntibioticmanufacturingSitesAre2019]
* What do we know about integron gene cassettes?
  - Gene cassettes "have been recovered from every environment surveyed" [@ghalyPerilPromiseIntegrons2020]
  - It is estimated that there are 4,000 to 18,000 unique gene cassettes per 0.3 g soil [@ghalyHighDiversityRapid2019]
  - Gene cassette acquisition via *intI* results in two substrates: the original substrate (e.g. plasmid) prior to the recombination event, and the original substrate with the inserted gene cassette [@ghalyPerilPromiseIntegrons2020]
    - This allows the bacterium to "sample any incoming gene cassette, while also maintaining the original phenotype, which will predominate if the new cassette profile reduces overall host fitness" [@ghalyPerilPromiseIntegrons2020]
    - "The same mechanism is likely to be involved in cassette excision" [@ghalyPerilPromiseIntegrons2020]
  - Gene cassettes that are associated with mobile integrons have inconsistent codan usage in their ORFs, and have considerable sequence diversity in their *attC* sites [@ghalyPerilPromiseIntegrons2020]
    - Gene cassettes that are associated with chromosomes often have highly similar *attC* sites that are species-specific and cluster according to host topology [@ghalyPerilPromiseIntegrons2020]
  - The majority of mobile gene cassettes confer resistance to antibiotics, even outside of clinical settings [@ghalyPerilPromiseIntegrons2020]
  - "In mobile integrons, heterologous cassettes are much more likely to be disruptive to host fitness. This may explain why the majority of cassettes associated with mobile integrons encode antibiotic-modifying
enzymes that function without significant cellular interactions..." [@ghalyPerilPromiseIntegrons2020]

## April 11, 2020

* What do we know about integron gene cassettes? (cont.)
  - ORFs in gene cassettes associated with mobile integrons are biased towards encoding b-lacatamases, acetyltransferases, and nucleotidyl transferases (i.e. antibiotic-modifying enzymes that function without significant cellular interactions) [@ghalyPerilPromiseIntegrons2020]
    - Genes that confer "antibiotic resistance through regulatory mechanisms are rarely observed within mobile integrons" [@ghalyPerilPromiseIntegrons2020]
    - **>80%** sequenced gene cassettes encode proteins of unknown function [@ghalyPerilPromiseIntegrons2020]
  - In soil from Antarctica and Australia, almost 600 cassettes were universally present [@ghalyHighDiversityRapid2019]
    - Some of these same cassettes have been recovered from Canada and France, and they appear to be independent of environment type
* What do we know about class 1 integrons? (cont.)
  - What do we know about class 1 integrons and macrolide resistance? (cont.)
    - Discharge from an azithromycin manufacturing plant significantly increased the abundance of macrolide resistance genes and class 1 integrons [@milakovicPollutionAzithromycinmanufacturingPromotes2019]
    - The expression of *intI1* is regulated by the SOS resposne in *E. coli*, and subinhibitory antibiotic concentrations promote the selection of integron-carrying bacteria, especially those with a strong Pc promoter [@lacotteClassIntegronsAre2017]

## April 17, 2020

* A good colour palette for future figures (in hexadecimal): #002f4a, #d62a29, #fe6625, #fdc04c, #e9e3b7

## April 22, 2020

* What do we know about integron gene cassettes? (cont.)
  - Mobile integrons "contain a limited number of [gene cassettes] (less than 10)" (Naas et al. 2001 referenced by @stalderIntegronInvolvementEnvironmental2012)

## April 23, 2020

* Viable plate count of macrolide soil using aminoglycoside antibiotics

## April 28, 2020

### Introduction WIP

* Effluent of European urban WWTPs of countries with high antimicrobial consumption had a significantly greater abundance of *intI1*, *tnpA*, and MLSb ARGs relative to the influent, whereas countries with low antimicrobial consumption had decreased abundance of these genes in the effluent relative to the influent [@parnanenAntibioticResistanceEuropean2019]
* *ermF*, *tnpA*, and *intI1* persisted after wastewater treatment in >90% of analyzed samples [@parnanenAntibioticResistanceEuropean2019]
* Reason for why macrolides are good at carrying over from WWTPs to sewage sludge to biosolids:
  - "the macrolide antibiotics are very large and positively charged molecules, while the biosolids particulates have large interstitial spaces and negative charges" [@jones-leppPharmaceuticalsPersonalCare2007]
* Another study that sequenced class 1 integron gene cassettes was @maPrevalenceIntegronsCarrier2017
  - Top two ARG phenotypes detected: aminoglycosides and trimethoprim
* MLS ARGs were carried mostly on plasmids in WWTPs [@cheMobileAntibioticResistome2019]
  - 17% of MLS ARGs were carried by ICEs
  - MLS carried by B. fragilis, E. anophelis, E. faecium, C. difficile, E. coli, K. pneumoniae, A. baumannii

## December 4, 2020

Antimicrobial resistance (**AMR**) is estimated to have caused 5,400 Canadian fatalities in 2015 — a number which is expected to climb to 13,700 deaths per year by 2050, while disproportionally affecting populations that are at a greater risk of acquiring infections [@councilofcanadianacademiesWhenAntibioticsFail2019].
AMR is the process by which microorganisms acquire or develop defences against harmful chemicals in their environment, including terrestrial and aquatic ecosystems, agri-food, hospitals, and the human body.
In the context of an infection, resistant microorganisms limit available treatment options.
The consumption of antimicrobials in healthcare and agriculture promotes AMR in the clinic [@europeancentrefordiseasepreventionandcontrolecdcECDCEFSAEMA2017] and in the environment [@parnanenAntibioticResistanceEuropean2019], thus there is a need to understand the consequences of antimicrobial exposure on resistance in environmental microorganisms.

AMR is ancient and prolific in the environment [@DCosta2006; @dcostaAntibioticResistanceAncient2011].
Hundreds of millions of years of chemical warfare between microorganisms has selected for diverse and elaborate resistance mechanisms, including but not limited to antimicrobial inactivation, efflux, and ribosomal subunit protection [@Boolchandani2019].
The long-term exposure of these microorganisms to antimicrobials results in the amplification of antimicrobial resistance genes (**ARGs**) which encode resistance to antimicrobials [@lauImpactsMultiyearField2020].
Interestingly, the amplified ARGs need-not encode resistance to the antimicrobials of which they were initially exposed;
genetic linkage of ARGs encoding resistance to different classes of antimicrobials has been extensively described in environmental bacteria [@johnsonClustersAntibioticResistance2016; @ghalyPerilPromiseIntegrons2020; @palCooccurrenceResistanceGenes2015] via mobile genetic elements.

In bacteria, mobile genetic elements promote the rearrangement of DNA within and between individuals, including the shuttling of ARGs [@partridgeMobileGeneticElements2018].
The collection of all mobile genetic elements within a bacterial metagenome is known as the **mobilome** (the fraction of the metagenome that is associated with the mobilization of DNA), which may include plasmids, insertion sequences, and transposons.
Class 1 integrons (**C1Is**) are genetic elements that are overrepresented in human pathogens [@zhangConservedPhylogeneticDistribution2018], but are incapable of mobilizing themselves, and must 'hitchhike' as passengers on mobile genetic elements to propagate within and between genomes [@gillingsIntegronsPresentFuture2014].
C1Is are minimally comprised of the C1I integrase (*intI1*) gene, recombination site (*attI1*), promoter (*Pc*), and a 3'-conserved segment containing a biocide resistance gene (*qacEdelta1*) and a sulfonamide resistance gene (*sul1*)~~, and an open reading frame encoding a protein of unknown function~~ [@stalderIntegronInvolvementEnvironmental2012; @gillingsIntegronsPresentFuture2014].
Importantly, C1Is are capable of acquiring and promoting the expression of **gene cassettes** --- discrete, circular DNA molecules that contain an open reading frame and a downstream cassette recombination site (*attC*) [@ghalyPerilPromiseIntegrons2020].

Gene cassettes are ancient structures that have been detected in every environment surveyed on Earth [@gillingsIntegronsPresentFuture2014; @ghalyPerilPromiseIntegrons2020].
About half of all sequenced gene cassettes carried by class 1 integrons are predicted to encode AMR [@zhangConservedPhylogeneticDistribution2018], predominantly, antibiotic-modifying enzymes that don't interfere with host cellular signaling pathways, such as beta-lactamases and aminoglycoside nucleotidyltransferases [@ghalyPerilPromiseIntegrons2020].
Recently, targeted metagenomic sequencing of class 1 integron gene cassettes in soil collected from Antarctica and Australia revealed extremely high sequence diversity, with 4,000--18,000 unique gene cassettes recovered per 0.3 g of soil [@ghalyHighDiversityRapid2019].
The high sequence diversity of C1I gene cassettes in soil, along with the high prevalence of ARGs carried by C1I gene cassettes, suggests a core **resistome** carried by these integrons, complemented by accessory ARGs that may be influenced by environmental selective pressures, such as macrolide antibiotics.

Macrolides have been identified as critically important by the World Health Organization because of their frequent use in healthcare and agriculture, and because of their status as the sole or one of the few remaining treatments for serious human bacterial infections [@worldhealthorganizationCriticallyImportantAntimicrobials2017].
Macrolide antibiotics target both gram-positive and gram-negative bacteria, and are most commonly used to treat community-acquired pneumonia (*Streptococcus pneumoniae*), soft-tissue infections ~~(*Staphylococcus aureus*)~~, and Campylobacteriosis.
Some macrolides are also prescribed to prevent secondary bacterial infections in cases of ~~severe~~ viral or fungal infection; most-recently, azithromycin has been prescribed to prevent secondary bacterial pneumonia in patients with SARS-CoV-2 infection in China [@guanClinicalCharacteristicsCoronavirus2020] ~~and in many other nations~~.
Many macrolide ARGs in human pathogens are known to be carried on plasmids (*msrE*, *mphE*, *ermB*), and some are mobilized by C1I gene cassettes (*ereA2*) [@fyfeResistanceMacrolideAntibiotics2016].
Wastewater treatment plants (**WWTPs**), in particular, are a reservoir of macrolide antibiotic pollution [@cheMobileAntibioticResistome2019].

Macrolide antibiotics are common contaminants of the influent and effluent of wastewater treatment plants:
Azithromycin, clarithromycin, and erythromycin are frequently detected at ng/L levels in WWTP influent, and are incompletely removed during the treatment process [@gobelOccurrenceSorptionBehavior2005; @gobelFateSulfonamidesMacrolides2007].
Due to their large molecular structure and positive charge, macrolides are effective at binding to negatively charged sewage particulates, and are consequently sequestered in ~~returned activated~~ sewage sludge [@gobelOccurrenceSorptionBehavior2005; @loganathanContaminationProfilesMass2009] at sub-mg/kg dry-weight levels.
Concerningly, there is an opportunity for macrolide-contaminated **biosolids** (treated sewage sludge) to select for AMR in agricultural soil [@sabourinUptakePharmaceuticalsHormones2012] through its widespread use an organic fertilizer.
The goal of this study is to assess the risk of long-term exposure of macrolide antibiotics to promote AMR in the soil mobile resistome, at a dosage that resembles biosolid carryover (0.1 mg/kg soil) and a dosage that is unrealistic under most exposure scenarios (10 mg/kg soil).

### Methods WIP

In Spring 2010, a series of microplots were established at the London Research & Development Centre in London, ON:
These microplots were comprised of 2m^2 fibreglass frames, filled with a silt loam soil commonly used in agriculture, in a location with no recent history of exposure to manure or biosolids [@toppReducedPersistenceMacrolide2016].

### Hypothesis and research plan widespread

In spring 2010, twelve 2 m^2 soil microplots were established in London, ON, and filled with silt loam soil as previously described [@toppReducedPersistenceMacrolide2016].
To investigate the effects of long-term exposure of agricultural soil to macrolide antibiotics on AMR, four of the soil microplots received a combination of three macrolide antibiotics (azithromycin, **AZM**; clarithromycin, **CLR**; erythromycin, **ERY**) at 0.1 mg/kg soil, four plots received the same combination at 10 mg/kg, and four plots were left untreated.
Each year until present, the soil microplots have received the same annual application of antibiotics, and soil core samples have been taken immediately prior to application, and within an hour (0 days), 7 days, and 30 days post-application.
Accelerated biodegradation of all three of the applied macrolides was previously observed in plots with five years of historic exposure to 10 mg/kg macrolides, and of erythromycin and clarithromycin in plots that were exposed to 0.1 mg/kg macrolides [@toppReducedPersistenceMacrolide2016], indicating that these compounds are bioavailable to the soil bacterial community.

A functional metagenomics investigation of these microplots has identified novel ARGs involved in macrolide, aminoglycoside, beta-lactam, and sulfonamide resistance  [@Lau2017], and quantitative PCR (**qPCR**) has revealed significant amplification of ARGs and mobile genetic elements (e.g. *intI1*, *tnpA*, *IS26*) in the plots exposed to 10 mg/kg antibiotics, but not the 0.1 mg/kg or untreated plots [@lauImpactsMultiyearField2020].
The amplification of both macrolide ARGs and ARGs that are not known to confer resistance to macrolide antibiotics in these plots (e.g. *sul1*, *aadA2*, *qacH*, *strB*) strongly implies a co-selection process, whereby resistance to other classes of antimicrobials is being selected for due to genetic linkage with macrolide ARGs.
The main goals of my research project are a) to determine if mobile genetic elements are involved in this co-selection process, and b) to identify the organisms in which ARGs are amplified and disseminated in response to macrolide exposure.
I hypothesize that plasmids and C1Is are responsible for facilitating the co-selection of macrolide ARGs and ARGs of other drug classes in these soil microplots, and that ~~members of the ESKAPE pathogens are responsible for the dissemination of AMR in the soil microplots~~.

**Objective 1**:
My first objective is to determine if C1Is facilitate the co-selection of macrolide ARGs and ARGs of other drug classes in macrolide-exposed soil.
C1Is are good candidates for facilitating this process for three reasons:
1) Macrolide ARGs are known to be carried by C1I gene cassettes [@fyfeResistanceMacrolideAntibiotics2016];
2) The C1I integrase gene *intI1* is amplified in the microplots exposed to 10 mg/kg macrolides [@lauImpactsMultiyearField2020];
3) ARGs that confer resistance to other classes of antimicrobials, and are carried by C1I gene cassettes, are amplified in the 10 mg/kg plots [@lauImpactsMultiyearField2020].
I predict that C1Is carrying both macrolide ARGs and other ARGs will be more abundant in plots with greater exposure to macrolide antibiotics.
I will investigate this by targeted metagenomic sequencing of C1I gene cassettes in each soil microplot.

**Objective 2**:
My second objective is to investigate if plasmids are involved in the co-selection of macrolide ARGs and ARGs of other drug classes in macrolide-exposed soil.
Plasmids are likely involved in this process, because many of the ARGs (e.g. *msrE*, *mphE*) and mobile genetic elements (e.g. *intI1*, *tnpA*, *IS26*) that were amplified in the 10 mg/kg plots are commonly carried by plasmids [@fyfeResistanceMacrolideAntibiotics2016; @zhangConservedPhylogeneticDistribution2018; @partridgeMobileGeneticElements2018].
I predict that plasmids carry some of the amplified macrolide ARGs and ARGs of other drug classes in the soil microplots.
I will investigate this by exogenous plasmid DNA isolation (plasmid capture) of each soil microplot.

**Objective 3**:
My third objective is to identify the microorganism(s) responsible for disseminating the detected ARGs and mobile genetic elements in the macrolide-exposed soil.
The large majority of sequenced CI1s (96%) are carried by Gammaproteobacteria--- specifically, human pathogens in the families of *Enterobacteriaceae*, *Moraxellaceae*, and *Pseudomonadaceae* [@zhangConservedPhylogeneticDistribution2018].
Within these families, a few pathogens are known to carry ARGs that were amplified in the 10 mg/kg microplots, including *Acinetobacter baumannii*, *Klebsiella pneumoniae*, and *Pseudomonas aeruginosa* [@alcockCARD2020Antibiotic2019].
I predict that at least one species in these bacterial families is responsible for disseminating AMR in the 10 mg/kg macrolide plots.
I will investigate this by enumerating and enriching members of these families that are resistant to macrolide antibiotics in the 10 mg/kg microplots.
