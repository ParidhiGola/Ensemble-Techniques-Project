# Ensemble-Techniques-Project
The main aim of the data is to discriminate healthy people from those with PD, according to "status" column which is set to 0 for healthy and 1 for PD.

Parkinson’s Disease (PD) is a degenerative neurological disorder marked by decreased dopamine levels in the brain.
It manifests itself through a deterioration of movement, including the presence of tremors and stiffness. 
There is commonly a marked effect on speech, including dysarthria (difficulty articulating sounds), hypophonia (lowered volume), and monotone (reduced pitch range). 
Additionally, cognitive impairments and changes in mood can occur, and risk of dementia is increased.

Traditional diagnosis of Parkinson’s Disease involves a clinician taking a neurological history of the patient and observing motor skills in various situations. Since there is no definitive laboratory test to diagnose PD, diagnosis is often difficult, particularly in the early stages when motor effects are not yet severe. Monitoring progression of the disease over time requires repeated clinic visits by the patient. An effective screening process, particularly one that doesn’t require a clinic visit, would be beneficial. Since PD patients exhibit characteristic vocal features, voice recordings are a useful and non-invasive tool for diagnosis. If machine learning algorithms could be applied to a voice recording dataset to accurately diagnosis PD, this would be an effective screening step prior to an appointment with a clinician.

The data & attributes information for this project is available at -

https://archive.ics.uci.edu/ml/machine-learning-databases/parkinsons/

The data consists of those diagnosed with Parkinson Disease and those who do not.

Steps to be followed:

Load the data set

It is always a good practice to eye-ball raw data to get a feel of the data in terms of number of structure of the file, number of attributes, types of attributes and a general idea of likely challenges in the data set. (2.5 points)

Using uni-variate & bi-variate analysis to check the individual attributes for their basic statistic such as central values, spread, tails etc.
 What are your observations? (15 points)

Split the data set into training and test set in the ratio of 70:30 (Training:Test)

Create the model using “entropy” method of reducing the entropy and fit it to training data. (5 points)

Test the model on test data and what is the accuracy achieved. Capture the predicted values and do a cross-tab. (7.5 points)

Use regularization parameters of max_depth, min_sample_leaf to recreate the model. What is the impact on the model accuracy? How does regularization help? (20 points) 
 8. Next implement the decision tree using Random Forest. What is the optimal number of trees that gives the best result? (10 points)

