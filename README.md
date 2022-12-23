# CSE 6220 Project

## For CARE-CNN Model:

Run amazon_preprocess.py for building relation graphs, features and users information.

Run data_process.py for converting relaiton matrix into adjacency lists.

Run train.py to generate new trained model using the new dataset. 
(adjusting hyperparameters such as batch size, adding CARE model layers, etc.)

New Graph data generated for training:
https://drive.google.com/file/d/1OuowH3njrXJyBK2FyAoVwL2yM99rIVJZ/view?usp=sharing, https://drive.google.com/file/d/1W03RJ9RvwrqFHOXRWyWXLyzn9clHT0hX/view?usp=sharing, https://drive.google.com/file/d/1ZDPLkLtq_VXibRiCU4uykYlJY8iDT0y1/view?usp=sharing, https://drive.google.com/file/d/1faPmQwE1mwNBCF0vhUaynoHuOwktPEJh/view?usp=sharing, https://drive.google.com/file/d/1ilxstqzkQH8fNg3-n1mOMZ8K_S_KVKEF/view?usp=sharing, https://drive.google.com/file/d/1r8c9lhzOoMiF_MkxLV55S5EOmTiUaoLY/view?usp=sharing, https://drive.google.com/file/d/1zyhBJmpkLWq8nV1LzUCWEduvG8hLHMgF/view?usp=sharing

## For REV2 Model:

Run Dataset_preprocessing.ipynb to preprocess data and generate datasets to be used by REV2 model.

Run REV2.ipynb to iteratively update the fairness score for each reviewer, and generate results.

## For PC-GNN Model:

Run data_process.py to pre process the data.

Run main.py to generate new trained model and get results.
