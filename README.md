# Awesome Large Biology Models [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

<font size=5><center><b> Table of Contents </b> </center></font>
- [Awesome Models and Codes](#awesome-papers-and-codes)
  - [DNA Models](#dna-models)
  - [RNA Models](#rna-models)
  - [Protein Models](#protein-models)
  - [Single-cell Models](#single-cell-models)
  - [Biological Text Models](#biological-text-models)
- [Awesome Datasets](#awesome-datasets)
  - [General Datasets](#general-datasets) 
  - [DNA Datasets](#dna-datasets)
  - [RNA Datasets](#rna-datasets)
  - [Protein Datasets](#protein-datasets)
  - [Single-cell Datasets](#single-cell-datasets)
  - [Biological Text Datasets](#biological-text-datasets)
---

## Awesome Papers and Codes

### DNA Models
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Predicting RNA-seq coverage from DNA sequence as a unifying model of gene regulation**](https://www.biorxiv.org/content/10.1101/2023.08.30.555582v1) | BioArxiv | 2023-09-01 | - | - |
| [**EpiGePT: a Pretrained Transformer model for epigenomics**](https://arxiv.org/abs/2307.05628) | BioArxiv | 2023-07-15 | [Website](https://health.tsinghua.edu.cn/epigept/) | - |
| [**DNAGPT: A Generalized Pre-trained Tool for Versatile DNA Sequence Analysis Tasks**](https://arxiv.org/abs/2307.05628) | Arxiv | 2023-07-11 | [Github](https://github.com/TencentAILabHealthcare/DNAGPT) | - |
| [**Hyenadna: Long-range genomic sequence modeling at single nucleotide resolution**](https://arxiv.org/abs/2306.15794) | Arxiv | 2023-06-27 | [Github](https://github.com/HazyResearch/hyena-dna) | [Blog](https://hazyresearch.stanford.edu/blog/2023-06-29-hyena-dna) |
| [**DNABERT-2: Efficient Foundation Model and Benchmark For Multi-Species Genome**](https://arxiv.org/abs/2306.15006) | Arxiv | 2023-06-26 | [Github](https://github.com/Zhihan1996/DNABERT_2) | [GUE](https://drive.google.com/file/d/1GRtbzTe3UXYF1oW27ASNhYX3SZ16D7N2/view?usp=sharing) |
| [**The Nucleotide Transformer: Building and Evaluating Robust Foundation Models for Human Genomics**](https://www.biorxiv.org/content/biorxiv/early/2023/03/09/2023.01.11.523679.full.pdf) | BioRxiv | 2023-01-11 | [Github](https://github.com/instadeepai/nucleotide-transformer) | - |
| [**GenSLMs: Genome-scale language models reveal SARS-CoV-2 evolutionary dynamics**](https://www.biorxiv.org/content/10.1101/2022.10.10.511571v1)| BioRxiv | 2022-10-11 | - | - |
| [**Effective gene expression prediction from sequence by integrating long-range interactions**](https://www.nature.com/articles/s41592-021-01252-x) | Nature Methods | 2021-10-04 | [Github](https://github.com/deepmind/deepmind-research/tree/master/enformer) | - |
| [**DNABERT: pre-trained Bidirectional Encoder Representations from Transformers model for DNA-language in genome**](https://academic.oup.com/bioinformatics/article/37/15/2112/6128680) | Bioinformatics | 2021-02-04 | [Github](https://github.com/jerryji1993/DNABERT) | - |


### RNA Models
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**An RNA foundation model enables discovery of disease mechanisms and candidate therapeutics**](https://www.biorxiv.org/content/10.1101/2023.09.20.558508v1.full.pdf) | BioRxiv | 2023-09-26 | - | - |
| [**CodonBERT: Large Language Models for mRNA Design and Optimization**](https://www.biorxiv.org/content/biorxiv/early/2023/09/12/2023.09.09.556981.full.pdf) | Arxiv | 2023-09-09 | - | - |
| [**UNI-RNA: UNIVERSAL PRE-TRAINED MODELS REVOLUTIONIZE RNA RESEARCH**](https://www.biorxiv.org/content/biorxiv/early/2023/07/12/2023.07.11.548588.full.pdf) | BioArxiv | 2023-07-11 | - | - |
| [**Self-supervised learning on millions of pre-mRNA sequences improves sequence-based RNA splicing prediction**](https://www.biorxiv.org/content/biorxiv/early/2023/05/09/2023.01.31.526427.full.pdf) | Arxiv | 2023-01-31 | [Github](https://github.com/biomed-AI/SpliceBERT) | - |


### Protein Models
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**Genome-wide prediction of disease variant effects with a deep protein language model**](https://www.nature.com/articles/s41588-023-01465-0) | Nature Genetics | 2023-08-10 | [Github](https://github.com/ntranoslab/esm-variants) | Sequence |
| [**De novo design of protein structure and function with RFdiffusion**](https://academic.oup.com/bioinformatics/article/37/15/2112/6128680) | Nature | 2023-07-11 | [Github](https://github.com/RosettaCommons/RFdiffusion) | Structure |
| [**xTrimoPGLM: Unified 100B-Scale Pre-trained Transformer for Deciphering the Language of Protein**](https://www.biorxiv.org/content/biorxiv/early/2023/07/11/2023.07.05.547496.full.pdf) | Arxiv | 2022-07-05 | - | Sequence |
| [**OntoProtein: Protein Pretraining With Gene Ontology Embedding**](https://arxiv.org/pdf/2201.11147.pdf) | ICLR22 | 2022-06-30 | [Github](https://github.com/zjunlp/OntoProtein) | Sequence |
| [**Accurate proteome-wide missense variant effect prediction with AlphaMissense**](https://www.science.org/doi/10.1126/science.adg7492) | Science | 2023-09-19 | [Github](https://github.com/google-deepmind/alphamissense) | Sequence |
| [**Evolutionary-scale prediction of atomic-level protein structure with a language model**](https://www.science.org/doi/10.1126/science.ade2574) | Science | 2023-03-23 | [Github](https://github.com/facebookresearch/esm) | Sequence |
| [**Protein complex prediction with AlphaFold-Multimer**](https://www.biorxiv.org/content/10.1101/2021.10.04.463034v2) | BioArxiv | 2022-03-10 | [Github](https://github.com/jcheongs/alphafold-multimer) | Sequence |
| [**ProtGPT2 is a deep unsupervised language model for protein design**](https://www.nature.com/articles/s41467-022-32007-7) | Nature Communications | 2022-07-27 | - | Sequence |
| [**ProtTrans: Toward Understanding the Language of Life Through Self-Supervised Learning**](https://ieeexplore.ieee.org/document/9477085) | IEEE Transactions on Pattern Analysis and Machine Intelligence | 2022-10-01 | [Github](https://github.com/agemagician/ProtTrans) | Sequence |



### Single-cell Models
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**GeneCompass: Deciphering Universal Gene Regulatory Mechanisms with Knowledge-Informed Cross-Species Foundation Model**](https://www.biorxiv.org/content/10.1101/2023.09.26.559542v1.full.pdf) | BioArxiv | 2023-09-26 | [Github](https://github.com/bowang-lab/scGPT) | - |
| [**scgpt: Towards building a foundation model for single-cell multi-omics using generative ai**](https://www.biorxiv.org/content/biorxiv/early/2023/05/01/2023.04.30.538439.full.pdf) | Arxiv | 2023-04-30 | [Github](https://github.com/bowang-lab/scGPT) | - |
| [**scBERT as a large-scale pretrained deep language model for cell type annotation of single-cell RNA-seq data**](https://www.nature.com/articles/s42256-022-00534-z) | Nature Machine Intelligence | 2023-09-26 | [Github](https://github.com/TencentAILabHealthcare/scBERT) | - |


### Biological Text Models
|  Title  |   Venue  |   Date   |   Code   |   Notes  |
|:--------|:--------:|:--------:|:--------:|:--------:|
| [**GeneGPT: Augmenting Large Language Models with Domain Tools for Improved Access to Biomedical Information**](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10153281/) | Preprint | 2023-05-16 | [Github](https://github.com/ncbi/GeneGPT) | - |
| [**BioGPT: generative pre-trained transformer for biomedical text generation and mining**](https://academic.oup.com/bib/article-abstract/23/6/bbac409/6713511) | Briefings in Bioinformatics | 2022-12-24 | [Github](https://github.com/microsoft/BioGPT) | - |



## Awesome Datasets

### General Datasets
|  Name   |   Paper  |   Data type   |   Link   |   Notes   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| NCBI Database | - | DNA/RNA/Protein | [Link](https://www.ncbi.nlm.nih.gov/) | - |
| Ensembl Database | - | DNA/RNA/Protein | [Link](https://www.ensembl.org/index.html) | - |
| UCSC Database | - | DNA/RNA | [Link](https://genome.ucsc.edu/) | - |
| RCSB PDB Database | - | Protein | [Link](https://www.rcsb.org/) | - |
| Uniprot Database | - | Protein | [Link](https://www.uniprot.org/) | - |
| STRING Database | - | Protein | [Link](https://string-db.org/) | - |


### DNA Datasets
|  Name   |   Paper  |   Data type   |   Link   |   Notes   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| Genome Understanding Evaluation (GUE) | [**DNABERT-2: Efficient Foundation Model and Benchmark For Multi-Species Genome**](https://arxiv.org/abs/2306.15006) | Sequence Classification | [Link](https://drive.google.com/file/d/1GRtbzTe3UXYF1oW27ASNhYX3SZ16D7N2/view?usp=sharing) | - |


### RNA Datasets
|  Name   |   Paper  |   Data type   |   Link   |   Notes   |
|:--------|:--------:|:--------:|:--------:|:--------:|
| Genotype-Tissue Expression (GTEx) | [**The GTEx Consortium atlas of genetic regulatory effects across human tissues**](https://www.science.org/doi/full/10.1126/science.aaz1776#editor-abstract) | General | [Link](https://www.gtexportal.org/home/) | - |
| (Master database of All possible RNA sequences (MARS) | [**The Master Database of All Possible RNA Sequences and Its Integration with RNAcmap for RNA Homology Search**](https://www.biorxiv.org/content/10.1101/2023.02.01.526559v1.full.pdf) | General | [Link](http://zhouyq-lab.szbl.ac.cn/download/) | - |


### Protein Datasets
|  Name   |   Paper  |   Data type   |   Link   |   Notes   |
|:--------|:--------:|:--------:|:--------:|:--------:|
TBD

### Single-cell Datasets
|  Name   |   Paper  |   Data type   |   Link   |   Notes   |
|:--------|:--------:|:--------:|:--------:|:--------:|
TBD

### Biological text Datasets
|  Name   |   Paper  |   Data type   |   Link   |   Notes   |
|:--------|:--------:|:--------:|:--------:|:--------:|
TBD
