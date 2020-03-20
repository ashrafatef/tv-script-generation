### **This Part of Deep Learning Nanodegree from Udacity**

# TV Script Generation Project

### Project Description 


In this project, you'll generate your own [Seinfeld](https://en.wikipedia.org/wiki/Seinfeld) TV scripts using RNNs.  You'll be using part of the [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv) of scripts from 9 seasons.  The Neural Network you'll build will generate a new ,"fake" TV script, based on patterns it recognizes in this training data.

---

### Stack
  
- Pytorch
- numpy
- panda 
- matplotlib

---

### Dataset

- You can Download [Seinfeld dataset](https://www.kaggle.com/thec03u5/seinfeld-chronicles#scripts.csv)

---

### Results

- You can find the results in generated_script_1_.txt

---

### What I leant in this project 

-  Apply pre-processing for text data ( Lookup Table , Tokenize Punctuation ).
- Apply batching for dataset to batch data into chunks based on batch size using DataLoader and TensorDataset classes in Pytorch.
- Apply unit testing through most of used functions. 
- Understanding RNN architecture and its different types ( GRU and LSTM ) , apply KSTM in this project.

- Understand feedforward and backward operations for training our model how it works in RNN.
-Dealing with hyperparamter as usual which control our model accuracy and it plays an important role in RNN , I tried different values you can check it in the notebook .


