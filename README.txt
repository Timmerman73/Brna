Benodigheden:
Het Rmarkdown script Main.rdm
De bestanden:
	metadata14.txt
	countdata14.txt
	featureData.txt
Verder zijn de gmt pathway bestanden nodig.
	h.all.v7.5.1.symbols.gmt
	c6.all.v7.5.1.symbols.gmt
	c2.cp.kegg.v7.5.1.symbols.gmt
	c2.cp.reactome.v7.5.1.symbols.gmt

Verder moeten er ook een aantal packages geinstaleerd zijn. Deze zijn:
	DESeq2
	apeglm
	ashr
	pheatmap
	vsn
	fgsea
	Rcp
	ggplot2
	hexbin
	RColorBrewer
	dplyr
	goseq
	rtracklayer
	BSgenome
	org.Hs.eg.db
	GO.db
	clusterProfiler
	AnnotationDbi
	R.utils
	pathview
	
Deze packages willen vaak zelf extra packages installeren. Deze zijn ook allemaal nodig. 
Deze kunnen geinstaleerd worden door de BiocManager met BiocManager::install("PACKAGE_NAAM")

Het gaat om een R markdown script. Zodat de coden in blokken uitgevoerd kan worden.
Alle code kan in 1x uitgevoerd worden door op run te clicken en dan helemaal onderaan op run all te clicken.

Alle resultaten worden opgeslagen in de out directory. Deze wordt automatisch aangemaakt. 
Uitzondering hierop zijn de clusterProfiler kegg pathways. Deze staan in de working directory van het script.



AGGA|^TTAT
ATAGGA|^TT
A|^TTATAGG
GA|^TTATAG
GGA|^TTATA
TAGGA|^TTA
TATAGGA|^T
TTATAGAA|^
^TTATAGAA|
|^TTATAGGA

TTGGAAT^|A


twee seqs 
ATGGATATG
ATGCCAAAG

1 
kmers = 3
ATG
 TGG
   GGA
    GAT
	 ATA
	  TAT
	    ATG
		
2
ATG
 TGC
  GCC
   CCA
    CAA
	 AAA
	   AAG