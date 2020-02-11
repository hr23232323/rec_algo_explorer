# Recommendation Algorithm Explorer
A project to explore different recommendation algorithms using Netflix Competition data. 

## About
This project was built to explore different recommendation algorithms and understand each of their shortcomings/merits. The project is designed in a way where each of the algorithms will be developed using jupyter notebooks, followed by a Python script implementation. Eventually, the goal is to build a library of recommendation algorithms where users can understand implementation details, compare performance and pick algorithms that best fit their needs. 

## Usage
Before you can run any code, you'll need to download the raw data associated with this project, which can be found [here](https://www.kaggle.com/netflix-inc/netflix-prize-data/data). Download the data, put it at the base of your project directory in a folder called `data` and add that folder to the `.gitignore` file. 

This project is primarily built in Jupyter notebooks/python 3.7.1 and involves packages which need to be installed. To make getting started with this project easier, we've created a requirements.txt file which contains all the different python packages needed. You can utilize this file (after cloning this repository) by using the following command:

```
pip install -r requirements.txt
```

We suggest starting with a specific algorithm, exploring it's corresponding jupyter notebook and go from there. 
