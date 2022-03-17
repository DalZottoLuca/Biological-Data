
----------------------- READ ME ----------------------- 

The final models are described in the notebook:

- Biological Data project - group 8.ipynb

and this notebook is the only one where we have reported the solutions of all the successive
questions.

In this folder, we report some additional trials with different hyper-parameter 
configurations that we have tried for our models. As described in the report, firstly, 
we tried a BLAST search with the default parameters against Uniprot, UniRef90 and UniRef50. 
The performances of these models are reported in the notebooks:

- BD project uniprot.ipynb
- BD project uniref90.ipynb
- BD project uniref50.ipynb

Then we reduced the maximum number of hits of the BLAST search to 100. Moreover, we changed
some parameter of PSI-BLAST, namely the number of iterations (2, 3 or 4) and the E-value
threshold. The results of this trials are reported in the notebooks:

- BD project uniref90 100hits 4iter.ipynb
- BD project uniref90 100hits 3iter.ipynb
- BD project uniref90 100hits 2iter.ipynb
- BD project uniref90 100hits 2iter eval0001.ipynb