# KIM-Frost
This Program is KIM-Frost(RF)!
*** Please check dir's name!! ***

- original training set
./ML_input

- DC(Divied Classes)-Oversampling (New training set)
./SMOTE
./ADASYN
./SMOTE_BL
./SVMSMOTE

- validation set (Model fitting)
./ML_test

- test set1 (other site)
./ML_vali

- test set2 (real test)
./ML_kma/ML_kma        (KIM-Regional data)
./ML_kma/re_kma_data   (frost observation data)

- code info. -

- DC-Oversampling
frost-adasyn.ipynb
frost-Bline.ipynb
frost-smote.ipynb
frost-svmsmote.ipynb

- Random forest code 
frost_rf_1h.ipynb   (1 hour score)
frost_rf_day.ipynb   (half day score) 
frost_rf_day24.ipynb   (1 day score) 
frost_rf_kma.ipynb    (test -> AM KST score)
