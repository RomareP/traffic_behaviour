# Behavior of the Urban Traffic of the City of Sao Paulo

In recent years with the exponential growth of the economic system, the movement of goods and people has become essential. 
The modern society accompanied by an increase in mobility. 
Carrying out a movement with any mode of transport entails for the user a series of costs of use and travel times of a network element which depend on:
- the levels of use of the element itself and possibly other elements which interact with it;
- the characteristics of the network element. <br> <br>
About costs, we can distinguish measurable charges:
- monetary type;
- non-monetary (essentially timing charges not measurable).

# In this project the contribution 
aim to compare different regression and Neural Networks techniques to verify the possibility to develop other kinds of prediction with the dataset proposed, considering hour as independent variable.

# Dataset
19 variables of the traffic and streets features: Day, Immobilized bus, Vehicle excess, Running over, Occurrence involving freight, Lack of electricity, Point of flooding, Defect in the network of trolleybuses, Semaphore off, Slowness in traffic (%), Hour (Coded), Broken Truck, Accident victim, Fire vehicles, Incident involving dangerous freight, Fire, Manifestations, Tree on the road, Intermittent Semaphore

# Features Extraction
The hour variable is split into 27 di↵erent binary columns: the column called 1 represent 7.00 am, the column called 2 represent 7.30 am, the column called 3 represent 8.00 am and so far and so on.
At this point, the dataset is divided into X vectors (e.g. a cluster of all independent variables) and y vector (e.g. a cluster of the dependent variable).

# Models 
Polynomial Regression, Decision Tree Regressor, Random Forest Regressor, MLP Regression, LSTM.

# Evaluations
R^2, MAE, MSE, RMSE.

# Considerations
Please, consider the overfitting, in particular when using LSTM.
