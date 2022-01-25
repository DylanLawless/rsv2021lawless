# Supplementary project data
<https://lawlessgenomics.com/rsv2021lawless.github.io>

* Pre-print <https://www.overleaf.com/project/61718a4e077acc3d20ee68f1>
* This repo contains the interactive results from [citation].
* The pre-print can be found on medarxiv [citation].
* Branch and md5sum of publication version:

<!-- <div class="evidence-graph-container"> -->
<!--   <div class="evidence-graph left" margin-bottom="3vh"> -->

<!-- <iframe id="igraph" scrolling="yes" style="border:none;" seamless="seamless" src=" -->
<!-- 	https://lawlessgenomics.com/topic/gnomad_table.html -->
<!-- 	" -->
<!-- 	height="240" --> 
<!-- 	width="90%"></iframe> -->

<!-- <iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src=" -->
<!-- 	https://lawlessgenomics.com/topic/gene_illustrate.html -->
<!-- 	" -->
<!-- 	height="1000" --> 
<!-- 	width="95%"></iframe> -->

<!-- <iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" allowFullScreen="true" src=" -->
<!-- https://www.ncbi.nlm.nih.gov/Structure/icn3d/full.html?mmdbid=2YKG&buidx=0&date=20220119&v=3.7.1&command=set background white; color domain -->
<!-- 	" -->
<!-- 	height="500" --> 
<!-- 	width="90%"></iframe> -->

<!--  </div> -->
<!-- </div> -->


<iframe id="igraph" scrolling="no" style="border:none;" seamless="seamless" src="
	https://lawlessgenomics.com/rsv2021lawless.github.io/pages/gene_illustrate_rsv_detail.html
	"
	height="1000" 
	width="95%"></iframe>

## Study population
<div class="evidence-graph-container">
<iframe scrolling="no" style="border:none;" seamless="seamless" src="
	https://lawlessgenomics.com/rsv2021lawless.github.io/pages/rsv_persist2022.html
	"
	height="500" 
	width="100%"
	></iframe>
</div>

# Software
- R v4.1.0 was used for data preparation and analysis <http://www.r-project.org>.
- R package *caret* was used for analysis: genetic correlations.
- R package *dplyr* was used for data curation.
- R package *factoextra* was used for analysis: PCA, and to visualise eigenvalues and variance.
- R package *ggplot2* was used for data visualisation.
- R package *MASS* was used to analysis: logistic regression model data.
- R package *stats* was used for analysis: including glm for logistic regressions. 
- R package *stringr* was used for data curation.
- R package *tidyr* was used for data curation.

- asn2fsa <https://www.huge-man-linux.net/man1/asn2fsa.html>
- clc\_novo\_assemble [qiagenbioinformatics.com](https://resources.qiagenbioinformatics.com/manuals/clcgenomicsworkbench/852/index.php?manual=De_novo_assembly.html)
- Clustal Omega <https://www.ebi.ac.uk/Tools/msa/clustalo/>
- GenBank <https://www.ncbi.nlm.nih.gov/genbank/>
- IQ-Tree <https://www.iqtree.org/>
- MAFFT <https://mafft.cbrc.jp/alignment/software/> [citation katoh2013mafft]
- Tbl2asn <https://www.ncbi.nlm.nih.gov/genbank/tbl2asn2/>
- Viral Genome ORF Reader, VIGOR 3.0 <https://sourceforge.net/projects/jcvi-vigor/files/>
- RCSB PDB	<https://www.rcsb.org>
- UniProt	<https://www.uniprot.org>

# Additional Data sources

- Dataset <https://www.ncbi.nlm.nih.gov/bioproject/267583>.
- Dataset <https://www.ncbi.nlm.nih.gov/bioproject/225816>.
- J. Craig Venter Institute <https://www.jcvi.org>.
- GenBank:NC\_001989 Bovine orthopneumovirus, complete genome <https://www.ncbi.nlm.nih.gov/nuccore/NC_001989>.
- Reference data <https://www.ncbi.nlm.nih.gov/gene/?term=1489824>.
G attachment glycoprotein [Human orthopneumovirus]; ID: 1489824; Location: NC\_001781.1 (4675..5600); Aliases: HRSVgp07.
- Reference data <https://www.ncbi.nlm.nih.gov/gene/?term=37607642>. G attachment glycoprotein [Human orthopneumovirus]; ID: 37607642; Location: NC\_038235.1 (4673..5595); Aliases: DZD21\_gp07.
- Reference data for all public NCBI Virus <https://www.ncbi.nlm.nih.gov/labs/virus/vssi/> for species: Human orthopneumovirus; genus: orthopneumovirus; family: Pneumoviridae.
- Reference data <https://www.ncbi.nlm.nih.gov/labs/virus/vssi/#/virus?SeqType_s=Nucleotide&VirusLineage_ss=Human\%20orthopneumovirus,\%20taxid:11250>
- contains sequence data for 
Virus Lineage ss=Human orthopneumovirus, taxid:11250
nucleotide: 26’965, 
protein: 53’804, 
RefSeq Genomes: 2.
- Reference <https://www.ncbi.nlm.nih.gov/protein/NP_056862.1>
- GCF\_002815475.1	(release 2018-08-19) Nucleotide Accessions: NC\_038235.1, protein: Y\_009518856.1
- Reference <https://www.ncbi.nlm.nih.gov/protein/YP_009518856.1>
- GCF\_000855545.1	(release 2015-02-12) Nucleotide Accessions: NC\_001781.1, protein: NP\_056862.1 (strain B1).

# Repository maintenance
Using a custom host and ssh key is recommended for maintenance.

```
## Set up the ssh config file
cd ~/.ssh/config

## Set such that Host and User are custom
# lawlessgenomics repo
Host dylanlawless.github.com
  HostName github.com
  User DylanLawless
  PreferredAuthentications publickey
  IdentityFile ~/.ssh/key1_rsa
  IdentitiesOnly yes


# Clone using the correct Host as per config.
git clone git@dylanlawless.github.com:DylanLawless/DylanLawless.github.io.git

# Set the local user here (instead of global, i.e. /Users/user/.gitconfig)
cd "the clone repo dir"
git config user.email personemail@addess.com
git config user.name DylanLawless
```

# Colophon
This page uses the body font Switzer-Light, a neo-grotesk Latin-script typeface with 18 styles, designed by Jérémie Hornus.
The layout is based on the jekyll-theme-cayman.
It was developed using a local installation of the Jekyll Ruby gem and published using GitHub Pages.
Add the methods section for all data access and software here.

