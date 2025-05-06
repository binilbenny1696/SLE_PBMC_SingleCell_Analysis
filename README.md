# 🧬 SLE_PBMC_SingleCell_Analysis

This project presents a **single-cell transcriptomic and CITE-seq analysis** of **peripheral blood mononuclear cells (PBMCs)** from patients with **Systemic Lupus Erythematosus (SLE)** compared to healthy controls. Using the **GSE189050 dataset**, we identify immune dysregulation patterns, inflammatory monocyte expansion, and interferon-stimulated gene (ISG) activation across disease states.

---

## 🎯 Objectives

- Profile immune cell composition across **active SLE, inactive SLE, and healthy controls**.
- Identify **type I interferon response signatures** using ISG expression.
- Quantify changes in **monocyte subsets** and CD8+/B cell depletion.
- Integrate **CITE-seq** surface protein data for validation.

---

## 🧰 Tools Used

| Category | Tools |
|----------|-------|
| Single-cell Processing | Seurat (R), SCTransform |
| Visualization | UMAP, violin plots, bar plots |
| Omics | RNA-seq + CITE-seq |
| DE Analysis | `FindMarkers`, Wilcoxon test |
| Dataset | GEO GSE189050 |

---

## 📂 Project Structure


---

## 🔍 Key Findings

| Observation | Details |
|-------------|---------|
| Inflammatory Monocytes | S100A8/A9^hi cells expanded in SLE-ACT |
| IFN Response | ISG15, IFI6, FKBP5 upregulated in SLE-ACT monocytes |
| CITE-seq Validation | Surface proteins (CD14, CD3D, MS4A1) confirmed cluster IDs |
| B Cell/CD8+ Reduction | Relative depletion in SLE-ACT vs controls |
| Type I IFN Signature | Dominant in monocyte clusters from active patients |

---

## 📚 Dataset Reference

- **GSE189050**: Single-cell and CITE-seq PBMC data for lupus vs control cohorts

---

## 👤 Author

**Binil Benny**  
Autoimmune Bioinformatics | scRNA + CITE-seq | Immuno-profiling  
GitHub: [@binilbenny1696](https://github.com/binilbenny1696)

---

## 🪪 License

Licensed under the [Creative Commons BY 4.0](https://creativecommons.org/licenses/by/4.0/).
