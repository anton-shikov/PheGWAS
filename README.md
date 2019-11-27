

### Scripts description
1. Downloading.sh - downloading tsv-files for all phenotypes from UK Biobank 
2. Data_prep.sh - preprocessing downloaded data and merging files into one table
3. tsv_parse.py - merging rows in tsv-file (mearging SNP associated with several phenotypes)  
4. Data_Visualization.r - visualisation data (distributions of SNPs eith signifficant associations)
5. Data_plot_preparation.sh, Data_preparation_for_plot.py - data preprocessing for Manhattan plot  
6. Heatmap_viz.r - heatmap visualizing and hierarchical clustering
7. Clustered_manhattan_prep.py - script for data preparation for Manhattan plot with associated clusters 
8. Manhattan_plot_viz.r - Manhattan plot visualizing  
9. creating_cluster_diagram.py, Cluster_annotation.py,SNP_diagram.py - creating treemap of phenotypes
10. eqtl_analysis.py - calculating the number of significant eqtls for data
11. CLUMPING.sh - performing PLINK clumping on phenotypes and clusters of phenotypes
12. LSEA - tool for performing hypergeometric test on independent loci
13. HLA_enrich.py - performing enrichment for HLA-locus and HIST1 gene cluster
14. enrichment_analysis.py - summarizing enrichment data
15. var_stats.py - analysis of protein altering variants enrichments for clusters
16. grapg_and_clust_diags.r - visualizing enrichments in clusters
