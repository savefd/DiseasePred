# Disease Type Prediction by Symptoms

About this Task
- Data from: https://www.kaggle.com/itachi9604/disease-symptom-description-dataset
- My Kaggle nb is here -> https://www.kaggle.com/napongleelasithorn/disease-prediction-random-forest

Reshaping then Predicting diseases with RandomForestClassifier



I have 100% accuracy in this work, The Dataset is too clean and too Fake. (1st Place)😥 

Briefly process
- transform df
- Train/Test with Random Forest
 
Before (Just an Example)

|index|Disease|Symptom_1|Symptom_2|...|Symptom_17|
|---|---|---|---|---|---|
|0|Bacterial Infection| Nausea | Fever |...| NaN|
|1|Conjunctivitis| Itching | NaN | ...| Nan|
|2|...| ... | ...|...|...|

After (Ex.)

|index| Disease | Fever | Nausea | Itching |...| Diarrhea |
|---|---|---|---|---|---|---|
|0|Bacterial Infection|1 |1| 0| ...| 0|
|1|Conjunctivitis|0|0|1|...|0|
|2|...|...|...|...|...|...|
