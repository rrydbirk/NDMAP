# NDMAP
Neurodegenerative Diseases analyzed by Multi Area Proteomics

Overall, we find the most interesting results for the striatum regardless of whether we take a regular approach looking at differentially expressed proteins (DEPs), or we use more advanced factor analyses - in this case, I used [MOFA2](https://biofam.github.io/MOFA2/).

For the regular analyses, please note for the striatum I set min log2 fold change (l2FC) ~ 2 and max adjusted p = 0.05, which is the community-wide generally accepted minimal requirements to accept a protein as a DEP. For the other areas, I set the l2FC much lower in order to capture anything to continue with.

**These analyses are not final**. Please provide relevant feedback so I can update/expand the analyses.

To do:

- Perform across area analyses of protein expression (are any proteins concurrently high/low across areas?)

- Between area protein crosstalk (will high levels of protein A in area X lead to low levels of B in area Y?)

# Analysis reports

## Preprocessing

- [Preprocessing](https://rrydbirk.github.io/NDMAP/Brain_regions_preprocessing.html)

## Regular analyses

- [Downstream analyses WITH imputation](https://rrydbirk.github.io/NDMAP/Brain_regions_downstream.html)

- [Downstream analyses WITHOUT imputation](https://rrydbirk.github.io/NDMAP/Brain_regions_downstream_no_imputation.html)

## Factor analyses

- [MOFA2 model creation](https://rrydbirk.github.io/NDMAP/Brain_regions_MOFA2_models.html)

- [MOFA2 downstream analyses](https://rrydbirk.github.io/NDMAP/Brain_regions_MOFA2_downstream.html)

- [MOFA2 GSEA analyses](https://rrydbirk.github.io/NDMAP/Brain_regions_MOFA2_GSEA.html)
