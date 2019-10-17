## Sales Prediction Model
Sample end to end sales prediction deployment projects from data collection to deployment of models.

## Environment and tools
1. scikit-learn
2. pandas
3. numpy
4. flask

## Installation

`pip install scikit-learn pandas numpy flask`

`python model.py`

`python app.py`

Developing a machine learning model using Scikit-Learn, TensorFlow, Keras, PyTorch etc, the ultimate goal is to make it available in production. Often times when working on a machine learning project, we focus a lot on Exploratory Data Analysis(EDA), Feature Engineering, tweaking with hyper-parameters etc. But we tend to forget our main goal, which is to extract real value from the model predictions

Deployment of machine learning models into production means making your models available to the end users. However, there is complexity in the deployment of machine learning models. This project aims to make you get started with putting your trained machine learning models into production using Flask API.

### What is Linear Regression
Regression is basically classification where we forecast a number instead of category. Examples are car price by its mileage, traffic by time of the day, demand volume by growth of the company etc. Regression is perfect when something depends on time.

Everyone who works with finance and analysis loves regression. It's even built-in to Excel. And it's super smooth inside — the machine simply tries to draw a line that indicates average correlation. Though, unlike a person with a pen and a whiteboard, machine does so with mathematical accuracy, computing the average interval to every dot.

!()[images/classical-ml.png]

### Regression
Drawing a line through tese dots. Yep, that's the machine learning

!()[images/lr.png]

Regression today is used for:
* Any number-time correlation

We'll use a linear regression algorithm to predict the sales value in the third month using rate of interest and sales of the first two months.

### Why Flask?
* Easy to use.
* Built in development server and debugger.
* Integrated unit testing support.
* RESTful request dispatching.
* Extensively documented.

### Project Structure
This project has four parts:

>model.py — This contains code for the machine learning model to predict sales in the third month based on the sales in the first two months.

>app.py — This contains Flask APIs that receives sales details through GUI or API calls, computes the predicted value based on our model and returns it.

>request.py — This uses requests module to call APIs defined in app.py and displays the returned value.

>HTML/CSS — This contains the HTML template and CSS styling to allow user to enter sales detail and displays the predicted sales in the third month.

!()[images/pipeline.png]

