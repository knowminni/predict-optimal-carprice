# Predict Optimal Car Price
Using Gradient Boosting Regressor to predict Optimal Price of a Car.

The dataset used in the project was sourced from www.numyard.com/dsap/
Each row of the dataset consisted of both categorical and numerical columns which were features of that particular car.
The features are:
 0   symboling         
 1   make              
 2   fueltype          
 3   aspiration        
 4   doornumber        
 5   carbody           
 6   drivewheel        
 7   enginelocation    
 8   wheelbase        
 9   carlength         
 10  carwidth          
 11  carheight         
 12  curbweight        
 13  enginetype        
 14  cylindernumber    
 15  enginesize        
 16  fuelsystem        
 17  boreratio         
 18  stroke            
 19  compressionratio  
 20  horsepower        
 21  peakrpm            
 22  citympg           
 23  highwaympg         
 24  price
 
The model is built using Gradient Booster Regressor and the Hyperparameter Tuning is done using GridSearchCV.
The model's accuracy is measured using R2 score and Mean Absolute Percentage or MAPE.
