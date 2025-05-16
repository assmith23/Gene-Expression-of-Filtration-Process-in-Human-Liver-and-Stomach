# Gene Expression Signatures Underlying Specialized Filtration Processes in Human Liver and Stomach
**Author:** A Manning Smith

## Abstrat
The human liver and stomach represent two distinct filtering systems with complementary functions in the body. While the liver filters blood and performs metabolic detoxification, the stomach filters ingested materials through physical and chemical processes. This study aimed to characterize the differences between these organs to better understand their specialized functions. RNA-sequencing results were utilized from three biological replicates of each human liver and stomach tissues. Following quality assessment, adapter trimming, and alignment to the human reference genome (GRCh38.p14-ensembl), differential gene expression analysis was conducted using DESeq2. Principal component analysis revealed extreme separation along PC1 (explaining 95% of variance), confirming fundamentally different expression profiles between tissues. The top differentially expressed genes included liver-specific markers involved in detoxification pathways (ALB, SERPINC1, CYP family) and stomach-specific genes related to mucosal protection (MUC5AC, GKN1, TFF1). Hierarchical clustering demonstrated two distinct gene expression patterns with minimal overlap between tissues. These findings support our hypothesis that liver and stomach tissues exhibit distinctive gene analysis signatures reflecting their specialized filtering functions, with liver expressing higher levels of detoxification and metabolic pathway genes, while stomach shows elevated expression of genes related to acid production, mucus secretion, and digestive processes.

## Available Resources
- `end2end.R` | Script include all the supporting code for the project
- `enrichmentResults.xlsx` | Enrichment Results from the various gene lists provide via the gene analysis.
- `differentialExpressionAnalysis_results.xlsx` | Contains the results from differential expression.
  - The fields are baseMean, log2FoldChange, lfcSE, stat, pvalue, padj
- `GeneExpressionAnalysis-finalReport.pdf` | Final Paper

## Data
- `enrichmentFiles` | The input files used in DAVID for enrichment analysis
- `countingResults` | The counting results after trimming, mapping and counting from the 6 different tissue samples.
