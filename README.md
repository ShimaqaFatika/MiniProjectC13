### Dataset
https://www.kaggle.com/datasets/sagarbapodara/parkinson-csv

### Abstract
Parkinson's disease prediction

Parkinson’s is considered one of the deadliest and progressive nervous system diseases that affect movement. It is the second most common neurological disorder that causes disability, reduces the life span, reduces the quality of life, and still has no cure. Symptoms begin with a hardly noticeable tremor in body parts. The disorder results in stiffness and slowing down of movements. It’s a debilitating neurodegenerative disease and cannot be diagnosed through blood tests. Parkinson’s disease mostly affects the people above 60 and is one of the common diseases among war veterans.
A doctor trained in nervous system conditions (neurologist) will diagnose Parkinson's disease based on the patient!s medical history, a review of the signs and symptoms, and a neurological and physical examination. Early detections can help doctors provide better diagnosis to patients and can also reduce Parkinson!s upto certain extent on early detection.
An ensemble model(XGBoost) is used to diagnose Parkinson's Disease with maximum accuracy using a dataset that consists of data from voice recordings of Parkinson's patients and unaffected subjects. These data of varying frequencies can be fed to the model and the results can be displayed.

### Limitations of Existing System

The existing systems for Parkinson's disease prediction have the following drawbacks.
1. Dependency on Subjective Assessments:
Many current prediction systems heavily rely on subjective assessments conducted by medical professionals. These assessments, while valuable, can introduce variability due to differences in interpretation and experience among different practitioners. This subjectivity may lead to inconsistencies in diagnosis and hinder the accuracy of predictions.
2. Lack of Real-time Monitoring:
A significant drawback of the current systems is their inability to provide real-time monitoring of Parkinson's disease symptoms. Patients' conditions can fluctuate throughout the day, and relying solely on intermittent assessments may fail to capture the full extent of their symptoms. This limitation reduces the effectiveness of these systems in providing a comprehensive view of the disease progression.
3. Insufficient Consideration of Non-Motor Symptoms:
Parkinson's disease is not solely characterized by motor symptoms; it also presents an array of non-motor symptoms such as cognitive impairments, sleep disturbances, and mood disorders. Many existing prediction systems predominantly focus on motor symptoms, overlooking these non-motor manifestations that significantly impact patients' quality of life.
4. Limited Generalizability and Accuracy:
Several prediction models exhibit limitations in terms of generalizability and accuracy. These models are often developed based on specific datasets that might not fully represent the diversity of the Parkinson's disease population. Consequently, their predictive power might diminish when applied to broader patient cohorts, compromising their reliability.

### PROPOSED SYSTEM
XGBoost is a machine learning algorithm that has gained significant popularity in various data science and machine learning competitions due to its robustness and high performance. It falls under the category of ensemble learning, which combines the predictions of multiple models to improve overall performance.

### Algorithm
XGBoost is an optimized distributed gradient boosting library designed for efficient and scalable training of machine learning models. It is an ensemble learning method that combines the predictions of multiple weak models to produce a stronger prediction. XGBoost stands for “Extreme Gradient Boosting” and it has become one of the most popular and widely used machine learning algorithms due to its ability to handle large datasets and its ability to achieve state-of-the-art performance in many machine learning tasks such as classification and regression.
In this algorithm, decision trees are created in sequential form. Weights play an important role in XGBoost. Weights are assigned to all the independent variables which are then fed into the decision tree which predicts results. The weight of variables predicted wrong by the tree is increased and these variables are then fed to the second decision tree. These individual classifiers/predictors then ensemble to give a strong and more precise model.

### Future Scope

1. Validation and External Testing: To ensure the model's reliability and generalizability, it should undergo rigorous validation and external testing using diverse and larger datasets from multiple sources and medical centers.
2. Integration into Clinical Practice: The model's integration into clinical practice requires collaboration with healthcare institutions and regulatory approval. Implementing the model as a decision support tool can assist neurologists in their diagnostic process and treatment planning.
3. Ensemble Models and Deep Learning: Exploring the use of ensemble models and deep learning architectures can potentially enhance the model's performance and increase its ability to handle complex and high-dimensional data.
4. Mobile Applications and Telemedicine: Developing user-friendly mobile applications for Parkinson's disease prediction can extend its accessibility to a broader population. Such applications could also facilitate telemedicine consultations for patients living in remote areas.

