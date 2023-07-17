# Emotion-recognition-eeg-
#Internship at NIT-T 


The codes for the book with OneAPI and , google colab notebooks I created for my internship is all found here.

1) Deap01_classification :
  
 In this I taken single persion's data,labels and extract the features( time domain ,frequency domain ,
  time-frequency domain) ,then classify emotions using simple codes of  Logistic regression , SVM ,KNN, Random forest .

2) Feature_extraction :

 By changing the file_path in the load dataset part , I taken all the 32 subject's datasets one after another and save each subject's extracted features as a .mat file in my drive
 (The functions used for extract a single person's dataset features in the above code - deap01_classification , where taken )

3) Combain :

 All the 32 feature extracted datasets , labels are combained together for the further classification and save as a seperate file in my drive .

4) Model_train_test :

  The final classification of features  with respected to the  4 target labels done by using  simple Ml models .
  ( by applying k-fold cv ,the accuracy get increased ) 

  
