# DNA-Binding-Protein-Classification
Project for NUS IT1244

## Team 16: DNA Binding Protein 
Team members: Vedam Akshata Jaishankar, Shah Keval Rahul, Jain 
Paridhi, Erica Yap Ping Xuan 
Our project consists of 2 files (including this README) and 2 folders. A brief 
overview of the files and how to run the project is provided below, using Jupyter 
notebook. 

### Code Folder 
This folder contains the 3 files including 2 that were given to us in the module 
for the project: 
1. IT1244_Team 16_Code.ipynb file: This notebook contains our group's entire 
coding aspect. Instructions for running the chunks are provided in the notebook 
itself as comments. The chunks are meant to be run in order.   
There exist some chunks of code that are present as multi-line comments, this is 
code that we had experimented with and chose not to use, but kept in case it was 
needed.  
2. Train.fasta file: file used for the training of our saved model 
3. Test.fasta file: file used for the testing of our saved model 
Be sure to import the 2 fasta files into the notebook before running the code. 

### Model and Dataset Folder 
This folder contains the following pickle files: 

Model 1: entire_stacked_model.pkl 

Our group's first model is a stacked ensemble. To enable the models we created 
to be saved and loaded quickly, they were saved as pickle files, but the code can 
be rerun at any time. 

Model 2: entire_rnn_model.pkl 

Our group's second model is an RNN with a bidirectional LSTM. To enable the 
models we created to be saved and loaded quickly, they were saved as pickle 
files, but the code can be rerun at any time. 

### Report  
A 5-page document that details on our research and methods for this project.
