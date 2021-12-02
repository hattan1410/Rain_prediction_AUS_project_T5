### Rain prediction inAustralia project_T5

#### Question/need:
* What is the framing question of your analysis, or the purpose of the model/system you plan to build? 
* I want to Predict if tommorow will rain by training classification models on the target variable RainTomorrow. 
* Who benefits from exploring this question or building this model/system?
* Service men,farmers ,any person or institues where rain affect there work

#### Data Description:
* What dataset(s) do you plan to use, and how will you obtain the data?
* This dataset contains about 10 years of daily weather observations from many locations across Australia. 
* the data size\shape is (145461,23)
* I have obtained this dataset from https://www.kaggle.com/jsphyg/weather-dataset-rattle-package 
* What is an individual sample/unit of analysis in this project? What characteristics/features do you expect to work with? 
* A collection of daily weather observations from many locations across Australia. I expect to work with observations reading such as (Date,Location,MinTemp,MaxTemp,Rainfall,Evaporation,etc..)
* If modeling, what will you predict as your target?
* next day rain [RainTomorrow]

#### Tools:
* How do you intend to meet the tools requirement of the project? 
* currently I will use Knn as my main MTL model using python
* I will use python to  prepare the data before applying MTL modling using servrel librires such is pandas and sklearn
* Are you planning in advance to need or use additional tools beyond those required?
* most likly not, however if additional tools are required ro meet the requirmt then it will be used 

#### MVP Goal:
* What would a [minimum viable product (MVP)](./mvp.md) look like for this project?
* I hope to prove that there is a possplty to predict with high accurcy the rain baised on the data provided
