# kaggle_knowledge-tracing_compitition


**Problem to be addressed:**

In this compitition, it is found that when a student is taking exam and attempting questions then will the next question be correctly attempted by a student or not. It is a two-class classification problem.


**Dataset:**

The data used for this compitition is available in this link https://www.kaggle.com/c/riiid-test-answer-prediction/data 
This data is about TOEIC (Test Of English for International Communication) that provides student previous performance in exam at question level. It is a big data that consists of more than 100 million records.


**Pre-processing:**

In this step feature engineering is performed. The new features are derived from the already available simple features to infer some implicit information from the data. To perform this step, mathematical and statistical analysis is conducted here.


**Self-Attention Knowledge Tracing Model:**

This model was built using feature of scores in questions of different modules of TOEIC.


**Boosting Machine Learning Algorithm-based Model:**

This model was built on the basis of engineered features obtained as output of the pre-processing step.


**Training and Testing:**

Both models were first trained and then tested to predict correctness of the future question.


**Ensemble Modelling:**

The predictive output of both models were first assigned some weights and then weighted predictions added up to get final prediction.

