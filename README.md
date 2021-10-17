A] PREPROCESSING

        1]we can determine that the mean average age in titanic ship that aboarded was 29 while max was 80

        2]Number of Siblings/Spouses Aboard was max of 8 people

        3] while maximum Fare was 512 dollors

        4] while parent child boared in titanic was range from with min(1) and max(8)


B] VISUALISATION

        1]No of people lossed there life were more than 500+ out of which 'male' was the most as of we can say that female and            children were resuced 1st -while only 300+ survived in the accident

        2]As people of 1st class has survived more in the incident as compare to that of 2nd and 3rd class people as 1st class have given first priority in boarding the rescue boat

        3]We can conclude that from data ticket price ranged from 0-75 dollar while maximum ticket sold was for 512 dollar,there         were many ticket sold in between 75-300 dollar this may be extra charges of last minute booking

        4] There were 5 such people having 8 sibling/spouses onboared with them,while 606 were without any siblings

        5]There were more than 600+couple in the ship while couple having 1 child with them were 118 and so on
C] BUILDING MODEL

        By using try and error
          -we can conclude that the accuarcy of the model by using [logistic Regression] the model give the maximum accuracy=85%
          -while that of using [svm]=82%
          -And of [knn]=72%

RESULT

        A] Before all the hyperparameter Tuning for LOGISTIC , KNN, SVM

            ACCURACY[KNN]==0.7219730941704036
            ACCURACY[LOGISTIC]==0.8430493273542601
            ACCURACY[SVC]==0.6502242152466368
            
        B] After all the hyperparameter Tuning for LOGISTIC , KNN, SVM

            ACCURACY[KNN]==0.726457399103139
            ACCURACY[LOGISTIC]==0.852017937219731
            ACCURACY[SVC]=0.8295964125560538
            
        c] ANN Model

            ACCURACY== 0.80

D] Hyperparameter Tuning of ann

            ACCURACY== 0.81
