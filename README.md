# Parameter optimization of SVM
# Parameter Optimization of SVM

This project was created for the UCS654 course and focuses on implementing Support Vector Machine (SVM) and parameter optimization using a fitness function.

About SVM and Parameter Optimization

SVM is a popular Supervised Learning algorithm used for Classification and Regression problems. In Machine Learning, SVM is primarily used for Classification problems. The kernel, C, and gamma are some of the most important parameters of SVM that can be changed to achieve higher accuracy. This process is known as Hyperparameter Tuning, and it can be performed using GridSearchCV to optimize the parameters.

In this project, a fitness function was used to optimize the SVM parameters. The results of the optimization are presented in the table below.

# Dataset

The Room Occupancy Estimation dataset used in this project was downloaded from the UCI Machine Learning Repository. This multi-variate classification dataset contains 10129 instances and 16 attributes. The dataset is used for estimating the number of occupants in a room using non-intrusive environmental sensors such as temperature, light, sound, CO2, and PIR.

Results

The final result table shows the best accuracy, kernel, nu, and epsilon values for each of the ten samples. The sample with the best accuracy is sample 9, which has an accuracy of 0.97 with a Poly kernel, nu = 1.27, and epsilon = 6.87.

The convergence graph shows that the model is well trained and the parameters have been optimized due to the small gap between the training and cross-validation curves.

Running the Code

To run the code, ensure that you have installed the necessary dependencies. Then, run the svm.py file using a Python IDE or the command line.

bash
Copy code
python svm.py
Acknowledgments

Special thanks to the UCI Machine Learning Repository for providing the Room Occupancy Estimation dataset.
