# Computational Biology Datasets Suitable For Machine Learning
This is a curated list of computational biology datasets that have been pre-processed for machine learning.
This list is a work in progress, please submit a pull request for any dataset you would like to advertise!

## Genotyping
|Name | Description | Comments |
|:-:|---|---|
|[The Cancer Genome Atlas](https://cancergenome.nih.gov/)| Variety of Cancer Data  | most cancer types have 100-1000 samples  |
|[NIH GDC](https://gdc-portal.nci.nih.gov/)| Cancer, many types of genomic data  |   |
|[UK Biobank](http://www.ukbiobank.ac.uk/about-biobank-uk/) |   |   |
|[European Genome-Phenome Archive](https://www.ebi.ac.uk/ega/datasets)| |  |
|[METABRIC](http://www.cbioportal.org/study?id=brca_metabric#summary)| The genomic profiles (somatic mutations [targeted sequencing], copy number alterations, and gene expression) of 2509 breast cancers.| |
|[HapMap](https://www.genome.gov/hapmap/)| | |
|[23andMe](http://www.biorxiv.org/content/early/2017/04/19/127241)| 2280 Public Domain Curated Genotypes | |
|[Mice](http://wp.cs.ucl.ac.uk/outbredmice/heterogeneous-stock-mice/) | SNPs, 2000+ samples | 4 generations. It might be possible to learn a family structure out of the data.  |
|[Arabidopsis](https://www.arabidopsis.org/download/) | SNPs, 100+ phenotypes | |

## Promoter-Enhancer Pairs
|Name | Description | Comments |
|:-:|---|---|
|[TargetFinder](https://github.com/shwhalen/targetfinder)|~100,000 DNA-DNA interaction pairs | |

## Gene/Protein Expression
|Name | Description | Comments |
|:-:|---|---|
|[GEO](http://www.ncbi.nlm.nih.gov/geo/) | Main place for NCBI data |  |
|[ENCODE](http://www.encodeproject.org/) | Variety of assays to identify functional elements | |
|[ArrayExpress](http://www.ebi.ac.uk/arrayexpress/) | DNA sequencing, gene/protein expression, epigenetics | |
|[Cytometry	Continuous](http://science.sciencemag.org/content/308/5721/523) | flow cytometry data of 11 proteins+phospholipids, Discretized and cleaned data available offline	| Classical benchmark dataset for learning graphical models; contains known errors |
|[Transcription factor binding](http://www.pnas.org/content/106/51/21521.abstract?tab=ds) |	ChIP-Seq data on 12 TFs |	 |
|[GTEx](http://www.gtexportal.org/home/) | Landmark study for EQTL analysis | |
|[PharmacoGenomics DB](https://www.pharmgkb.org/)	|	| |
|[ProteomeXChange](http://www.proteomexchange.org/)| | |
|[BeatAML](https://www.nature.com/articles/s41586-018-0623-z)| whole-exome sequencing, RNA sequencing and analyses of ex vivo drug sensitivity | 672 tumour specimens collected from 562 patients |

## Single-cell Data
|Name | Description | Comments |
|:-:|---|---|
|[Single-cell expression atlas](https://www.ebi.ac.uk/gxa/sc/) | | |
|[scPerturb](https://www.nature.com/articles/s41592-023-02144-y) | single-cell perturbation-response datasets | harmonized and preprocessed across 44 original datasets |

## Regulatory Networks
|Name | Description | Comments |
|:-:|---|---|
|[TRRUST](http://www.grnpedia.org/trrust/)| manually curated database of human transcriptional regulatory network |  |
|[Yeast Network](http://science.sciencemag.org/content/353/6306/aaf1420/tab-pdf)| 23-million yeast 2-hybrid experiments to investigate genetic interactions |  |
|[Perturb-Seq](http://www.sciencedirect.com/science/article/pii/S0092867416316105)| Integrated model of perturbations, single cell phenotypes, and epistatic interactions |  |
|[KEGG Metabolic Regulatory Network (Undirected)](https://archive.ics.uci.edu/ml/datasets/KEGG+Metabolic+Reaction+Network+%28Undirected%29) | 65554 instances, 29 attributes each |  |
|[KEGG Metabolic Regulatory Network (Directed)](https://archive.ics.uci.edu/ml/datasets/KEGG+Metabolic+Relation+Network+%28Directed%29) |53414 instance, 24 attributes each |  |

## Images
|Name | Description | Comments |
|:-:|---|---|
|[The Cancer Imaging Archive](http://www.cancerimagingarchive.net/)| Extracts the images from the TCGA data | |
|[Multiple Myeloma DREAM Challenge](https://www.synapse.org/#!Synapse:syn6187098/wiki/401884)| Challenge to identify Multiple Myeloma Patients |  |
|[Breast Cancer Wisconsin (Diagnostic) Data Set](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data)| Predict whether the cancer is benign or malignant | |
|[DDSM](http://marathon.csee.usf.edu/Mammography/Database.html)|Mammogram Database | |
|[Kaggle Soft Tissue Sarcomas](https://www.kaggle.com/4quant/soft-tissue-sarcoma)| Preprocessed subset of the TCIA study "Soft Tissue Sarcoma" | segmentation task |
|[Kaggle Cervical Cancer Screening](https://www.kaggle.com/c/intel-mobileodt-cervical-cancer-screening)| Classify cervix type from images| |
|[CMELYON17](https://camelyon17.grand-challenge.org/) | Pathology challenge - automated detection and classification of breast cancer metastases in whole-slide images of histological lymph node sections| |
|[Grand Challenges](https://grand-challenge.org/all_challenges/) | Datasets from biomedical image analysis competitions | |
|[Breast Cancer MRI Dataset](https://sites.duke.edu/mazurowski/resources/breast-cancer-mri-dataset/) | Demographic, clinical, pathology, treatment, outcomes, and genomic data + MRI images | |

## fMRI
|Name | Description | Comments |
|:-:|---|---|
|[ENGIMA Cerebellum](https://my.vanderbilt.edu/enigmacerebellum/)| Goal: Examine the relationships between regional atrophy and motor and cognitive dysfunction | |
|[Seizure Prediction](https://www.kaggle.com/c/melbourne-university-seizure-prediction/data) | Goal: Classify EEG time series into pre-seizure vs. interictal (i.e., not preceding a seizure). | |

## Electronic Medical Records
|Name | Description | Comments |
|:-:|---|---|
|[MIMIC](https://mimic.physionet.org/)| 59,000 EHRs |  |
|[UCI Diabetes](https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008)| 130 US hospital data for 1999-2008| |
|[i2b2](https://www.i2b2.org/NLP/DataSets/Main.php) | Clinical notes only, designed for NLP tasks | |
|[PhysioNet](https://www.physionet.org/physiobank/database/) |  | |
|[Metadata Acquired from Clinical Case Reports (MACCRs)](https://www.nature.com/articles/sdata2018258) | 3,100 curated clinical case reports spanning 15 disease groups and more than 750 reports of rare diseases | |
|[eICU](https://www.nature.com/articles/sdata2018178)| 200k EHRs | |
|[All of Us](https://databrowser.researchallofus.org/)| >250k EHRs, some genomic data | |
|[PMC-Patients](https://www.nature.com/articles/s41597-023-02814-8)| 167k patient summaries with 3.1 M patient-article relevance annotations and 293k patient-patient similarity annotations | |

## Radiographs
|Name | Description | Comments |
|:-:|---|---|
|[CheXPert](https://stanfordmlgroup.github.io/competitions/chexpert/) | 200k chest radiographs |  Competition and leaderboard associated |
|[MIMIC-CXR](https://arxiv.org/abs/1901.07042) | ~400k chest x-rays, 14 labels | Data on PhysioNet |
|[PadChest](http://bimcv.cipf.es/bimcv-projects/padchest/) | 160k chest x-rays, 174 different findings | |

## Protein-Protein Interactions
|Name | Description | Comments |
|:-:|---|---|
|[HINT (High-quality INTeractomes)](http://hint.yulab.org/) |  curated compilation of high-quality protein-protein interactions from 8 interactome resources | |

## Longitudinal Studies
|Name | Description | Comments |
|:-:|---|---|
|[National Population Health Survey](http://www.statcan.gc.ca/eng/survey/household/3225)| Longitudinal Survey that collects health information via surveys every two years. | |

## Protein Structure
|Name | Description | Comments |
|:-:|---|---|
|[ProteinNet](https://github.com/aqlaboratory/proteinnet) | Standardized dataset for learning protein structure. Includes sequences, structures, alignments, PSSMs, and standardized train/test/valid splits. | |

## Natural Language Data
|Name | Description | Comments |
|:-:|---|---|
|[BioASQ](http://www.bioasq.org/) | Abstracts of medical articles (from PubMed); ontologies of medical concepts. | Tasks: MLC, QA. |
|[Cases](http://www.casesdatabase.com/) | Articles from medical case studies. | |
|[UPMC Pathology](http://path.upmc.edu/cases.html) | UPMC Pathology case studies. | |

## Therapeutics
|Name | Description | Comments |
|:-:|---|---|
|[Therapeutic Data Commons](https://tdcommons.ai/)| Many preprocessed datasets for therapeutic discovery, including target discovery, activity modeling, efficacy and safety, and manufacturing. | Available as Python modules. |
|[Cancer Omics Drug Experiment Response Dataset](https://github.com/PNNL-CompBio/coderdata)| Molecular datasets paired with corresponding drug sensitivity data | Seeks to standardize datasets of cancer drug responses into a [standard schema](https://github.com/PNNL-CompBio/coderdata/blob/main/schema/README.md) |
