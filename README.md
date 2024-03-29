
 An issue might occur when trying to view the jupyter notebook , check this link to view the notebook(https://nbviewer.org/github/AbdulRasheed6/India_Flight_Price/blob/main/Flight_Prediction.ipynb)


# India Flight Fare Prediction: 

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview)
  * [Research questions](#research-questions)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)
  * [Insights](#insights)
  * [Future scope of project](#future-scope)


## Demo
Link: [https://india-flight-price.herokuapp.com/](https://india-flight-price.herokuapp.com/)

[![](https://i.imgur.com/R1g2wvC.png)](https://india-flight-price.herokuapp.com/)

[![](https://i.imgur.com/p0aeL6c.png)](https://india-flight-price.herokuapp.com/)

## Overview
Flight ticket prices can be something hard to guess, today we might see a price, check out the price of the same flight tomorrow, it will be a different story. 
We might have often heard travellers saying that flight ticket prices are so unpredictable.
Here you will be provided with prices of flight tickets for various airlines between the months of March and June of 2019 and between various cities. 

This is a Flask web app which predicts fare of Flight ticket.

## Research questions
Research Questions
The aim of our study is to answer the below research questions:
a) Does price vary with Airlines?
b) How the price changes with change in Source and Destination?
c) Does price also vary with total_stops






## Insights/Answers to research questions
Jet Airways buisness and Jet Airways are the most expensive airline, while spicejet and indigo are the cheapest airline.
As the number of stops increases the prices also increases.
Delhi, kolkata and banglore are the most expensive airport to take off from.
Spicejet and vistara premium economy airways takes lesser time to get to their destination compared to other airways.
It takes more time for airlines to get to banglore compared to other destinations, it might be as a result of traffic or distance.


## Installation
The Code is written in Python. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can deploy  the web app using github  or download the heroku 
ctl to manually deploy this project.

[![](https://i.imgur.com/dKmlpqX.png)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── style 
│   ├── css
├── template
│   ├── home.html
├── Data_Train.xlsx
├── flight_price.ipynb
├── Procfile
├── README.md
├── Data_Test.xlsx
├── app.py
├── flight_rf2.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 


## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
