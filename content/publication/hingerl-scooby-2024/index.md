---
title: 'scooby: Modeling multi-modal genomic profiles from DNA sequence at single-cell
  resolution'
authors:
- Johannes C. Hingerl
- Laura D. Martens
- Alexander Karollus
- Trevor Manz
- Jason D. Buenrostro
- Fabian J. Theis
- Julien Gagneur
date: '2024-09-01'
publishDate: '2024-11-15T17:08:50.378092Z'
publication_types:
- manuscript
publication: '*bioRxiv*'
doi: 10.1101/2024.09.19.613754
abstract: Understanding how regulatory DNA elements shape gene expression across individual
  cells is a fundamental challenge in genomics. Joint RNA-seq and epigenomic profiling
  provides opportunities to build unifying models of gene regulation capturing sequence
  determinants across steps of gene expression. However, current models, developed
  primarily for bulk omics data, fail to capture the cellular heterogeneity and dynamic
  processes revealed by single-cell multi-modal technologies. Here, we introduce scooby,
  the first model to predict scRNA-seq coverage and scATAC-seq insertion profiles
  along the genome from sequence at single-cell resolution. For this, we leverage
  the pre-trained multi-omics profile predictor Borzoi as a foundation model, equip
  it with a cell-specific decoder, and fine-tune its sequence embeddings. Specifically,
  we condition the decoder on the cell position in a precomputed single-cell embedding
  resulting in strong generalization capability. Applied to a hematopoiesis dataset,
  scooby recapitulates cell-specific expression levels of held-out genes and cells,
  and identifies regulators and their putative target genes through in silico motif
  deletion. Moreover, accurate variant effect prediction with scooby allows for breaking
  down bulk eQTL effects into single-cell effects and delineating their impact on
  chromatin accessibility and gene expression. We anticipate scooby to aid unraveling
  the complexities of gene regulation at the resolution of individual cells.
links:
- name: URL
  url: https://www.biorxiv.org/content/10.1101/2024.09.19.613754v2
---
