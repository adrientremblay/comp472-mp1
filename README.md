# comp472-mp1

https://github.com/adrientremblay/comp472-mp1

### To start off
1. Make sure the goemotions.json is located in the same folder location as all the .ipynb files in this project.

### How to use Q1.ipynb
Step 1) Import the necessary libraries by running the first two code cells.\
Step 2) To get the number of entries for each label, run Cell 3. Cell 4 will print the content of the 
        dictionaries for both the emotions labels and the sentiments labels, with the number of entries assigned to each\
Step 3) This is to create the figures for the label distribution:\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.1) To get the histogram for the sentiments distributions, run the Cell 5. This will also save the figure as png in the same folder as Q1.inpynb.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3.2) To get the pie chart for the emotions distributions, run the Cell 6. This will also save the figure as png in the same folder as Q1.inpynb.

### How to use Q2(2.1-2.4).ipynb
1. Run all cells from top to bottom

### How to use Q2(2.5).ipynb
1. Run all cells from top to bottom

### How to use Q3.ipynb
There are three pretrained word embedding models: word2vec, Wikipedia Gigaword 2014 5th Ed and the Fastest Wikipedia News from October 2017
#### Preliminary Steps
Step 1) Import the necessary libraries by running the first code cells under the section "Importing the libraries".\
Step 2) Tokenize each of the posts. Run the cell in order in the section "Generate the tokenized words" to do so.\
You can use the cell to check if the amount of tokenized posts is the same as the original one.
#### Using a word embedder to train the model
Step 1) Choose the word embedding model you wish to use by going to their associated section.\
Step 2) To generate the word embeddings, click the nodes in order in the section "Preparing the Data".\
Step 3) To train the models, click the nodes in order in the section "Training the models".\
Step 4) To get the performance metrics, click the nodes in order in the section "Evaluating the models".
