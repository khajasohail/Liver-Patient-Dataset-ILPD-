PROBLEM STATEMENT :

TASK1:-PREPARE A COMPLETE DATA ANALYSIS REPORT ON THE GIVEN DATA

TASK2:-CREATE A PREDICTIVE MODEL WITH IMPLEMENTATION OF DIFFERENT CLASSIFIER ON LIVER PATIENT DISEASES DATASET TO PREDICTIVE LIVER DISEASES

TASK3:-CREATE AN ANALYSIS TO SHOW WHAT BASIS YOU HAVE DESIGNED YOUR MODEL



AS PER THE GOVERNMENT DATA ABOUT LIVER PATIENT,WE TOOK 3 RANDOM PERSONS DATA AND GIVE TO THE MODEL.THE MODEL HAS PREDICTED EVERY 3 DATA CORRECTLY


CONCLUSION

IN CONCLUSION,MODELS HAVE SHOWN PROMISING RESULTS IN PREDICTING OUTCOMES FOR LIVER PATIENTS. BY LEVERAGING VARIOUS DATA POINTS SUCH PERSONAL INFORMATION,BLOOD TEST RESULTS, AND LIVER CONDITION STUDIES, THESE MODELS CAN HELP HEALTHCARE PROVIDERS IDENTIFY PATIENTS AT RISK OF LIVER DISEASES AND MAKE INFORMED DECISION REGARDING TREATMENT.
1.THE GIVEN DATA DOESN'T HAVE ANY COLUMN NAME AND THE FIRST ROW COMES IN COLUMN NAME SPACE THUS I MAKE COLUMN NAME COME DOWN AND RENAME THE COLUMN AS RESPECT TO DATA

2.THERE WERE 582 ROWS AND 11 COLUMNS IN 2 WERE AGE AND GENDER , 8 WERE ABOUT LIVER TEST RESULTS AND ONE IS RESULT (TARGET)

3.THE TARGET VALUES WERE [1,2] WHICH I CHANGED TO [0,1] FOR MORE EASIER TO DO

4.THERE WERE NULL VALUES WHICH I REPLACED WITH MEAN AND DUPLICATE ROWS WERE DROPPED.

5.THE GIVEN DATA WAS IMBALANCED , SO WE BALANCED IT WITH OVERSAMPLING

6.I PERFORMED 4 MODELS , RANDOM FOREST , DECISION TREE , SVM AND LOGISTIC REGRESSION . FROM THESE MODELS SVM GIVES HIGH ACCURACY OF 92%

7.THIS SVM IS UESD TO PREDICT A RANDOM DATA FROM GOVERNMENT WEBSITE FOR LIVER PATIENTS AND EVERY 3 PREDICTION WERE CORRECT

SUGGESTION

HAVING A HEALTHY DIET , DROPPING TOBACCO AND REDUCING ALCOHOL , MAINTAIN A HEALTHY BODY MASS , STAYING HYDRATED , MONITORING OUR OWN MEDICATIONS , GETTING PROPER VACCINATION ON THE RIGHT TIME , HAVING A HABIT OF TAKING REGULAR HEALTH CHECK UP , AND ALSO SEEKING HELP FOR THE PROFESSIONAL WILL HELP US TO HAVE A HEALTHY LIFE STYLE AND CONTROLLING TO NOT HAVE DISEASES LIKE LIVER DISEASES


RISK
SINCE ALL OF THE ATTRIBUTES ARE FROM MEDICAL DOMAIN , IT WAS DIFFICULT TO LEARN ABOUT THEM AND FIND THE INSIGHT . BUT LATER WE GOT FEMILIAR WITH THEM AND FOUND ALL INSIGHTS