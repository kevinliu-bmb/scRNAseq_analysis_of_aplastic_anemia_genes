# Elucidation of B cell Function in Aplastic Anemia Through Single-cell RNA-Seq of Bone Marrow Tissue

## Project Description

This project uses single-cell RNA sequencing (scRNA-seq) data from bone marrow tissue samples of two adult aplastic anemia (AA) patients and two non-AA donors to validate and extend the findings of a previous scRNA-seq study by Tonglin et al. (2022) [1] on B cell destruction of hematopoiesis in AA patients. The previous study identified 8 broad cell clusters, 17 refined cell clusters, their respective marker genes associated with immune function, and elevated expression of B cells that are specific to AA patients. [1] The present study takes on a more simplistic approach and follows a standard analytical workflow for scRNA-seq datasets generated via 10X Genomics protocols using Seurat under an R environment. After filtering the data and conducting dimensionality reduction, the clusters were annotated using a reference-based mapping tool, Azimuth [2]. Downstream analysis included both differential abundance analysis and differential gene expression analysis to validate the findings of the previous study. The results validated the role of B cells in AA patients and identified differentially expressed genes associated with immune function.

## References

[1] Tonglin H, Yanna Z, Xiaoling Y, Ruilan G, Liming Y. Single-Cell RNA-Seq of Bone Marrow Cells in Aplastic Anemia. Front Genet. 2022;12:745483. Published 2022 Jan 3. doi:10.3389/fgene.2021.745483

[2] Hao Y, Hao S, Andersen-Nissen E, et al. Integrated analysis of multimodal single-cell data. Cell. 2021;184(13):3573-3587.e29. doi:10.1016/j.cell.2021.04.048
