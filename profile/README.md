# Pathways+Omics

**Computational biology at Oregon Health & Science University · Portland, Oregon**

We develop computational methods to understand how molecular changes alter cell behavior in cancer. Our work brings together biological pathway knowledge, multi-omics measurements, and machine learning to connect molecular profiles with the mechanisms that produce them.

Pathways+Omics brings together research led by Emek Demir and collaborators at OHSU. This organization hosts software and analysis workflows spanning pathway informatics, regulatory networks, cancer genomics, and multimodal single-cell analysis.

## Research

- **Pathways and biological knowledge.** Representing molecular interactions in computable forms and using prior knowledge to interpret omics data, with contributions to resources and standards including Pathway Commons and BioPAX.
- **Regulatory and signaling networks.** Inferring transcription factor activity and generating mechanistic hypotheses from gene expression, proteomic, and phosphoproteomic measurements.
- **Cancer-associated molecular programs.** Learning the expression patterns associated with driver alterations and investigating when these patterns transfer across cohorts and from bulk tumors to individual cells.
- **Multimodal single-cell learning.** Developing generative models that integrate RNA, chromatin accessibility, protein, and other measurements to study cell states across partially observed datasets.
- **Computational imaging.** Developing tools for digital pathology and quantitative analysis of tissue organization.

## Current directions

Our current work explores cancer cell states, tumor heterogeneity, and treatment response through multimodal data analysis, computational imaging, and interpretable machine learning. We are also developing approaches for studying biological variation across cells, tissues, and patient cohorts.

## Software

| Project | Focus |
| :--- | :--- |
| [UniVI](https://github.com/Ashford-A/UniVI) | Mixture-of-experts variational autoencoders for multimodal single-cell integration, cross-modal reconstruction, and reference-to-query mapping. |
| [UniVII](https://github.com/Ashford-A/UniVII) | An extension of UniVI with modular infrastructure for additional data types and analyses, and model development. |
| [scOPE](https://github.com/Ashford-A/scOPE) | Learning driver-associated expression programs in bulk tumors and evaluating their transfer to single-cell transcriptomes. |
| [MiroSCOPE](https://github.com/ohsu-cedar-comp-hub/qupath_monaillabel_plugin) | AI-assisted annotation of functional tissue units in digital pathology, with a QuPath interface and [MONAI Label backend](https://github.com/ohsu-cedar-comp-hub/monailabel_cedar_app). |
| [Priori / regulon-enrichment](https://github.com/Pathways-Omics/regulon-enrichment) | Predicting transcription factor activity from RNA-seq using prior biological knowledge and regulatory relationships. |
| [PRECEPTS1](https://github.com/Pathways-Omics/PRECEPTS1) | Workflows using biological feature trees and machine learning to predict cancer-associated mutation status from RNA-seq. |
| [CausalPath](https://github.com/PathwayAndDataAnalysis/causalpath) | Inferring candidate causal signaling relationships from molecular profiles using curated pathway knowledge. |

UniVI, UniVII, and scOPE are primarily developed in [Andrew Ashford's repositories](https://github.com/Ashford-A), linked above. Use those repositories for current releases, documentation, and issue reporting. Copies under Pathways-Omics may not contain the latest updates.

See each repository for installation, examples, data requirements, licensing, and citation instructions. Related software and earlier project repositories are also available through [OHSU Computational Biology](https://github.com/ohsu-comp-bio).

Try the [UniVI RNA–protein explorer](https://huggingface.co/spaces/ashford-andrew/UniVI-explorer) and [UniVI RNA–ATAC Multiome explorer](https://huggingface.co/spaces/ashford-andrew/UniVI-Multiome-explorer) for interactive examples.

## Foundations: BioPAX and Pathway Commons

Our work builds on Emek Demir's earlier contributions to community pathway informatics. Emek led the development of BioPAX and helped develop Pathway Commons alongside collaborators across institutions. These are shared community efforts with their own project homes.

| Resource | What it provides | Links |
| :--- | :--- | :--- |
| **BioPAX — Biological Pathway Exchange** | A standard language for representing and exchanging biological pathway knowledge, including molecular interactions, reactions, and regulatory relationships. It allows databases and software to describe biology in a common, computable format. | [Project](https://www.biopax.org/) · [Foundational paper](https://doi.org/10.1038/nbt.1666) |
| **Pathway Commons** | A resource that brings together pathway and interaction data from multiple public databases, using BioPAX to integrate their representations and make the information accessible for analysis. | [Project](https://www.pathwaycommons.org/) · [Foundational paper](https://doi.org/10.1093/nar/gkq1039) |
| **Paxtools** | A Java toolkit for reading, writing, querying, and manipulating pathway models in BioPAX. It provides software infrastructure used by Pathway Commons and other pathway-analysis tools. | [GitHub](https://github.com/BioPAX/Paxtools) · [Paper](https://doi.org/10.1371/journal.pcbi.1003194) |

**BioPAX defines how pathway knowledge is represented; Pathway Commons brings that knowledge together.** Both underpin approaches that connect molecular measurements with established biology.

## Selected publications and collaborative work

- **Unifying multimodal single-cell data with a mixture-of-experts β-variational autoencoder framework.** Ashford et al. *Genome Research*, 2026. [Paper](https://doi.org/10.1101/gr.281431.125)
- **scOPE identifies which driver-associated expression programs transfer from bulk tumors to single cells.** Ashford, Lapadat & Demir. *bioRxiv*, 2026. [Preprint](https://doi.org/10.64898/2026.07.24.740598)
- **MiroSCOPE: An AI-driven digital pathology platform for annotating functional tissue units.** Fenner et al. *bioRxiv*, 2025. [Preprint](https://doi.org/10.1101/2025.07.11.664228)
- **Predicting transcription factor activity using prior biological information.** Yashar, Estabrook et al. *iScience*, 2024. [Paper](https://doi.org/10.1016/j.isci.2024.109124)
- **A framework for considering prior information in network-based approaches to omics data analysis.** Somers et al. *Proteomics*, 2023. [Paper](https://doi.org/10.1002/pmic.202200402)
- **Asxl1 deletion disrupts MYC and RNA polymerase II function in granulocyte progenitors.** Braun, Estabrook et al. *Leukemia*, 2023. [Paper](https://doi.org/10.1038/s41375-022-01792-x)
- **Systematic interrogation of mutation groupings reveals divergent downstream expression programs within key cancer genes.** Grzadkowski et al. *BMC Bioinformatics*, 2021. [Paper](https://doi.org/10.1186/s12859-021-04147-y)
- **Causal interactions from proteomic profiles: Molecular data meet pathway knowledge.** Babur et al. *Patterns*, 2021. [Paper](https://doi.org/10.1016/j.patter.2021.100257)
- **Using Biological Pathway Data with Paxtools.** Demir et al. *PLOS Computational Biology*, 2013. [Paper](https://doi.org/10.1371/journal.pcbi.1003194)
- **Pathway Commons, a web resource for biological pathway data.** Cerami et al. *Nucleic Acids Research*, 2011. [Paper](https://doi.org/10.1093/nar/gkq1039)
- **The BioPAX community standard for pathway data sharing.** Demir et al. *Nature Biotechnology*, 2010. [Paper](https://doi.org/10.1038/nbt.1666)

## Connect

For software questions and bug reports, use the relevant repository's issue tracker. For research and collaboration inquiries, see [Emek Demir's OHSU profile](https://www.ohsu.edu/people/emek-demir-phd).

[Emek Demir · LinkedIn](https://www.linkedin.com/in/emekdemir/) · [Andrew J. Ashford · LinkedIn](https://www.linkedin.com/in/andrew-ashford-589376133/)

See our [public organization members](https://github.com/orgs/Pathways-Omics/people).
