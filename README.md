# What Has Been Completed Thus Far

# Next Steps
The purpose of this readme is to address any future design decisions or feature that we believe should be worked on in the next iteration of this project.

## Connection between watches and web app
A pivotal feature that will prove to be a strong asset to the project is implementing a method in which both smartwatches can automatically send the retrieved PPG data directly to the web application. Since the ML models have been completed, there is already functionality to read this data and determine a patient's diagnosis. 

### Ideal Solution:
TODO

### Repositories that may be helpful to analyze when formulating a solution to this issue:
- RescueHeroes/SensorExample
- RescueHeroes/ProjectLimbRescue

## *Summer 2021 Iteration*

Technical Team:
-  Mengdi Fan
-  Tai-Yu Pan
-  Rithvich Ramesh
-  Browy Li

## Repositories
### LimbRescueML
- LimbRescueML implements four classification algorithms, Support Vector Machine(SVM), Multilayer Perceptron(MLP), Random Forest(RF), and Naive Bayes(NB) to predict lymphedema. Users can compare four classification algorithms, train and evaluate models, and predict based on saved models.
- LimbRescueML provides dataset generation(`generate_dataset.py`), model training(`train_net.py`), model evaluation(FIXME), wave prediction(FIXME), and package installation(FIXME) pipelines.
- Navigate to the README within the LimbRescueML repository for any clarifications regarding setup/installation.

### LimbRescueWeb
- Develop a user friendly web application that allows patients/doctors to create an account, upload data, and identify a diagnois. 
- The web application will facilitate a home based monitoring protocol for patients to monitor and track their lymphedema recordings.
- The web application has been built using the Django framework and is styled using CSS, Bootstrap, and Javascript. 
- The webapplication also features a chat bot within the 'Help' page in order for patients to recieve automated assistance to answer any questions regarding the project.
- Navigate to the README within the LimbRescueWeb repository for any clarifications regarding setup/installation.

### LimbRescueWorkflow
- Our team has drafted this wonderful repo that you are currently accessing. :)
- The purpose of this workflow is to keep a running list of features and design decisions that have been implemented over the various iterations of this project.
- Each team should take it upon themselves to update this README as they add new features to the project in order to maintain an organized workflow for future teams and sponsors to access. 
- Keeping this README organized will ensure a more productive and less confusing development cycle of the project for each team's iteration.

## *Spring 2021 Iteration*

Technical Team:
-  Michael Montelone
-  Nathan Newcomer
-  Daniel Simpkins
-  Cole Swartz

## Repositories
### ProjectLimbRescue
- The purpose of the code within this repo is to gather data on the water content of a limb using non-invasive wearable devices to assist in an early-warning system for patients at risk of lymphedema.
- The code within this repo also enables the use of an Android Mobile app, for details on installation/set-up, navigate to the README within the ProjectLimbRescue repository and direct your attention to the 'Installation' section.

### PPGGraph
- This repository contains a messy python script that will display a graph of telemetry captured from the "Telemetry" wearOS app.
- For usage of this code please navigate to the 'Usage' section of the PPGGraph README.

### SensorExample
- This application is an example of how to enumerate and poll data from the raw sensors on WearOS. This example requires at least WearOS 2.0 and a Fossil Gen 5 smartwatch. Emulators may not be fully supported. When run, the debug console will be populated with the readings.

