## Electric Motor Temperature Prediction

**Project description:** The main purpose of the data set's recording is to be able to model the stator and rotor temperatures of a PMSM in real-time. Due to the intricate structure of an electric traction drive, direct measurement with thermal sensors is not possible for rotor temperatures, and even in case of the stator temperatures, sensor outage or even just deterioration can't be administered properly without redundant modeling.In addition, precise thermal modeling gets more and more important with the rising relevance of functional safety.

### Objective:
Predict Motor temperature (“PM”) based on other attributes available are like ambient, coolant, torque, current d_q components, voltage d_q components, stator yoke, stator tooth, stator winding, permanent magnet and profile_id.

### Data Set Details

998070 rows X 14 Columns-Continuous Data 

### Relationship among variables

<img src="images/correlation.png?raw=true"/>

### Algorithms Used
- Multiple Linear Regression
- Ridge Regression
- Lasso Regression
- Elastic net regression
- Decision tree Regressor
- Xgboost Regressor
- GBM model
- Random Forest Regression
- Earth: Multivariate Adaptive Regression Splines

#### H2O.ai models:

- Neural network
- Random forest
- Auto ML
- GBM

### Model Evaluation
- Random Forest
<img src="images/model.png?raw=true"/>
