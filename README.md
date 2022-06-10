# CSE523-Machine-Learning-2022-Discover-Decipher
  CO2 Emissions Prediction using Machine Learning Algorithms
# Introduction
     The project and the presentation is showcased on the basis of the information available on kaggle.The usage of different techniques for the prediction of Co2          emissions  considering 11 features and respective vehicles(different models) was taken into consideration while implementation of the project. Regression  and          classification machine learning algorithms were widely used in the project.
 
# Methods
    1.  Machine Learning 
    2.  Data Cleaning
    3.  Data analysis
# Technologies 
    1. Python
    2. Pandas, NumPy
    3. Scikit-learn
    3. Matplotlib
    4. Seaborn


# Implementation of Machine Learning Algorithms
 
# Regression analysis
 
    1. Linear Regression
    2. Polynomial Regression
    3. Decision tree regression 
    4. Random forest regression
 
# Classification analysis
 
    1. KNN classification
    2. Decision Tree  classification
    3. Random Forest classification
 
# Metrics/ Accuracy scores for Regression based algorithms
 
     1. Root Mean Square Error

     RMSE is used as one of factors to check on the quality of predictions by calculating the residuals which is a difference between the predicted and actual value    for each data point and thus by computing the mean of residuals with the square root measures the RMSE.

     2. Mean Absolute Error

     The most used metric for model evaluation specifically for regression models  , considering the test set there is a mean of absolute error for individual prediction errors on overall instances in a test set , prediction error depicts the difference between the actual and predicted value.

     3. R2 Score

     The R2 is considered as a coefficient of determination, It measures the amount of variance in predictions.
 
# Metrics for Classification based algorithms
      1. Confusion matrix

      The table/matrix depicts and visualizes the performance of the classification algorithm , the values described in matrix TP , TN , FP , FN play a vital role while visualizing the results.
      TP  : True positive (defines number of positives)
      TN : True Negative (defines number of negatives)
      FP  : False Positive(defines number of actual negatives classified as positives)
      FN : False Negative(defines number of actual positives classified as negatives)
      The accuracy calculated on the basis of these variables in the matrix  is (TP + TN) / (TP + TN + FP + FN)

 
2. AUC-ROC (Area under the curve and Receiver Operating characteristics )

         Visualizes and defines the quality of the performance for classification problems.
         ROC represents the probability curve and AUC defines the measure at which there is a separability.
         few measures taken into considertion are , 
      
         1. TPR(True Positive Rate) : (TP)/(TP + FN)
         2. FPR (False Postive Rate) : (FP)/(FP +TN)

# Results

         Regression : Accuracy achieved - 0.9961 for Decision Tree Regression, with 5 feature variable input the model predicts real value of CO2 Emission in g/km. 
         Classification : Accuracy achieved 0.98 for random forest classifier, input the feature variables and output will be the class label in which the vehicle belongs.
         Important features :Engine Size(L),Fuel Type,Fuel Consumption City (L/100 km), Fuel Consumption Comb (L/100 km), Fuel Consumption Comb (mpg).
  
# References
          1. F. Perera, “Pollution from fossil-fuel combustion is the leading environmental threat to Global Pediatric Health and Equity: Solutions Exist,” International journal of environmental research and public health, 23-Dec-2017. [Online]. Available: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5800116/ . [Accessed: 14-Apr-2022].
          
          2. “Faster adoption and manufacturing of (Hybrid &) Electric ...” [Online]. Available: https://heavyindustries.gov.in/UserView/index?mid=2418. [Accessed: 04-Mar-2022]. 
          
          3. N. Ma, W. Y. Shum, T. Han, and F. Lai, “Can machine learning be applied to carbon emissions analysis: An application to the CO2 emissions analysis using gaussian process regression,” Frontiers, 01-Jan-1AD. [Online]. Available: https://www.frontiersin.org/articles/10.3389/fenrg.2021.756311/full. [Accessed:05 -Apr-2022].
          
          4. D. Podder, “CO2 emission by vehicles,” Kaggle, 05-Aug-2020. [Online]. Available: https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles. [Accessed: 22-Apr-2022]. 
          
          5.  J Mater Environ Sci.com, Journal of Materials and Environmental Science. [Online]. Available: https://www.jmaterenvironsci.com/Journal/vol11-2.html. [Accessed: 22-Apr-2022].
          
          6. Iea, “Tracking Transport 2020 – analysis,” IEA, 01-Jun-2020. [Online]. Available: https://www.iea.org/reports/tracking-transport-2020. [Accessed: 18-Mar-2022]. 
          
          7. H. Ritchie and M. Roser, “Emissions by sector,” Our World in Data, 11-May-2020. [Online]. Available: https://ourworldindata.org/emissions-by-sector#:~:text=The%20global%20breakdown%20for%20CO,transport%2C%20and%20manufacturing%20and%20construction. [Accessed: 15-Mar-2022]. 
          
          8. “Fuel consumption ratings,” Open Government Portal. [Online]. Available: https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6. [Accessed: 27-Mar-2022]. 
          
          9. R. Lee, “Are automotive suppliers ready for the move to electrification?,” LinkedIn, 06-Apr-2021. [Online]. Available: https://www.linkedin.com/pulse/automotive-suppliers-ready-move-electrification-ron-lee. [Accessed: 16-Mar-2022]. 

          10. “Can machine learning be applied to carbon emissions ...” [Online]. Available: https://www.researchgate.net/publication/354838594_Can_Machine_Learning_be_Applied_to_Carbon_Emissions_Analysis_An_Application_to_the_CO2_Emissions_Analysis_Using_Gaussian_Process_Regression/. [Accessed: 02-Mar-2022]. 

          11. “Structural breaks in carbon emissions: A machine ... - imf.org.” [Online]. Available: https://www.imf.org/-/media/Files/Publications/WP/2022/English/wpiea2022009-print-pdf.ashx. [Accessed: 10-Mar-2022]. 

          12. “Fuel consumption ratings,” Open Government Portal. [Online]. Available: https://open.canada.ca/data/en/dataset/98f1a129-f628-4ce4-b24d-6f16bf24dd64#wb-auto-6. [Accessed: 10-Mar-2022]. 

          13.Eeer.org. 2022. [online] Available at: <https://www.eeer.org/upload/eer-1489554553.pdf>  [Accessed 21 April 2022].

          14.  Iopscience.iop.org. 2022. ShieldSquare Captcha. [online] Available at: <https://iopscience.iop.org/article/10.1088/1757-899X/114/1/012148/pdf > [Accessed 21 April 2022].







