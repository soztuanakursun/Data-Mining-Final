# DATA MINIG FINAL PROJECT : D I A B E T E S

This project has been prepared by the M: K: S group as the final assignment of the dataming course.
---
Before reading the ReadMe file;
All files related to the project have been collected in this repository.
* ### [requirements.txt](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/requirements.txt)
> ***The name and version values of libraries used for the project.***
* ### [İmages](https://github.com/soztuanakursun/Data-Mining-Final-/tree/main/images)
> ***All images used in the project and report***
* ### [Reports File](https://github.com/soztuanakursun/Data-Mining-Final-/tree/main/Report%20Files) 
> ***The folder that contains the report.***
* ### [Diabets.csv](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/diabetes.csv)
> ***Database file***

---
1. **Abstract**
2. **Team Information adn Team Members**
3. **Description The Project**
4. **Assigments**
   - *Editing Data*
   - *Correlation Analysis*
   - *Classification Task using 3 different types of classification*
   - *Compare Performance and Observation*
   - *Sub-tasks Requested From Us*
 
5. **Conclusion**
 


## Abstract

In this project we are going to realize, we will predict whether a diabetic patient will be sick or
not. Based on the data kept in Excel; it is aimed to segment, group and organize patients.Some
information is available in our data set to make this prediction


## Team Information  and Team Members
The **M:K:S** team took part in this project. In this project, each member worked to fulfill his or her duties completely. Project members:
* **Söz Tuana Kurşun**
* **Mert Furkan Ergüden**
* **Mehmet Kubilay Elüstü** 

Although there are different libraries
 we all work with, we used pandas and 
numpy libraries in common to organize and call data.(MERT-TUANA)

*What we mean by organizing data,Was there any blank data to see them and 
we linear regressed the 0 values ​​we saw and eliminated the 0s.(TUANA)*

*And instead of regression, we averaged the values ​​and filled with it.(MERT)*

*then we drew some shapes to visualize(scatter features and order of importance) (MERT)*

*We used the heatmap we learned in the first lessons.To understand the relationship between each features.(KUBİLAY)*

*then we applied clustering(TUANA)
and we got what we wanted finally..Classification!We tried 3 types
 of classification methods so that we know which one is more reliable.(TUANA)*

*In the last part, we found the method that we get the most efficiency by comparing their performance.(KUBİLAY)*


 

## Description The Project
In this project, many operations were carried out with the python programming language and [libraries](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/requirements.txt).

We will predict whether a diabetic patient will be sick or not. We have a file called [Dataset](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/diabetes.csv)
 and according to this data; It is aimed to divide, group and organize patients into sections. It is available in many of our information sets to make this prediction. These; Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age and outcome. This means that if the result is 1, the patient is diabetic, otherwise 0.


## Assigments

## 4-1.Editing Data
First of all, we examined our data and identified its deficiencies. We provide outputs by writing some commands with the Python programming language.

![alt text](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/images/head.png?raw=true)
---

![alt text](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/images/info.png?raw=true)




We determined the values that should be in real life. For example Values like glucose,blood pressure etc. can not be 0, we have to regulate them.

![alt text](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/images/double.png?raw=true)



we showed the distribution plots of the features.And the last features for editing data data.shape,this code means we have the 768 patients and 500 are not sick.


![alt text](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/images/scatter.png?raw=true)



---

## 4-2.Correlation Analysis
Here we  examined the correlation analysis by  using Pandas and Seaborn  libraries here.

![alt text](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/images/corr.png?raw=true)

---

![alt text](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/images/heatmap.png?raw=true)


## 4-3.Classification Task using 3 Different Types of Classification
In the stage, we create the algorithms.We used 3 different types of classification. These are logistic
regression,KNN and random forest.Using these three, we chose the classification that gave the closest results and made a performance comparison. We discussed these results in the conclusion part.





## 4-4.Compare Performance and Observation
In this section, we compared classifications performance using pyplot.plot and we got such a result.
 
![alt text](https://github.com/soztuanakursun/Data-Mining-Final-/blob/main/images/compare.png?raw=true)



## 4.5-)Sub-tasks Requested From Us
 

## Conclusion
