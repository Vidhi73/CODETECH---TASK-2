 Name - VIDHI KOHLI 
Company - CODETECH IT SOLUTION 
ID - CT08DS1780
Domain : Web Development 
Duration : 10th June 2024 - 10th July 2024
Mentor : SRAVANI GOUNI 

 Overview of the project  
 
 Project : Weather Forecast App 
 
 Introduction to Weather Forecasting 
 
Weather forecasting is the task of predicting the state of the atmosphere at a future time and a specified location.
Traditionally, this has been done through physical simulations in which the atmosphere is modeled as a fluid. The present state of the atmosphere is sampled, and the future state is computed by numerically solving the equations of fluid dynamics and thermodynamics. 
However, the system of ordinary differential equations that govern this physical model is unstable under perturbations,
and uncertainties in the initial measurements of the atmospheric conditions and an incomplete understanding of complex atmospheric processes restrict the extent of accurate weather forecasting to a 10 day period, 
beyond which weather forecasts are significantly unreliable.
Machine learning, on the contrary, is relatively robust to perturbations
and doesn’t require a complete understanding of the physical processes that govern the
atmosphere. Therefore, machine learning may represent a viable alternative to physical models in weather forecasting.

Machine learning is the ability of computer to learn without being explicitly programmed. It allows machines to find hidden patterns and insights.  
In supervised learning, we build a model  based on labeled training data. The model is then used for mapping new examples. 
So, based on the observed weather patterns from the past, a model can be built and used to predict the weather.
This project work focuses on solving the weather prediction anomalies and in-efficiency based on linear regression algorithms and to formulate an efficient weather prediction model based on the linear regression algorithms 

Problem Statement : 

Weather prediction is a useful tool for informing populations of expected weather conditions. Weather prediction is a complex topic and poses significant variation in practice.
We will attempt to understand and implement a weather prediction application using the linear regression. 

Project Scope :
 
Weather forecasts are made by collecting as much data as possible about the current state
of the atmosphere (particularly the temperature, humidity and wind) to determine how the
atmosphere evolves in the future. 
 
However, the chaotic nature of the atmosphere makes the forecasts less accurate as the range of the forecast increases.

 Traditional observations made at the surface of atmospheric pressure, temperature, wind speed, wind direction, humidity, precipitation are collected routinely from trained
 observers, automatic weather stations or buoys.During the data assimilation process, information gained from the observations is used In
 conjunction with a numerical model's most recent forecast for the time that observations were made to produce the meteorological analysis.  The complicated equations which govern how the state of a fluid changes with time require supercomputers to solve them.
 
The output from this model can be used the weather forecast as alternative.

 Design and Implementation Constraints : 
 
The product is developed using API server. The back-end database are CSV files on the basis of that, the prediction takes place.
The product is a general-purpose application software in which any user can gather the predicted information. The linear regression is used that predicts the weather based on the previous analysis of a data. 

Major Components:

Data Collection: The feeding historical data to the system, this could be from specific region.

Data Cleaning: Under this component the data like the missing data, duplicated data is found and bad data is weed out

Data selection: Under this stage, relevant data related to analysis is retrieved and classified under 6 attributes

User Documentation : 

The product is a general-purpose application software where any user can access the software to gather information about the weather based on a current or a previous data analysis. 
In this  product the software makes a request to the server to access the current dataset through which the data is analyzed using various machine learning algorithms. 

Assumptions and Dependencies : 

The software product is dependent on a dataset that is been retrieved from the server using various commands.

The product will work based on the algorithm that has been discussed above
