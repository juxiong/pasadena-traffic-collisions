# Welcome to Pasadena Traffic Collisions

We are a group at Caltech who decided to analyze Pasadena traffic collision data to improve the traffic system. We followed the following steps. 

### Data Preprocessing
We Preprocessed data so that it could be used by a typical sklearn classifier. This includes rounding all times to the nearest hour so that it could be more easily encoded into a onehot vector, and also writing a general function to onehot encode columns.

### Model Building
In the data, there are many unknown causes for accidents. So, we have created a model that predicts unknown values for cause of accident.
