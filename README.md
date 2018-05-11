# NCBI_Fetch

This repo will utilize the some python and biopython tools to access NCBI and pull down information. 

As of now (5/11/18) there are 3 notebooks in this repo. 

Viral_Genome_Extraction:
	This is exactly what it sounds like. We will use urllib (python3) to scrape a text file containing virus bioprojects and then get their corresponding genomes from NCBI

Human_Disease_Gene_Extraction_NCBI:
	This is a fun little interactive script that will ask you a few questions, and then return human genes associated with a disease. This heavily uses the Bio Entrez module.

fasta_human_orthologs_blastx_NCBI_Extraction: 
	This notebook will take in a fasta file from a non-human organism and return human homolgs. This uses NCBIWWW and NCBIXML.

