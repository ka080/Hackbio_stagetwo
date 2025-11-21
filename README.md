qc and filtering is code for performing qaulity control, normailisation and filtering tasks.

cell annotation is code for visaulising different cell clusters.
purpose of each major step in single-cell RNA-seq (scRNA-seq) data analysis:
1. Quality Control (QC)
Purpose:
Remove low-quality cells and technical artifacts (e.g., dying cells, doublets, cells with high mitochondrial RNA) to ensure that downstream analyses reflect true biology rather than noise.
2. Normalization
Purpose:
Correct for differences in sequencing depth or capture efficiency across cells so that gene expression values are comparable across the dataset.
3. Feature Selection (Highly Variable Genes, HVGs)
Purpose:
Identify genes that vary meaningfully across cells (rather than noise) to focus analyses on informative signals driving biological differences.
4. Dimensionality Reduction (e.g., PCA, UMAP, t-SNE)
Purpose:
Simplify high-dimensional gene-expression data into a smaller number of dimensions, making cell-to-cell variation easier to visualize and interpret.
5. Clustering
Purpose:
Group cells into clusters based on similarity in gene expression in order to identify putative cell types, states, or subpopulations.
6. Differential Expression Analysis / Marker Gene Identification
Purpose:
Find genes that define each cluster, allowing biological interpretation (e.g., identifying specific cell types or functional states).
7. Cell Type Annotation
Purpose:
Assign biological identities to clusters using marker genes, reference datasets, or automated tools.
