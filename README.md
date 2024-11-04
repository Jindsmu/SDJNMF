Joint non-negative matrix factorization with similarity and dissimilarity constraints

This project constructed a framework for integrating two scRNA-seq gene expression matrices. This framework, called Joint non-negative matrix factorization with similarity and dissimilarity constraints (SDJNMF), allows for precise clustering and visualisation of similar cells close to each other and different cells far from each other.

The code in this project will reproduce the results in our paper, "A Semi-Supervised Non-Negative Matrix Factorization Model for scRNA-seq Data Analysis".

## Requirement
- CUDA>=10.0 (gpu required)
- Pandas>=2.2
- Python>=3.6
- NumPy >= 1.13.3
- Cupy >= 12.0
- SciPy >= 0.19.1
- Scikit-Learn >= 0.23


## Usage
When you start to perform cluster analysis on a brand new dataset, we recommend that you first execute the script located at ‘\SDJNMF-code\SDJNMF\S.V.Z.A.py’ in order to dig deeper into the similarities and dissimilarities of the cells in the dataset, and to lay down the a priori knowledge base for the subsequent clustering operations. for subsequent clustering operations. Afterwards, you can continue to run the example script located at ‘SDJNMF-code\example\example1.py’ to obtain and view the results of the cluster analysis.

The Input data is located at ‘SDJNMF-code\test_data’.The .csv files are the input datasets of SDJNMF method.


Contact Information:

Junjie Lan, South China Agricultural University, Guangzhou, Guangdong, China. Email: lanjunjie_gdou@163.com

Jin Deng, South China Agricultural University, Guangzhou, Guangdong, China. Email: jindsmu@gmail.com

References:

[1] Shiga, Mikio et al. “SC-JNMF: single-cell clustering integrating multiple quantification methods based on joint non-negative matrix factorization.” PeerJ 9 (2020): n. pag.

[2] Lee, Daniel D. and H. Sebastian Seung. “Learning the parts of objects by non-negative matrix factorization.” Nature 401 (1999): 788-791.

[3] Boutsidis, Christos and Efstratios Gallopoulos. “SVD based initialization: A head start for nonnegative matrix factorization.” Pattern Recognit. 41 (2008): 1350-1362.

