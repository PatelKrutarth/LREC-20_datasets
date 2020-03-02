# Data: 
=========
There are three datasets:
- UNT.edu
- Texas.gov
- USDA.gov

All datasets are stored according to the following, common structure:

    dataset/
           /docs/       	<- pdf documents
           /split_ids/  	<- containing 3 train-dev-test splits of ids (append .pdf to locate the pdf file in `docs/` directory)
           /positives.txt/  <- list of IDs for the documents in the positive class
           /negatives.txt/  <- list of IDs for the documents in the negative class


Cite
==========
If you use the datasets, please cite the following paper:

> Krutarth Patel, Cornelia Caragea, and Mark E. Phillips. Dynamic Classification in Web Archiving Collections. Proceedings of the Twelth International Conference on Language Resources and Evaluation, 2020. 

