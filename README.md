# Car-selling-price
A simple flask app for prediction of second hand car prices

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Dataset](#dataset)
  * [Future scope of project](#future-scope)


## Demo
https://user-images.githubusercontent.com/51751926/123714260-99611280-d893-11eb-80f4-5f7a11016e63.mp4

## Overview
This is a Flask web app which predicts price of different cars for a person who wants to sell. <br>
Year in the app is basically the year that person bought the car <br/>
Rest of the features are self explanatory

## Installation
The Code is written in Python 3.9.1. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). <br/>
Make sure that pip is upgraded if not:
```bash
pip install --upgrade pip
```
- Cloning the repository :
     - 🦖 go to the folder in your device where you want to clone <br/>
     - 🦖 make sure that git is installed already if not click [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
```bash
git clone https://github.com/amey16/Flight-fare-prediction.git
```
If you face any import error just run command pip install library_name for windows | sudo apt install library_name for linux

## Deployement on Heroku(optional)
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

![image](https://user-images.githubusercontent.com/51751926/122658097-f61f4780-d186-11eb-8b74-2b37d9bbb4b9.png)
Click on the create app option once you reach this page
<br/>
Follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.
  
## Directory Tree 
```
├── app.py
├── car data.csv
├── EDA--model-implementation.ipynb
├── random_forest.pkl
├── tree.txt
├── 
├── .ipynb_checkpoints
|   ├── EDA--model-implementation-checkpoint.ipynb
├──     
├── templates
    ├── index.html
        
```

## Dataset

The dataset was collecected from kaggle .To go to the dataset [click here](https://www.kaggle.com/nehalbirla/vehicle-dataset-from-cardekho).
<br />
What the columns of dataset look like - <br/>
Feature name | Feature meaning
:---: | :---:
name | Name of the vehicle
year | Year that vehicle was bought in
selling_price | labels as selling price to train
km_driven | Number of kilometers driven
fuel | CNG,Diesel or Petrol
seller_type | Individual or Dealer
transmission | manual or Automatic
Owner |  0,1 or 3 how many owners did car belong to


## Future Scope

* Can be used as third party app for websites for second hand vehicles
