
# Decision tree from scratch

In this project, we implement a decision tree algorithm and use it to determine one of the indoor locations based on WIFI signal strengths collected from a mobile phone. We have included two different pruning methods. To evaluate the performance of our model, we 
use nested cross-validation with 10 outer and 10 inner folds.


## Dataset
You can load the datasets from the files ”WIFI db/clean dataset.txt” and
”WIFI db/noisy dataset.txt”. They contain a 2000x8 array. This array represents a dataset of 2000 samples. Each sample is composed of 7 WIFI signal strength while the last column indicates the room number in which the user is standing (i.e., the label of the sample). All the features in the dataset are continuous except the room number. You can load the text file with the ”loadtxt” function from Numpy.

## Usage
The whole code is contained in a Jupyter Notebook in a file called 'decision_tree.ipynb', so to run all cells, download the .ipynb file, open it with an IDE like PyCharm, VS Code,
Spyder, or using the terminal, and just click the button 'run all'. 

Before running the code input your path directory that contains your data to the project
to the 'path' variable. 

## Packages
numpy==1.21.6

matplotlib==3.2.2