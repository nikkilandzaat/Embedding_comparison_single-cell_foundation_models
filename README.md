## Comparative analysis of foundation models for single-cell data

### Project
This project explores foundation models Geneformer and scGPT in single-cell RNA sequencing. We assess their ability to encode useful features from high-dimensional data by assessing their embeddings alongside PCA and UMAP for dimensionality reduction in PBMC and NSCLC datasets. Despite pretraining, Geneformer and scGPT show minimal agreement in embedding similarity, challenging their utility in single-cell biology compared to traditional methods. Results suggest these models may not reliably encode relevant biological features without task-specific fine-tuning, emphasizing the need for further evaluation in diverse biological contexts.

### Installation

### Notebooks
a. data_expl_NSCLC.ipynb & a. data_expl_PBMC.ipynb
- Explore the datasets.

b. data_prep_NSCLC.ipynb & b. data_prep_PBMC.ipynb
- Prepare the datasets for further  analysis.

c. PCA_UMAP_NSCLC.ipynb & c. PCA_UMAP_PBMC.ipynb
- Apply PCA and UMAP dimensionality reduction on both datasets.

d. GF_NSCLC.ipynb & d. GF_PBMC.ipynb
- Extract Geneformer embeddings from both datasets.

e. scGPT_NSCLC.ipynb & e. scGPT_PBMC.ipynb
- Extract scGPT embeddings from both datasets.

f. NN_analysis_NSCLC.ipynb & f. NN_analysis_PBMC.ipynb
- Deploy a pair-wise nearest neighbor analysis for all embeddings, per dataset.

### Data
The 68k PBMC dataset is available at: https://www.10xgenomics.com/datasets/fresh-68-k-pbm-cs-donor-a-1-standard-1-1-0.

The 20k NSCLC dataset is available at: https://www.10xgenomics.com/datasets/20-k-mixture-of-nsclc-dt-cs-from-7-donors-3-v-3-1-3-1-standard-6-1-0. 

