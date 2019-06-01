

### Scripts description
1. Downloading.sh - script for downloading tsv-files for all phenotypes  
2. Data_prep.sh - script for downloaded data preprocessing, this files were subsequently merged in uneted tsv-file  
3. tsv_parse.py - script for merging rows in tsv-file (merging SNP associated with several phenotypes)  
4. Data_Visualization.r - script for visualisation data 
5. Data_plot_preparation.sh, Data_preparation_for_plot.py - scripts for data preprocessing for Manhattan plot  
6. Data_preparation_for_heatmap.py - script for  data preprocessing for heatmap  
7. Heatmap_array_build.py - script for building heatmap with phenotypes  
8. Heatmap_viz.r - script for heatmap visualizing and hierarchical clustering  
9. Manhattan_plot_viz.r - script for Manhattan plot visualizing  
10. Clustered_manhattan_prep.py - script for data preparation for Manhattan plot with associated clusters  
11. MAF_preparation.py, MAF_for_all_SNP.py, Specifying_data_for_phen_corr.sh - scripts for data preprocessing for further MAF modelling
12. MAF_correlation.r - scripts for calculating MAF and modelling MAF with Poissoin distribution
13. pval_manhattan.py - script preparing Manhattan plot with Poissoin modelling p-values
14. creating_cluster_diagram.py, Cluster_annotation.py,SNP_diagram.py scripts for creating treemap of phenotypes
15. Common_SNP_jaccard.py, Common_SNP_bed_and_VCF.py - exracting SNPs common for 2 or more clusters and creatind BED and VCF-files for further analysis
16. eqtl_analysis.py - calculating the number of signifficant eqtls for data
17. CLUMPING.sh - script for performing PLINK clumping on phenotypes and clusters of phenotypes
18. LSEA - tool for performing hypergeometric test on independant loci
19. enrichment_analysis.py - summarising enrichment data
21. var_stats.py - analysing protein altering variants enrichment for clusters
22. graph_preparation.py - creating network of sharedo loci fbetween clusters
23. find_cliques.py - searcing for dense subgraphs from obtained network
24. grapg_and_clust_diags.r - visualising enrichments and network of shared loci between clusters

