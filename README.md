# SADSE: Learning Structure Aware Deep Spectral Embedding

Official implementation of our paper (Yaseen, H., & Mahmood, A. (2023). Learning structure aware deep spectral embedding. IEEE Transactions on Image Processing, 32, 3939-3948.).
1. pip  install munkres
2. pip install spams

3. Learning_Sb_datasetname file in respective dataset folder is the learning of batch based self-expression matrix using query-net & key-net. 
4. Computing_Hs_datasetname file in respective dataset folder is the learning of batch based self expressive matrix using traditional optimization techniques. 
5. To obtain results of table 6 in the paper:
    load 'Hs_datasetname.npy' file, instead of 'Sb_datasetname.npy' in each .ipynb implementation accordingly. 
