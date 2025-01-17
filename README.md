<p align="center">
  <h1>Doctor In A Browser</h1>
</p>


<p align="center">
  <img width="400" height="400" src="https://github.com/MLXTREME/Doctor-In-A-Browser/blob/main/assets/Smart-Doc-IN-A-Browser.gif">
</p>
<br/>
<p align="center">

 <img src="https://forthebadge.com/images/badges/built-with-love.svg">  <img src="https://forthebadge.com/images/badges/made-with-python.svg">  <img src="https://forthebadge.com/images/badges/made-with-javascript.svg">  <img src="https://forthebadge.com/images/badges/open-source.svg">
<a href="CONTRIBUTING.md"><img alt="Contributions Welcome" src="https://img.shields.io/badge/contributions-welcome-brightgreen?style=for-the-badge&labelColor=black&logo=github"></a>
<a href="LICENSE"><img alt="GitHub License Apache-2.0" src="https://img.shields.io/github/license/vysakh-m/Virtual-Doc?style=for-the-badge&labelColor=black&logo=github"></a>

</p>
<br/>

# What is Doctor In A Browser?🤔
Doctor In A Browser, as the name suggests, is like a doctor in a browser, basically in the form of a Web Application. What does this doctor do, I hear you asked? It is a diagonistic tool. As we know, diagnosis is the first step in any treatment. So, quick and accurate diagnosis can be life saving. 

So, how does it diagnose diseases? Well, it harnesses the power of Machine Learning. Machine Learning, as we know, can be used to learn complex features from data, which can be game changing in the field of disease diagnosis. 

It also produces a report, with a certificate. This report and certificate are mailed to the user for further usability and treatment. 
 
# USP of our project🌈:
 1. **Machine Learning** based Disease detection for **COVID-19,HIV,Alzheimers,Parkinson**.
 2. **Chatbot* based on diet and recommended physical activities for a pregnant person.
 3. we provide an **analytics page**, **which shows why the predicted results are in that way**.Analysis mail will be consist of Grad-cam and LIME results with different kind of charts.
 4. **Auto mail** after prediction is done with as govt. certified cirtificate based on the disease detection result.
 5. **Personalized Dashboard** for showing previously prediction results. 
 6. Providing **doctor’s appointment booking online.**

 
 # User Interface⚡:
<pre>

<img src="https://i.imgur.com/YJVLlDd.png" width="700"> <img src="https://i.imgur.com/OvyI1eQ.png" width="700">  <img src="https://i.imgur.com/I3HZRb6.png" width="700">  <img src="https://i.imgur.com/TgdR7fx.png" width="700"> <img src="https://i.imgur.com/pJJoKWr.png" width="700"> <img src="https://i.imgur.com/b3aBShI.png" width="700"> <img src="https://i.imgur.com/sz6NSVq.png" width="700">  <img src="https://i.imgur.com/ed8pouA.png" width="700"> <img src="https://i.imgur.com/zjTa9lx.png" width="700"> <img src="https://i.imgur.com/ZA7sZHk.png" width="700">
 
 </pre>

 
 

# Machine Learning Models Supported in Doctor In A Browser👨‍💻
1. **Maternal Health Chatbot** : Pregnancy is an uncertain time for the mothers carrying the foetus. A lot of questions arise in the minds of the to be mothers, especially for the first baby, which they are maybe afraid or too shy of judgement to ask others. Here is where the Maternal Health chatbot comes in. **It is a Frequently Asked Questions based Chatbot on subjects such as the diet to be consumed and the physical activity to go through during the phase of Pregnancy**. It will help to be mothers clear their doubts and a smoother 9 months of carrying the baby.

2. **COVID-19 Detection From CT Scan** : We have been in a pandemic situation for more than a year now. Even today we don't have a system of detecting whether a certain person is infected by COVID-19 with near perfect accuracy. We have an average error of about 0% to 30% , which can be catastrophic, especially for the false negative cases. So, we have made a **COVID-19 detection model which uses the Computer Tomography Scan of the lungs to detect the presence of the deadly virus**. **Our model gives a testing accuracy of 88% , which is better than the existing methods. **

3. **Predict HIV Progression(HIV model)**:
The HIV epidemic not only affects the health of individuals, it also impacts households, communities, and the development and economic growth of nations. Many of the countries hardest hit by HIV also suffer from other infectious diseases, food insecurity, and other serious problems. Here is where the ML model comes in. This model predicts the likelihood that an HIV patient's infection.It takes ,

- Protease nucleotide sequence 

- Reverse Transcriptase nucleotide sequence (if available)

- viral load at the beginning of therapy (log-10 units)

- CD4 count at the beginning of therapy
 
PS: not interested because of some time constraints.

4. **Fetal Health Classification**:
The success of fetal life determines not only the health of the newborn, but also has a major impact on adult health and disease risk. Good perinatal health is therefore important to individuals, to society and to future generations. **Now to classify the health of a fetus is Normal, Suspect or Pathological is what our ML model does with ~95% accurecy**.Classify fetal health in order to prevent child and maternal mortality.

5. **Parkinson Disease Detection:**
Parkinson’s disease is the second most common age-related neurodegenerative disorder after Alzheimer’s disease. An estimated seven to 10 million people worldwide have Parkinson’s disease. To solve this problem we have created a ML model which can detect the Parkinson Disease. It is too easy to detect by our app, go to the Parkinson Disease section upload a image with drawing spirals and waves by the patient, and hit predict. it will show, you have that disease or not and on top of it it will give an analytics that why the predicted result is that way. 

PS: not interested because of some time constraints.

5. **Alzheimers Disease Classification: **
**Alzheimer's is the sixth leading cause of death in the United States**. On average, a person with Alzheimer's lives four to eight years after diagnosis, but can live as long as 20 years, depending on other factors. Alzheimer's has no current cure, but treatments for symptoms are available and research continues.**Our model detects 5 stages of Alzheimer's Disease.These stages are,  EMCI,LMCI, MCI, AD, CN.**


# Technology Stack⚛
 We used quite a lot of languages and frameworks in this project. 

 Firstly we will have a look at the FrontEnd part of the Web Application. We used HTML, CSS and JavaScript for this part of the project, to design the look and feel of the web application.


 <p align="center">
<img src="assets/img/htmlcssjs.png" width="300">
 </p>
 Now comes the Machine Learning models. We used the popular Python based framework Keras, which is built on top of the framework Tensorflow. 

<p align="center">
<img src="assets/img/tfk.png" width="500">
  </p>
 For the BackEnd, which basically integrates all the different FrontEnd files and the files containing the Machine Learning models, to get the predictions out of the models, we have used the Python based microframework Flask.
 

 <p align="center">
<img src="assets/img/flask.png" width="400"> <img src="https://www.margo-group.com/wp-content/uploads/2018/05/dialogflow1.jpg" width="470">
  </p>
  
  
# Usability of our project✅
 
 As said earlier, our project is aimed at improved diagnosis of diseases for the models we have prepared. The least we, as developers, in these testing times can do is help out the health professionals working out their, in the frontline for us day in and day out. With our certificates, when patients visit their doctor, they can skip the diagnosis step and directly move into treating patients, which in case of medical emergencies can save lives. This was for the COVID-19 detection part.
 
 The Maternal Health Chatbot will prove to be very useful for to be mothers, who might have a lot of simple questions about the diet and nutrition plan they should be following. This will also save time as asking and getting replies from a chatbot is easier and time saving than consulting a doctor, who might be busy at the time. 
 


 # Regards from the team🚀
 Here is hoping you liked our project.
 
 Regards,
 
 <p align="center">
<img src="https://github.com/MLXTREME/Doctor-In-A-Browser/blob/main/assets/MLXTREME.gif" width="450">
  </p>
  
  
Team Members:
1. Farhan Hai Khan
2. Soumyadip Sarkar
3. Nirmalya Misra
4. Damik Dhar
5. Spandan Giri
6. Madhu Charan

 
