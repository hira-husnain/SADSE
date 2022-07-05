# SDSC: Structure Aware Deep Spectral Embedding


1. pip  install munkres
2. pip install spams

3. Learning_Sb file in respective dataset folder is the learning of batch based self-expression matrix using query-net & key-net. 
4. Computing_Hs file in respective dataset folder is the learning of batch based self expressive matrix using traditional optimization techniques. 
5. To obtain results of table 6 in the paper:
    load 'Hs_datasetname.npy' file, instead of 'Sb_datasetname.npy' in each .ipynb implementation accordingly. 
