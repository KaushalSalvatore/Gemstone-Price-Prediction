# Gemstone-Price-Prediction
This is machine learning web app that use to predict gemstone price according to given Parmenter in data set.

## Click the following link for view the deployed project:
- https://boston-price-prediction.onrender.com/

## Webview screenshots
![Screenshot (78)](https://github.com/KaushalSalvatore/Gemstone-Price-Prediction/assets/50286592/f296e9ed-6ecc-47e4-b537-5d3570b04d4f)
![Screenshot (77)](https://github.com/KaushalSalvatore/Gemstone-Price-Prediction/assets/50286592/5221f7f4-8e7f-4956-8f54-d82af318a51a)

## ML Project lifeCycle Stp by Step

- Data Collection
- Data Analysis
- Data Visualization
- Feature Engineering
- Feature Selection
- Model Building
- Model Evalution
- Hyper Parameter Tunning
- Creating Pickle file
- Web App using Flask
- Deployment

### Steps
#### 1. virtual environment 
```bash
    1.1 Create a new Environment
    virtualenv Gemstone_venv  
```
```bash
    1.2 Remove Environment 
    rmvirtualenv Gemstone_venv 
```
#### 2. Setup.py and requirements.txt
```bash
    2.1 Create requirements.txt :- a type of file that usually stores information about all the libraries, modules, and packages in itself that are used while developing a particular project.
```
```bash
    2.2 Create setup.py :- a module used to build and distribute Python packages. It typically contains information about the package, such as its name, version,and dependencies, as well as instructions for building and installing the package.
```
#### 3. Logging And Exception Handling
```bash
    3.1 Exception :- create a exception.py class for handle custom exception 
```
```bash
    3.2 logging :- This is the class whose objects will be used in the application code directly to call the functions. LogRecord : Loggers automatically create LogRecord objects that have all the information related to the event being logged, like the name of the logger, the function, the line number, the message, and more.
```
#### 4. download data set and EDA model training 
```bash
    4.1 download data set link :- 
    - https://www.kaggle.com/datasets/colearninglounge/gemstone-price-prediction?resource=download   
```

```bash
   4.2 Data Set Characteristics:
- Number of Instances: 193573 
- Number of Attributes: 10 numeric/categorical predictive.
```

```bash
    4.3 Data Attribute Information
    - **id:** unique identifier of each diamond
    - **carat:** Carat refers to the unique unit of weight measurement used exclusively to weigh gemstones and diamonds.
    - **cut:** Quality of Diamond Cut
    - **color:** Color of Diamond
    - **clarity:** Diamond clarity is a measure of the purity and rarity of the stone, graded by the visibility of these characteristics under 10-power magnification.
    - **depth:** The depth of diamond is its height in millimeters  measured from the culet bottom tip to the table flat, top surface
    - **table:** A diamond's table is the facet which can be seen when the stone is viewed face up.
    - **x:** Diamond X dimension
    - **y:** Diamond Y dimension
    - **x:** Diamond Z dimension
    - **Price:** Price according to the deatials
```
```bash
    4.4 create EDA_Gemstone_price.ipynb class for Exploratory data analysis (EDA)
```
```bash
    4.5 create Model_Training_Gemstone.ipynb class for model training ,Transforming the data with pipeline and Hyperparameter tuning
```
```bash
    4.5 create Explainability_with_LIME.ipynb class for Model Explainability with LIME(Local Interpretable Model-agnostic Explanations.)
```
#### 5. Components

```bash
    5.1 data_ingestion.py this class use for collect the data for anywhere it can be cloud , sql , local data set    
```
```bash
    5.2 data_transformation.py this class use for data cleaning , feature engineering and other things. 
```
```bash
    5.3 model_trainer.py this class use for traine data  with different machine learning algorithemns     
```
## Use Technologies

**python packages:** Pandas, Numpy, Scikit-learn, matplotlib ,seaborn

**ML Algorithms:** Regression Algo
 
**Framework:** Flask

**frontend:** Html, CSS

### Use python libraries
```bash
1. sys :- The sys module in Python provides various functions and variables that are used to manipulate different parts of the Python runtime environment.  
```
```bash
 2. LIME stands for Local Interpretable Model-agnostic Explanations. LIME focuses on training local surrogate models to explain individual predictions. Local surrogate models are interpretable models that are used to explain individual predictions of black box machine learning models. Surrogate models are trained to approximate the predictions of the underlying black box model. Instead of training a global surrogate model, LIME focuses on training local surrogate models. 

 - LIME is model-agnostic, meaning that it can be applied to any machine learning model. The technique attempts to understand the model by perturbing the input of data samples and understanding how the predictions change.
```
```bash
3. dataclasses :- a data class is a class that is designed to only hold data values. They aren't different from regular classes,but they usually don't have any other methods. They are typically used to store information that will be passed between different parts of a program or a system.
```

## Important Definition :
- **LinearRegression**
- **coefficients**
- **intercept**
- **Assumptions**
- **mean squared error**
- **Mean absolute error**
- **R square**
- **Adjusted r square**

## Feedback

if you have any suggetion and feedback and need any kind of project related help reach me out at
[linkedin](https://www.linkedin.com/in/kaushal-pandey-067898165/)

#### Thank You 