## Risk Factors in Coronary Artery Disease

---

In this project, this study attempted to predict the possibilities of a given patient to have heart disease. Logistic regression and support vector machines were applied on the ‘heart.csv’ data set, which contains data on 303 patients consisting of 13 risk factors and a zero-one valued variable that indicates if the patient has heart disease.  

---

<p align="center">
  <img width="450" height="300" src="https://github.com/ankur715/coronary_artery_disease/blob/master/dc-Cover-gvrs121ec4vt8q8dgabh2k2d54-20181112170506.Medi.jpeg"> 
</p>
---

Conclusion:

For Logistic Regression, the best model found was Model 6 (AHD ~ Sex + ChestPain + RestBP + ExAng + Oldpeak + Slope + Ca + Thal). The train data set gave an accuracy of 85.23 and an AIC of 184.87, and the test data set gave an accuracy of 90 and an AUC of 0.926). For SVM, the best model was SVM 4 (AHD ~ Age + Sex + ChestPain +  RestBP + MaxHR + Oldpeak + Slope + Ca + Thal + Chol, data = train, kernel = "linear"). It provided the lowest number of support vectors of 98 and the second highest accuracy of 85.23. For the test data set, SVM 4 provided the better accuracy of 93.33, and therefore it was the final best model. We would use this model to study and make predictions for patients or hospitals if we were to get more observations. 
