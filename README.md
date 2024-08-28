# SegCol Task 2

You can also create your list of filenames and their corresponding segmentation maps with generate_ann.py.

The DeepLab models can be trained by running train.py. 
Check the argument_parser.py to ensure a good configuration of running. 

### Setup in argumennt parser
root-dir         : location of your data folder
train-img-file   : the csv file with the names of the training images
train-segm-file  : the csv file with the names of the training annotations
valid-img-file
valid-segm-file


For saving the results, you can make use of save_results.py 
