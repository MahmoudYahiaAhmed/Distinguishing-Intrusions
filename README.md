# Distinguishing-Intrusions
![image](https://user-images.githubusercontent.com/109751694/209457729-2c2ba591-eae5-4a79-821a-506aff3d9241.png)

## Data set 
UNR-IDD: Intrusion Detection Dataset using Network Port Statistics https://www.kaggle.com/code/sripadkarthik/ids-using-ml/data?select=UNR-IDD.csv

![image](https://user-images.githubusercontent.com/109751694/209457703-be4e7b0e-d4a4-457b-a88b-437b4903d4f1.png)
![image](https://user-images.githubusercontent.com/109751694/209457709-f7809521-90ae-4f6e-9129-b14f3371cbfd.png)
![image](https://user-images.githubusercontent.com/109751694/209457713-64398013-4802-466d-89c2-42ced4cce5dd.png)
## Flowchart For used Preprocessing 
![image](https://user-images.githubusercontent.com/109751694/209457740-9a8bee38-17c0-4db7-8dc1-2bd187431b56.png)
All plots done by TSNE https://en.wikipedia.org/wiki/T-distributed_stochastic_neighbor_embedding
## Baseline Model
![image](https://user-images.githubusercontent.com/109751694/209457767-35cc2d2d-f8dd-4ab6-8b0c-afe968db75fb.png)
![image](https://user-images.githubusercontent.com/109751694/209457763-43299ccd-4e8d-4342-adde-8b51839b7383.png)
![image](https://user-images.githubusercontent.com/109751694/209457773-139d626c-5d3d-4136-add8-28a9d54f738f.png)
![image](https://user-images.githubusercontent.com/109751694/209457776-9afbf703-210a-4bae-ad79-ececfeaafa01.png)
## Dimensionality Reduction (PCA)
![image](https://user-images.githubusercontent.com/109751694/209457789-6a802eb5-fe09-41d0-9a23-082512206f6e.png)
![image](https://user-images.githubusercontent.com/109751694/209457793-5fc7539d-98e7-4eb7-910c-0fb67ba9608c.png)

## Feature selection
### (Mutual Info)
![image](https://user-images.githubusercontent.com/109751694/209457809-211e5233-d227-4641-a7e7-d9ad08a120d4.png)
### (ANOVA)
![image](https://user-images.githubusercontent.com/109751694/209457817-57e86c3d-a674-4f36-a800-91d8ec5cf62c.png)
![image](https://user-images.githubusercontent.com/109751694/209457823-929cbc06-4200-4795-b574-58ab60a289ee.png)
![image](https://user-images.githubusercontent.com/109751694/209457835-17af6b74-c819-4a40-ae07-bfd25a87f82e.png)

## Using Deep Learning (Fully Connected NeuralNetwork)
### HyperParameters
Batch size=32,64,128
Hidden Layer= 1,2,4,8
Neurons/Layer= 10,20,30,40
Learning Rate= 0.1,0.01,0.001
Optimizers= AdamW, SGD(momentum=0.1,0.5,0.9),Rprop
Activation Functions= Relu,LeakyRelu,Sigmoid,Tanh
## Best HyperParameters
![image](https://user-images.githubusercontent.com/109751694/209457905-5ab76330-9440-4559-82e6-d3dbe682c237.png)
![image](https://user-images.githubusercontent.com/109751694/209457913-0104bbed-4ec3-4589-9e41-28bb71e07ffa.png)

Obtaining and evaluating baseline performance model (MLP). Applying Dimensionality reduction, Feature selection to compare which one of them would improve the result accuracy. Also, we understand the impact of various values in Batch Size, learning rate, optimizers, hidden layer, neuron number, and activation functions on the accuracy result. After collecting different combinations of values from different experiments we are able now to deal with deep learning problems






