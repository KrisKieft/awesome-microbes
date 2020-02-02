# awesome-microbes

List of resources, including software packages (and the people developing these methods) for microbiome (16S), metagenomics (WGS, Shot-gun sequencing), and pathogen identification/detection/characterization.  [Contributions welcome...](https://github.com/stevetsa/awesome-microbes/blob/master/CONTRIBUTE.md)

Inspired by [awesome-single-cell](https://github.com/seandavi/awesome-single-cell/blob/master/README.md)

## 2019 Novel Coronavirus Resources 

### International Government Organization

[US Center for Disease Control](https://www.cdc.gov/coronavirus/index.html) - Situation Summary - "The Centers for Disease Control and Prevention (CDC) is closely monitoring an outbreak of respiratory illness caused by a novel (new) coronavirus first identified in Wuhan, Hubei Province, China. Chinese authorities identified the new coronavirus, which has resulted in thousands of confirmed cases in China, including cases outside Wuhan City. Additional cases have been identified in a growing number of other international locations, including the United States. There are ongoing investigations to learn more."

[World Health Organization](https://www.who.int/emergencies/diseases/novel-coronavirus-2019) - "This page is a one-stop shop for all information and guidance from WHO regarding the current outbreak of novel coronavirus (2019-nCoV) that was first reported from Wuhan, China, on 31 December 2019. Please visit this page for daily updates. WHO is working closely with global experts, governments and partners to rapidly expand scientific knowledge on this new virus, to track the spread and virulence of the virus, and to provide advice to countries and individuals on measures to protect health and prevent the spread of this outbreak." [Situation Reports](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports/)

[US National Institute of Allergy and Infectious Diseases](https://www.niaid.nih.gov/news-events/niaid-officials-discuss-novel-coronavirus-recently-emerged-china) - "Current studies at NIAID-funded institutions and by scientists in NIAID laboratories include efforts that build on previous work on SARS- and MERS-CoVs. For example, researchers are developing diagnostic tests to rapidly detect 2019-nCoV infection and exploring the use of broad-spectrum anti-viral drugs to treat 2019-nCoVs, the authors note. NIAID researchers also are adapting approaches used with investigational SARS and MERS vaccines to jumpstart candidate vaccine development for 2019-nCoV. Advances in technology since the SARS outbreak have greatly compressed the vaccine development timeline, the authors write. They indicate that a candidate vaccine for 2019-nCoV could be ready for early-stage human testing in as little as three months as compared to 20 months for early-stage development of an investigational SARS vaccine."

[US Food and Drug Administration](https://www.fda.gov/emergency-preparedness-and-response/mcm-issues/novel-coronavirus-2019-ncov) - "FDA is working with U.S. Government partners, including the U.S. Centers for Disease Control and Prevention (CDC), and international partners to closely monitor an outbreak caused by a novel (new) coronavirus first identified in Wuhan City, Hubei Province, China."

### Data Repositories

[C-I-TASSER](https://www.viprbrc.org/brc/home.spg?decorator=corona_ncov) - "This page contains 3D structural models and function annotation for all proteins in the 2019-nCov genome. The structure models are generated by the C-I-TASSER pipeline, which utilizes deep convolutional network based contact-map predictions to guide the I-TASSER fragment assembly simulations. Benchark and blind CASP tests showed that C-I-TASSER generates models with a higher accuracy than I-TASSER does, especially for the protein targets lack of homologous templates."  

[NCBI Genbank](https://www.ncbi.nlm.nih.gov/genbank/2019-ncov-seqs/) - Entrez Nucletide/RefSeq sequences, [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi?PAGE_TYPE=BlastSearch&BLAST_SPEC=Betacoronavirus) against a custom Betacoronavirus database, the new NCBI Virus resource, SRA sequences, reference genome, and [PubMed articles](https://pubmed.ncbi.nlm.nih.gov/?term=2019-Ncov).  

[Chinese National Genomics Data Center](https://bigd.big.ac.cn/ncov?lang=en) - 2019 Novel Coronavirus Resource.  

[Protein Data Bank](http://www.rcsb.org/pdb/results/results.do?tabtoshow=Current&qrid=FD0ED183) - Coronavirus protein structures.   

[Virus Pathogen Database and Analysis Resource (ViPR)](https://www.viprbrc.org/brc/home.spg?decorator=corona_ncov) - Nucleotide sequences, preliminary [comparative genomics](https://www.viprbrc.org/brcDocs/documents/announcements/Corona/2019-nCov-ViPR-report_24JAN2020.pdf), tools for sequence alignment, phylogenetic, SNP, BLAST, annotation and analysis.  

### Visualization

[JHU CSSE Near-real-time mapping of 2019-nCoV](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6) - Near-real-time mapping of the pathogen.

[Nextstrain](https://nextstrain.org/ncov) - Real-time tracking of pathogen evolution. [Chinese Version/中文版](https://nextstrain.org/ncov/zh) 

### Publications

[American Society for Microbiology](https://www.asm.org/Press-Releases/2020/nCoV2019-Resources) - ASM is providing free access to more than 100 research articles published over the last year in ASM’s 18 scholarly journals to support research efforts and communications about the novel coronavirus (2019-nCoV).    

[bioRxiv](https://www.biorxiv.org/search/2019ncov) - 2019nCoV articles.  

[Elsevier](https://www.elsevier.com/connect/coronavirus-information-center)- Elsevier’s free health and medical research on novel coronavirus (2019-nCoV).  

[medRxiv](https://www.medrxiv.org/search/2019ncov) - 2019nCoV articles.  

[PubMed](https://pubmed.ncbi.nlm.nih.gov/?term=2019%20nCOV) - PubMed articles on the pathogen.

[Science Magazine](https://www.sciencenews.org/article/new-coronavirus-outbreak-your-most-pressing-questions-answered) - 2019nCov Q&A.  

[The Lancet](https://www.thelancet.com/coronavirus) - 2019-nCoV Resource Centre.    

[The New England Journal of Medicine](https://www.nejm.org/coronavirus) - A collection of articles and other resources on the 2019 Novel Coronavirus outbreak, including clinical reports, management guidelines, and commentary.  

### Twitter hashtags
#2019ncov #ncov2019 #ncov


## Long-read Sequencing Tools

[Canu](https://github.com/marbl/canu) - [Perl/C] - scalable and accurate long-read assembly via adaptive k-mer weighting and repeat separation.  

[BulkViz](https://github.com/LooseLab/bulkVis) - [Python] - An app written in Python3 using Bokeh to visualise raw squiggle data from Oxford Nanopore Technologies (ONT) bulkfiles. See the documentation at https://bulkvis.readthedocs.io .  

[HGAP](https://github.com/PacificBiosciences/Bioinformatics-Training/wiki/HGAP) - [?] - The Hierarchical Genome Assembly Process (HGAP) for long single pass reads generated by the PacBio® Single Molecule Real Time (SMRT) sequencer was developed to allow the complete and accurate shotgun assembly of bacterial sized genomes.

[metaFlye](https://github.com/fenderglass/Flye) - [C++] - scalable long-read metagenome assembly using repeat graphs.  

[MetaMaps](https://github.com/DiltheyLab/MetaMaps) - [perl/R] - Strain-level metagenomic assignment and compositional estimation for long reads.  

[Minimap](https://github.com/lh3/minimap) - [C] - an experimental tool to efficiently find multiple approximate mapping positions between two sets of long sequences, such as between reads and reference genomes, between genomes and between long noisy reads.   

[Shasta](https://github.com/chanzuckerberg/shasta) - [C++] - The goal of the Shasta long read assembler is to rapidly produce accurate assembled sequence using as input DNA reads generated by Oxford Nanopore flow cells.  


## Microbiome (16S)

[Explicet]( http://www.explicet.org) - [?] - a free to use, open source software package (GPLv3) available for Windows, Mac, and Linux that facilitates the exploration and visualization of taxonomy-based microbiome datasets (a.k.a. OTU tables).

[LotuS]( http://psbweb05.psb.ugent.be/lotus) - [?] - aims at scientists and bioinformatician that want a simple pipeline that is streamlined to a core functionality of creating OTU and taxa abundance tables, at very fast speeds (e.g. processing an 8GB 16S miSeq run takes ~ 30 min on a laptop). LotuS does not include numerical analysis of samples, instead we designed LotuS output to be easily integrateable into existing workflows in e.g. statistical programming languages like R, QIIME/mothur or Matlab.

[METAREP](https://github.com/jcvi/METAREP) - [?] - high-performance comparative metagenomics. It provides a suite of web based tools to help scientists to view, query, browse and compare metagenomic annotation data derived from ORFs called on metagenomics reads or assemblies.

[Microbiome Util]( http://microbiomeutil.sourceforge.net) - [perl] - NASTiEr - Sequence Alignment; WigeoN - Chimera detection; TreeChopper - OTU binning; AMOSScmp - Sequence assembly.

[mothur](https://www.mothur.org/) - [C++] - OTU-based analysis of 16S data.

[Otupipe](http://www.drive5.com/usearch/manual/otupipe.html) - [?] - a bash script for OTU clustering based on USEARCH. This page is retained for historical interest because a script based on otupipe was used to create the published QIIME results for the Human Microbiome Project (HMP).

[Puma](https://github.com/puma/puma) - [Ruby] - Program for Unifying Microbiome Analyses (PUMA) - a novel tool for comprehensive and efficient streamlining of 16S rRNA microbiome taxonomy data for analysis and visualization (CLI/GUI).
  
[Qiime](http://qiime.org/) - [Python] - QIIME is designed to take users from raw sequencing data generated on the Illumina or other platforms through publication quality graphics and statistics. This includes demultiplexing and quality filtering, OTU picking, taxonomic assignment, and phylogenetic reconstruction, and diversity analyses and visualizations.

[Qiita (cheetah)]( http://qiita.microbio.me/) - [?] - microbiome storage and analysis resource that can run on everything from your laptop to a supercomputer. It is built on top of the widely used QIIME package, and enables the exploration of -omics data.

[UPARSE]( http://drive5.com/uparse/) - [?] - generates OTUs that are far superior to state-of-the-art methods including QIIME, mothur and AmpliconNoise on mock community tests. OTU representative sequences are more accurate predictions of biological sequences, and the number of OTUs is much close to the number of species.

[USEARCH](https://www.drive5.com/usearch/) - [?] - a high-throughput sequencing tool that offers read processing, clustering (ESTs, OTUs, +more), and diversity and taxonomy analysis algorithms in a single package. USEARCH's database search feature is 10-100 times faster than BLAST, and the documentation is thorough and user-friendly. The 32-bit version is free, including for commercial use. A paid 64-bit version is also available.


## Metagenomics (WGS, Shot-gun sequencing)

[bioBakery-MetaPhlAn](https://bitbucket.org/biobakery/biobakery/wiki/Home) - [python] - a virtual environment platform that provides meta'omic analysis tools.

[Mauve](http://darlinglab.org/mauve/mauve.html) - [?] - a system for constructing multiple genome alignments in the presence of large-scale evolutionary events such as rearrangement and inversion. Multiple genome alignments provide a basis for research into comparative genomics and the study of genome-wide evolutionary dynamics.

[curatedMetagenomicData](https://waldronlab.github.io/curatedMetagenomicData/) - [R] - a curated database of processed human microbiome data from metagenomics, from the Human Microbiome Project and numerous other published datasets.  Provides both taxonomic profiles and inferred metabolic function.  Distributed via Bioconductor's [ExperimentHub](https://bioconductor.org/packages/ExperimentHub/), command-line interface also available.

[MetaKallisto](https://github.com/pachterlab/metakallisto) - [Python] - Pseudoalignment for metagenomic read assignment.  

[MetaMeta](https://github.com/pirovc/metameta) - [python] - Integrates metagenome analysis tools to improve taxonomic profiling. [doi](https://doi.org/10.1101/138578)

[SMART Metagenomics Classifer](https://bitbucket.org/ayl/smart) - [C++] - Metagenomics aligner pipeline for ingesting WGS FASTQ files and uses highly parallel k-mer search strategy to search against all of NCBI GenBank. [Link to manuscript](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-016-1159-6)

## Microbe (pathogen, bacterial, viral) Identification/Detection/Characterization

[GenomeGraphR](https://fda-riskmodels.foodrisk.org/genomegraphr/) - [R] - A user-friendly open-source web application for foodborne pathogen Whole Genome Sequencing data integration, analysis, and visualization.  
  
[Pathoscope](https://sourceforge.net/p/pathoscope/wiki/Home/) - [python] - Species identification and strain attribution with unassembled sequencing data.

[MetaHIT](http://www.metahit.eu/index.php?id=232) - [?] - DNA microarrays and high-throughput DNA re-sequencing technology for structural and functional analysis of microbial populations.

[POPSICLE](https://popsicle-admixture.sourceforge.io/) - [R] - a software suite to determine population structure and Ancestral Determinants of Phenotypes using Whole Genome Sequencing data.  
  
## Visualization

[Krona](https://github.com/marbl/Krona/wiki) - [python] - Interactive metagenomic visualization in a Web browser. 

[MEGAN](http://ab.inf.uni-tuebingen.de/software/megan6/) - [?] - The most powerful interactive microbiome analysis tool
Analyse metagenome, metatranscriptome and amplicon sequences from multiple sources.

## Other Tools 

[AmpliconNois]( https://code.google.com/p/ampliconnoise) - [?] - a collection of programs for the removal of noise from 454 sequenced PCR amplicons. It involves two steps the removal of noise from the sequencing itself and the removal of PCR point errors. This project also includes the Perseus algorithm for chimera removal.

[BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) - [C/C++] - Basic Local Alignment Search Tool (BLAST) finds regions of local similarity between sequences. The program compares nucleotide or protein sequences to sequence databases and calculates the statistical significance of matches. BLAST can be used to infer functional and evolutionary relationships between sequences as well as help identify members of gene families. Introduced in 2009, BLAST+ is an improved version of BLAST command line applications. 

[BLAST+ Docker](https://github.com/ncbi/blast_plus_docs) - [NA] - Docker image for BLAST.

[gist, genepuddle, and gargle]( http://www.compsysbio.org/front/?id=73) - [?] - filter contaminants from RNA-seq sequences to make them suitable for alignment and analysis.

[MLSTEZ](https://sourceforge.net/projects/mlstez/) - [python] - MLSTEZ is designed for next generation sequencing technology (PacBio CCS or Roche 454 platform) based MSLT methods. 

## Workflows

[SAMSA2](https://github.com/transcript/samsa2) - [NA] - Simple Analysis of Metatranscriptomes by Sequence Annotation.  

## Web Portals
[CosmosID](http://www.cosmosid.com/) - Exploring the Universe of Microbes.

[One Codex](https://www.onecodex.com) - One Codex is a data platform for applied microbial genomics.

[NCI Cloud Resources](https://cbiit.cancer.gov/ncip/cloudresources) - A cloud platform to analyze microbe data.  Currently available pipelines - BLAST-based microbe identification and characterization, mothur, Qimme, and MetaPhlAn with built-in visualization.  Contact @stevetsa for [more information](http://bit.ly/nciposter).  

[MG-RAST](http://metagenomics.anl.gov/) - Metagenomics Analysis Server.

[Nephele](https://nephele.niaid.nih.gov/#home) - Microbiome Analysis without Boundaries.

[PATRIC](https://www.patricbrc.org/) - Bacterial database and analysis platform.

[ViPR](https://www.viprbrc.org/brc/home.spg?decorator=vipr) - Viral pathogen database and analysis platform.

## Journal Articles, etc.
[BIOM Format](http://biom-format.org/) - is designed to be a general-use format for representing biological sample by observation contingency tables. BIOM is a recognized standard for the Earth Microbiome Project and is a Genomics Standards Consortium supported project.

[Experimental and analytical tools for studying the human microbiome](http://www.nature.com/nrg/journal/v13/n1/full/nrg3129.html) - Nature Reviews Genetics 13, 47-58 (January 2012) | doi:10.1038/nrg3129.

[Metagenomics - Tools and other Points of Interest](https://docs.google.com/document/d/1qLczhk4MAKjkOtz-PnXhmgGEWnWQJHLf0Mjd1B9U2RU) - list compiled by [@bioinformer](https://twitter.com/bioinformer)
