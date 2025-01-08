# GET Foundation
GET Foundation is a international collaboration to build foundation models to understand gene expression. 

Our first release, GET (general expression transformer) is a model that can predict gene expression using solely cell-type specific chromatin accessibility data.

Checkout our paper at https://www.nature.com/articles/s41586-024-08391-z.

In this repo:
- get_model: the official model repo for GET with tutorials for data processing and training. Also as a modular, composable framework for constructing multimodal cross-cell-type models.
- gcell: the analysis package behind GET's TF-TF interaction and regulatory analysis. Also a Python playground for cell-type-specific biology hopefully can be used by Agent scientist in the future.
- getdemo: code for hugginface demo, if you are interested in the implementation.
- atac_rna_data_processing: deprecated and refactored into gcell.
