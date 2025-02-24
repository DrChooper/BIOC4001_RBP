# BIOC4001_RBP

## Description
**BIOC4001** is an advanced unit in biochemistry and molecular biology at UWA, focusing on recent developments in the field. The unit covers topics such as protein interactions, non-coding RNAs, cell signalling, and organelles. Students develop and present a lecture on an aspect of one of these topics through independent readings, highlighting the research that has led to our current understanding of the topic. 

The main academic objective is for students to gain an understanding and appreciation of how knowledge in biochemistry and molecular biology progresses. 

This repository contains bits and pieces on RNA-binding proteins (RBPs), essential regulators of RNA metabolism —including splicing, transport, localisation, and stability— that influence gene expression and various cellular processes. RBPs recognise specific RNA sequences or structures through domains such as RNA-recognition motifs (RRMs), double-stranded RNA-binding motifs (dsRBMs), and zinc fingers. Disruptions in RBP functions can lead to diseases, highlighting their significance in maintaining cellular health. Advancements in technologies, such as cross-linking immunoprecipitation (CLIP) methods, have enhanced the study of these interactions, providing detailed maps of RBP binding sites on RNAs. Understanding RNA-protein interactions is crucial for insights into gene regulation and potential exploitable targets for medical and biotechnological applications.

## Quick Connections

- [Lecture Overview](#lecture-overview)
- [Reading Materials](#reading-materials)
- [WorkShop2(SOON)](more/WorkShop2.md)


## Lecture Overview
#### 1. General Features of Nucleic-Acid-Binding Proteins
- Definition and significance of nucleic-acid-binding proteins.
- Types of binding proteins and their interactions with RNA and DNA.
- Modular nature and functional domains (e.g., RRMs, zinc fingers, dsRBMs).
---

#### 2. Function and Specificity of RNA-Binding Proteins
- Protein modularity and function relationship
- (1) Structure-specific recognition (e.g., stem-loop binding proteins).
- (2) Sequence-specific recognition (e.g., PPR proteins).
- (3) RNA-led recognition (e.g. Arganaute, CRISPR)
- Examples of proteins and their function
---

#### 3. Biotechnological exploitation opportunities
- RBP in synthetic biology
- Opportunity to modulate gene expression at the DNA, RNA, and protein levels.
---

#### 4. Identifying RNA-Protein Interactions
- Methods for identifying RBP or RNA binding partners (CLIP, RNA pull down)
- Crosslinking techniques (e.g., CLIP and versions of it)
---

#### 5. Quantifying RNA-Protein Interactions
- Experimental methods:
  - Electrophoretic Mobility Shift Assays (EMSA).
  - Fluorescence polarization.
  - Microscale thermophoresis.
  - Surface plasmon resonance.
- Importance of dissociation constants (Kd) in quantifying binding strength and functionality.
--- 

### Reading Materials
They are some fundamental concepts in these papers rather then the newest discoveries. This will help understand the subject.

**1. [RNA-binding proteins: modular design for efficient function](https://europepmc.org/articles/PMC5507177)**  
*Lunde BM, Moore C, Varani G. Nat Rev Mol Cell Biol. 2007 Jun;8(6):479-490.*  
This comprehensive review discusses the modular architecture of RNA-binding proteins (RBPs) and how their structural domains facilitate diverse biological functions. 

**2. [A brave new world of RNA-binding proteins](https://www.nature.com/articles/nrm.2017.130)**  
*Hentze MW, Castello A, Schwarzl T, Preiss T. Nat Rev Mol Cell Biol. 2018 May;19(5):327-341.*  
This article explores the expanding knowledge of RBPs, highlighting new discoveries and their implications in cellular biology.

**3. [Beyond CLIP: advances and opportunities to measure RBP–RNA and RNA–RNA interactions](https://academic.oup.com/nar/article/47/11/5490/5488019?)**  
*Lin Y, Miles WO. Nucleic Acids Res. 2019 Jun 20;47(11):5490-5501.*  
This paper reviews recent technological advancements in studying RBP–RNA and RNA–RNA interactions, moving beyond traditional crosslinking and immunoprecipitation (CLIP) methods. 


---
#### Extended reading list - not a must but if you are interested in this topic

**1. [Alternative Splicing Modulates Cancer by Disrupting Protein–Protein Interactions and Mimic Mutations](https://www.cell.com/cell-reports/fulltext/S2211-1247(17)31104-X)**  
*Climente-González H, Porta-Pardo E, Godzik A, Eyras E. Genome Res. 2017 Jan;27(3):549-557.*

RNA-binding proteins (RBPs) regulate alternative splicing by interacting with pre-mRNA to influence exon inclusion or exclusion. Dysregulation of RBPs can lead to aberrant splicing linked to diseases like cancer, making them key targets for therapeutic intervention.

**2. [SUPPA2: Fast, Accurate, and Uncertainty-Aware Differential Splicing Analysis Across Multiple Conditions](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1417-1)**  
*Trincado JL, Pagés A, Granneman S, Eyras E. Genome Biol. 2018 Nov;19:40.*

RNA-binding proteins (RBPs) regulate gene expression by controlling RNA splicing, transport, localisation, and stability. They achieve this through diverse RNA-binding domains, enabling interactions with various RNA targets to modulate cellular processes.

**3.[Pentatricopeptide Repeat RNA-Binding Protein](https://www.annualreviews.org/doi/10.1146/annurev-arplant-050213-040159)**  
*Barkan A, Small I. Annual Review of Plant Biology. 2014;65:415-442.*

Pentatricopeptide repeat (PPR) proteins, comprising over 400 members in most land plant species, play crucial roles in organellar RNA metabolism, including splicing, editing, stability, and translation. They recognise RNA sequences through modular base-specific contacts will help match proteins to their RNA targets and enable the design of artificial PPR proteins to target specific transcripts.

**4. [RNA-binding proteins: Splicing Regulators and RNA Metabolism](https://www.med.upenn.edu/dreyfusslab/publications/2008GlisovicFEBSLetters.pdf)**  
*Glisovic T, Bachorik JL, Yong J, Dreyfuss G. FEBS Lett. 2008;582(14):1977-1986.*


RNA-binding proteins (RBPs) in post-transcriptional gene regulation, influence processes such as splicing, editing, polyadenylation, stability, transport, and localisation of pre-mRNAs and mRNAs. Their diverse RNA-binding domains and interactions with other proteins allow for the formation of unique ribonucleoprotein complexes, essential for the maturation and function of each RNA.

**6. [A computational study of off-target effects of RNA interference](https://academic.oup.com/nar/article/33/6/1834/2401265?)**  
*Shibin et al., NAR, Volume 33, Issue 6, 1 April 2005, Pages 1834–1847*

This study analyses the specificity of RNA interference (RNAi) and highlights the potential for off-target gene silencing due to partial sequence complementarity between siRNAs and unintended mRNA targets.

**7. [Methods Favoring Homology-Directed Repair Choice in Response to CRISPR/Cas9 Induced-Double Strand Breaks](https://www.mdpi.com/1422-0067/21/18/6461)**  
*Riesenberg S, Maricic T. Int J Mol Sci. 2020 Sep;21(18):6461.*

A review on DNA double-strand break repair pathways, focusing on strategies to enhance homology-directed repair over non-homologous end joining in CRISPR/Cas9 gene editing to improve precision.

**9. [Quantitative Protein–Nucleic Acid Interaction Monitoring](https://rnajournal.cshlp.org/content/17/1/14.full.pdf)**  
*Pagano JM, Clingman CC, Ryder SP. RNA. 2011 Jan;17(1):14-20.*

The study discusses the necessity of sequence-specific protein–nucleic acid recognition in gene expression and reviews various quantitative methods to analyse these interactions.

**10. [Argonaute proteins on alternative RNA splicing](https://wires.onlinelibrary.wiley.com/doi/10.1002/wrna.1264)**  
*Batsché, E. and Ameyar-Zazoua, M. (2015),WIREs RNA, 6: 141-156.*

The article explores the potential of engineered transfer RNAs (tRNAs) in suppressing premature termination codons, with implications for restoring full-length protein production, including in RNA-binding protein (RBP)-associated disorders where nonsense mutations disrupt RNA regulation and processing.