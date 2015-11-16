1. quality filter parameters using FASTX-Toolkit (v0.0.13)

	a. quality filter  params
	
	```
		fastx/bin/fastq_quality_filter -Q33 -q20 -p50
	```
	
	b. artifact filter params
	
	```
		fastx/bin/fastx_artifacts_filter -Q33
	```
	
	
	
2. Bowtie (v0.12.8) alignment parameters
	
	```
		bowtie -p8 -q -a -m10 --best --strata --chunkmbs 4086 -y
	```
	
3. Novoalign (v2.08.03) alignment parameters
	
	```
		novoalign -s 1 -r A 100
	```
	
4. Arabidopsis chromosme sequences used
	
	```
		ftp://ftp.arabidopsis.org/home/tair/Sequences/whole_chromosomes/
	```
	
5. Arabidopsis cDNA sequences	used

	```
		ftp://ftp.arabidopsis.org/home/tair/Sequences/blast_datasets/TAIR10_blastsets/TAIR10_cdna_20101214_updated
	```