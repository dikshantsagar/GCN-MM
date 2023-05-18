# GCN-MM

### A Graph Convolution based Neural Network to predict multiple myeloma cancer serverity.
Adjacency matrices (3) used for graph network information is precomputed using Cox Hazard ratios and Kaplan Meier Analysis. For more information see 
<a href="https://www.sciencedirect.com/science/article/pii/S0010482522007582?casa_token=aue9qiYY7JMAAAAA:8vG_r6nPLiIHbmsIAQvfpRuqNmamBr-YzbDvUD9ks1_oCRFWQ3OU3asKWY7GVP2KD0Bm0akJ5ow">paper</a>. <br>


## File Descriptions

- ADJ3_GCN_MM_MMRF.ipynb - Jupyter notebook to train on MMRF data.
- ADJ3_GCN_MM_AIIMS_FINETUNE.ipynb - Jupyter notebook to finetune on AIIMS data.

- best_model_16unit_3000epochs_weights.h5 - Best model weights for MMRF data.
- aiims_best_model_16_units_mmrfpretrained_6000epochs.h5 - best model weights for AIIMS data.



## Citation

Please cite the following work
```
@article{sagar2022gcrs,
  title={GCRS: A hybrid graph convolutional network for risk stratification in multiple myeloma cancer patients},
  author={Sagar, Dikshant and Aggarwal, Priya and Farswan, Akanksha and Gupta, Ritu and Gupta, Anubha},
  journal={Computers in Biology and Medicine},
  volume={149},
  pages={106048},
  year={2022},
  publisher={Elsevier}
}
```
  
