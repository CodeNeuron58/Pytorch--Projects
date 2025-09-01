# MNIST and Fashion-MNIST Classification Project

## Overview
This project implements deep learning models to classify fashion items (Fashion-MNIST) using PyTorch. The goal is to try and achieve high accuracy through various model architectures and optimization techniques.

in this i have first achieved arounf 83 percent accouracy by training in cpu , not using the whole dataset just a subset of it. and then i have used the full dataset and the train and test accouracy comming out to be 98 and 88 percent approximately. so i saw the without hassle a base model is overfitting. so , to reduce overfiting i used batch normalozarion , droppit and regulization/weight decay and then the aacrracy comes up to be 94 and 89 percent approximately . now comes the hypertunign part , i will be ising optuna 
