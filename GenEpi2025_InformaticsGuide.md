# <img src="https://coursesandconferences.wellcomeconnectingscience.org/wp-content/themes/wcc_courses_and_conferences/dist/assets/svg/logo.svg" width="300" height="50"> 
# Genomics and Epidemiological Surveillance of Bacterial Pathogens 2025 Informatics Guide

**Software used during the course**      

## Software Used During the Course

| Software | Version | Course Module | Website / Notes |
|----------|---------|----------------|------------------|
| [samtools](http://www.htslib.org/) | 1.25 | Mapping + Phylogenetics, Genome Annotation | Command-line tool for manipulating alignments in the SAM format |
| [bwa](http://bio-bwa.sourceforge.net/) | 0.7.19 | Mapping + Phylogenetics | Sequence alignment algorithm for short reads |
| [snippy](https://github.com/tseemann/snippy) | 4.0.2 | Mapping + Phylogenetics, Genome Annotation | Rapid bacterial SNP calling pipeline |
| [IQ-TREE 2](http://www.iqtree.org/) | 2.4.0 | Phylogenetics | Efficient phylogenetic tree reconstruction |
| [Gubbins](https://github.com/sanger-pathogens/gubbins) | 3.3.x | Phylogenetics | Detect recombination in bacterial genomes (`conda activate gubbins-env`) |
| [FastBAPS](https://github.com/gtonkinhill/fastbaps) | — | Phylogenetics | Bayesian clustering |
| [FigTree](http://tree.bio.ed.ac.uk/software/figtree/) | 1.4.4 | Phylogenetics | Tree visualization software |
| [ETE Toolkit](http://etetoolkit.org/) | 3.1.3 | Phylogenetics | Python framework for tree analysis (`conda activate ete3-env`) |
| [Unicycler](https://github.com/rrwick/Unicycler) | 0.5.1 | Assembly Comparison | Hybrid assembler for bacterial genomes |
| [Dragonflye](https://github.com/rpetit3/dragonflye) | 1.2.1 | Assembly Comparison | Nanopore-based genome assembly (`conda activate dragonflye-env`, Docker also available) |
| [QUAST](http://quast.sourceforge.net/) | 5.3.0 | Assembly Evaluation | Quality assessment of genome assemblies (`conda activate quast-env`) |
| [NUCmer (MUMmer)](https://github.com/mummer4/mummer) | 3.23 | Assembly Comparison | Whole-genome alignment tool |
| [Google Chrome](https://www.google.com/chrome/) / [Firefox](https://www.mozilla.org/firefox/) | Latest | Web Tools | Pre-installed for accessing online tools |
| [Artemis](https://github.com/sanger-pathogens/artemis) | 18.2.0 | Genome Annotation | Genome viewer and annotation tool |
| [ACT](https://www.sanger.ac.uk/tool/artemis-comparison-tool-act/) | 18.1.0 | Genome Annotation | Artemis Comparison Tool for genome alignments |
| [FastQC](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/) | 0.12.1 | Genome Annotation | Quality control for sequencing reads |
| [Trim Galore!](https://www.bioinformatics.babraham.ac.uk/projects/trim_galore/) | 0.6.10 | Genome Annotation | Adapter trimming and QC wrapper |
| [ARIBA](https://github.com/sanger-pathogens/ariba) | 2.14.6 | Genome Annotation | Antimicrobial resistance detection (`conda activate ariba-env`) |
| [SPAdes](https://github.com/ablab/spades) | 3.15.5 | Genome Annotation | Genome assembler; bundled with Unicycler |
| [ABACAS](https://www.sanger.ac.uk/tool/abacas/) | 1.3.1 | Genome Annotation | Contig ordering tool (manual install `abacas.1.3.1.pl`) |
| [BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) | Latest | Genome Annotation | Sequence similarity search tool |
| [Bakta](https://github.com/oschwengers/bakta) | Latest | Genome Annotation | Prokaryotic genome annotation tool |
| [RATT](https://ftp.sanger.ac.uk/pub/resources/software/ratt/) | 1.0 | Comparative Genomics | Transfer annotations between genomes (installed via FTP source) |
| [Filtlong](https://github.com/rrwick/Filtlong) | 0.2.1 | Sequencing & QC | Long-read read quality filtering |
| [NanoPlot](https://github.com/wdecoster/NanoPlot) | 1.44.1 | Sequencing & QC | QC and visualization for Nanopore reads (`NanoPlot` command) |
| [Roary](https://sanger-pathogens.github.io/Roary/) | Latest | Pan-genome analysis | Pan-genome pipeline (`conda activate roary`) |
| [Panaroo](https://github.com/gtonkinhill/panaroo) | 1.1.2 | Genome Annotation | Pangenome analysis (`conda activate panaroo`) |
| [Docker](https://www.docker.com/) | 28.2.2 | Container-based tools | Used to run containerized versions of bioinformatics tools |

---

### Notes on Conda Environments

Many tools are installed in their own Conda environments to ensure version compatibility and reproducibility. To use a tool within its environment:

```bash
conda activate <tool-env-name>


## Informatics Set-Up
For installation and setup, please refer to the following guides:

- **[Oracle VM VirtualBox Installation Guide](https://github.com/WCSCourses/index/blob/main/VM_Guide.md)** – Detailed instructions for installing and configuring VirtualBox on different operating systems. *(Note: Separate installations are needed for Intel-based and ARM-based Macs, and the VDI files will differ.)*

The Host Operating System Requirements are: <br />
- RAM requirement: 8GB (preferably 12GB) <br />
- Processor requirement: 4 processors (preferably 8) <br />
- Hard disk space: 200GB <br />
- Admin rights to the computer <br />

## Citing and Re-using Course Material

The course data are free to reuse and adapt with appropriate attribution. All course data in these repositories are licensed under the <a rel="license" href="https://creativecommons.org/licenses/by-nc-sa/4.0/">Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)</a>. <a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /> 

Each course landing page is assigned a DOI via Zenodo, providing a stable and citable reference. These DOIs can be found on the respective course landing pages and can be included in CVs or research publications, offering a professional record of the course contributions.

## Interested in attending a course?

Take a look at what courses are coming up at [Wellcome Connecting Science Courses & Conference Website](https://coursesandconferences.wellcomeconnectingscience.org/our-events/).

---

[Wellcome Connecting Science GitHub Home Page](https://github.com/WCSCourses) 

For more information or queries, feel free to contact us via the [Wellcome Connecting Science website](https://coursesandconferences.wellcomeconnectingscience.org).<br /> 
Find us on socials [Wellcome Connecting Science Linktr](https://linktr.ee/eventswcs)

---
