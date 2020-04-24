# Human Activity Recognition
 Predicting Human Activity Recognition (HAR) Using Smartphone Data


This is the mini-project of Data Science Senior Capstone.This project uses regression models to classify Human Activity based on sensor values. This project used pandas, sklearn, and matplotlib python libraries. The models used in this project are lasso and fandom forest. 
	To run the project, download the project zip file and place it on the Desktop. Unzip the file and open the terminal. Type in the following code in the terminal:
		cd Desktop
		cd project
		python main.py (to see the results of the two objects)
		python tmp.py (to see the graphs)
	Moreover, in main file, you need to change the method in order to see the results for each object. To change the method, screw down to the last several lines of the file and change the method into “one” or “two”. Method one shows the result of accuracy and confusion matrix using lasso and random forest. Method two shows the predictions and accuracy of using random forest while varying the number of features from 100 to 561. 