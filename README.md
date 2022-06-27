# SDSC
Structure Aware Deep Spectral Embedding

################installation packages############
pip  install munkres
pip install spams

#########implementation for table-6 #############
attention_H file in respective dataset folder is the learning of batch based self-expression matrix using query-net & key-net. 
traditional_H file in respective dataset folder is the learning of batch based self expressive matrix using traditional optimization techniques. 
To obtain results of table 6 in the paper:
    load 'htraditional_datasetname.npy' file, instead of 'h_datasetname.npy' in each .ipynb implementation accordingly. 
