# diabetes-AI-ML
diabetes detection using AI-ML Algorithms

	
    The objective of this project is to compare the accuracy of seven Machine Learning algorithms to 
    diagnostically predict whether or not a patient has diabetes, based on certain diagnostic measurements
    included in the dataset.

The seven Supevised algorithms for clssification problems used in this project are listed below:
    
    -  KNN Classiﬁer
    -  Logistic Regression
    -  Decision Tree
    -  Random Forest
    -  Gradient Boosting
    -  Naive Bayes Classiﬁer
    -  Support Vector Machine Classiﬁer

DATASET DESCRIPTION:
	The data set is originally obtained from the National Institute of Diabetes and Digestive and Kidney Diseases. It contains information of 768 women from Arizona, USA: 268 tested positive and 500 tested negative for diabetes. Each instance comprises of 8 attributes, all numeric, obtained from personal health data as well as results from medical examinations:
    -  Pregnancies: Number of times pregnant
		-  Glucose: Plasma glucose concentration at 2h in an oral glucose tolerance test.
		-  BloodPressure: Diastolic blood pressure 
		-  SkinThickness: Triceps skin fold thickness
		-  Insulin: 2-h serum insulin
		-  BMI: Body Mass Index
		-  Diabetes Pedigree Function 
		-  Age
		-  Outcome: Class variable

RESULT:
	The accuracies of the algorithms over mentioned dataset is give below:
  
  
            -----------------------------------------------------------
            |                                   |      Accuracy {%}   |
		|             Algorithm             |---------------------|
            |                                   |   Test   | Training |
		|-----------------------------------|----------|----------|
		| Logistic Regression               |   80.20  |   76.21  |
		| Support Vector Machine Classiﬁer  |   79.16  |   76.56  |
		| Naive Bayes Classiﬁer             |   78.12  |   75.69  |
		| KNN Classiﬁer                     |   77.08  |   79.16  |
		| Gradient Boosting                 |   76.04  |   80.56  |
		| Random Forest                     |   75.52  |    1.0   |
		| Decision Tree                     |   74.48  |    1.0   |
            |---------------------------------------------------------|

The Logistic Regression algorithm and Support Vector Machine giving the highest accuracy of 80.20% and 79.16%, respectively hold best for the analysis of diabetic data.
