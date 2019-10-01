# Homer-analysis
HOMER contains a novel motif discovery algorithm that was designed for regulatory element analysis in genomics applications (DNA only, no protein).  It is a differential motif discovery algorithm, which means that it takes two sets of sequences and tries to identify the regulatory elements that are specifically enriched in on set relative to the other.


findMotifs.pl will analyze the promoters of genes and look for motifs that are enriched in your target gene promoters relative to other promoters.  The idea is to provide a list of genes that you believe should contain the same elements, such as genes that are co-regulated.  For example, you may want to analyze the genes that are up-regulated by a stimulus, or genes that are specific to a certain cell type, or genes that appear in the same gene-expression cluster when doing clustering analysis.  Alternatively, the gene IDs could come from a promoter ChIP-Chip experiment where each of the promoters are bound by the same transcription factor.






 http://homer.ucsd.edu/homer/microarray/index.html

the results are still in progress...
