# Anomaly-Detection-for-Autonomous-Drone
This reposiory contains the analysis on the Robot Operating System Data obtained via Signal Processing Cup

The data was extracted from the on-board ROS of the Drone. The ROS file's data was transformed to BAG files so that the final CSV files could be obtained.

The CSV thus obtained several features that denote the sensor readings. This includes accelerometer value, GPS velocity, etc. 

The dataset is shuffled for normalizing the distribution. The dataset consists of instances belonging to both, Normal as well as Abnormal Classes. 

Performance:

Got 87% accuracy in Multinomial Bayesian Network.
This actually improved on using Gaussian Bayesian Network, accuracy being 93%.

Future Work:
1. Bayesian Belief Network
2. Ensemble Methods
3. Apply Cross validation for authenticity
4. Noise Removal due to varied distribution.
