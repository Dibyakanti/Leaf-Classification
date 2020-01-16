# Leaf-Classification

## Objective

There are 185 classes of leaves , task is to find which class the leaf belongs to.

## Data Analysis

The pictures have been augmeneted in the train set itself so any further augmentation by rotation or inversion does not help the model. A few outliers in the train set where two leafs are too small to be differentiated from one another affects the model and hence removing those helped the model a lot.

## Neural Net used :

The Neural Net used has one inception net and a skip connection,followed by 4 dense layers of depth 2048,1024,512,256.  
 

