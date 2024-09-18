[Readme_Report.docx](https://github.com/user-attachments/files/17044406/Readme_Report.docx)

Readme – Report

( Logistic regression is used for carrying out this task. Premade dataset found in Kaggle was used and modified. 
Link to the dataset : https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset
Certain modifications were made to the dataset such as removing the columns trestbps, thalach, and thal. It was done so as it did not have much effect in providing the end results. As well as, it will be easier for patients to enter much lesser details.)

In todays world of technology in most of every sector, improvement in patient care and management with the advancement of technological innovation continues. Heart failure, which is a very common and fatal condition, necessitates serious approaches to early detection and care. 
This report presents the possibility of using logistic regression, a machine learning approach, to forecast the risk of heart failure in a mobile or miniature robotic platform. People can obtain real-time insights into their cardiovascular health state by integrating advanced algorithms with portable robotics. This allows them to take proactive steps to reduce risks and improve their overall well-being.

In short, by combining machine learning techniques such as the logistic regression within a movable or mini robot, can provide an application for predicting heart failure risk. 
This report showcases the importance and advantages of a heart failure prediction mini-robot that allows individuals to monitor their health and obtain essential health resources.
Functionality of the robot.
It will be a movable mini robot with two wheels on the side that can go around the hospital so that the patients can check on their own while they wait for their turn at the doctor. It can be used as a free quick check up robot. As well as doctors can use it as quick check up to get a prediction while waiting for blood or Xray results of patients.
The robot can be designed in a way where it consists of a mini screen which provides the option for patients to input his health condition levels such as for cholesterol, blood pressure etc. it then calculates using machine learning and states if the patient has a chance of heart failure. The robot can consist of information on precautions and measures.


Future uses and improvements:
Increased Healthcare Accessibility: 
The heart failure prediction mini-robot can be used in community health centers, retirement homes, and even isolated or underprivileged locations in addition to hospital settings.

Continuous Learning and Adaptation: 
By putting in place algorithms that are able to learn and adapt continuously, the mini-robot can evolve in parallel with new developments in healthcare and the unique characteristics of individual patients. The mini-robot can improve the accuracy and relevance of its prediction models over time by evaluating user feedback and real-world results. By taking an adaptable approach, the mini-robot may maximize its impact on patient outcomes and stay at the forefront of cardiovascular healthcare innovation.

Relationships with Wearable Devices: 
The mini-robot's seamless integration with wearables, such fitness trackers and smartwatches, gives it access to real-time activity metrics and physiological data. The mini-robot can offer dynamic feedback and individualized interventions by utilizing this continuous stream of data, which can encourage continued participation in health-promoting behaviors and facilitate proactive control of cardiovascular risk factors.

The first few columns of the excel sheet:
 
age = age of the patient
gender = 1 : male, 0 : female
cp = chest pain level (1-4)
chol = serum cholestoral in mg/dl
fbs = fasting blood sugar (1 = true, 0 = false)
restecg = resting ecg results in values 0,1,2
exang = exercise induced angina (1 = yes, 0 = no)
slope = slope of ST segment (0,1,2)
ca = number of major vessels (0-3)
target = 0 : no chances of heart failure, 1 : chances of heart failure

Machine learning model used: Logistic Regression. 
Logistic regression calculates the probability of an event happening based on a given set of independent factors. This sort of statistical model (otherwise known as the logit model) is commonly employed in classification and predictive analytics. Given that the outcome is a probability, the dependent variable is limited to 0 and 1.
In this scenario, when the user provides his health condition values and levels which are the independent variable, logistic regression model predicts the dependent variable which is the heart failure resulting in 0’s or 1’s
The training and testing size was split into 80% and 20% respectively.

Working of the model

Once the program is run the user is prompted to enter the following details:

age1 = float(input("Enter your age : "))
gender1 = float(input("Enter your gender (1 = male, 0 = female): "))
cp1 = float(input("Enter chest pain level (1-4): "))
chol1 = float(input("Enter the serum cholestoral in mg/dl: "))
fbs1 = float(input("Enter fasting blood sugar (1 = true, 0 = false): "))
restecg1 = float(input("Enter the resting ecg results in values 0,1,2: "))
exang1 = float(input("Enter exercise induced angina (1 = yes, 0 = no): "))
slope1 = float(input("Enter the  slope of ST segment (0,1,2): "))
ca1 = float(input("Enter the number of major vessels (0-3): "))

(To check the accuracy of the model, I had removed a few patients’ data from the database before feeding it to the model so that it can be used to cross check the accuracy)

48	1	0	256	1	0	1	2	2   -   0
54	0	1	288	1	0	1	2	1   -   1
 

Conclusion

In summary, the incorporation of machine learning methodologies into a mobile robotic platform presents significant potential for transforming the provision of cardiovascular healthcare services. The heart failure prediction mini-robot is a key step towards proactive and personalized healthcare management since it provides people with timely insights and makes it easier for patients and healthcare providers to collaborate.

The future of the heart failure prediction mini-robot is defined by its ability to transform healthcare delivery, enhance access to preventive treatments, and empower people to take control of their cardiovascular health far earlier.

