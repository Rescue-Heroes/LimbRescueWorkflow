# What Has Been Completed Thus Far

## Next Steps
The purpose of this README is to address any future design decisions or features that we believe should be worked on in the next iteration of this project.

### Connection between watches and web app
A pivotal feature that will prove to be a strong asset to the project is implementing a method in which both smartwatches can automatically send the retrieved PPG data directly to the web application. Since the ML models have been completed, there is already functionality to read this data and determine a patient's diagnosis. 

### Ideal Solution:
An ideal solution that has been formulated is to pair one of the watches to the other watch and send the longitudinal waveform data from both arms via one watch. Our sponsors have a plethora of relevant articles relevant to sending data via the watches and the spring 2021 group has code within the repositories listed below that will assist with the functionality of this feature.

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
### [LimbRescueML](https://github.com/Rescue-Heroes/LimbRescueML)
- LimbRescueML implements four classification algorithms, Support Vector Machine(SVM), Multilayer Perceptron(MLP), Random Forest(RF), and Naive Bayes(NB) to predict lymphedema. Users can compare four classification algorithms, train and evaluate models, and predict based on saved models.
- LimbRescueML provides dataset generation([Generating Dataset](https://github.com/Rescue-Heroes/LimbRescueML#getting-started)), model training([Training](https://github.com/Rescue-Heroes/LimbRescueML#training)), model evaluation([Evaluation](https://github.com/Rescue-Heroes/LimbRescueML/blob/main/docs/evaluation.md)), wave prediction([Prediction](https://github.com/Rescue-Heroes/LimbRescueML/blob/main/docs/prediction.md) for more information.), and package installation pipelines.

- Navigate [LimbRescueML](https://github.com/Rescue-Heroes/LimbRescueML) for any clarifications regarding setup/installation.

### [LimbRescueWeb](https://github.com/Rescue-Heroes/LimbRescueWeb)
- Develop a user-friendly web application that allows patients/doctors to create an account, upload data, and identify a diagnosis. 
- The web application will facilitate a home-based monitoring protocol for patients to monitor and track their lymphedema recordings.
- The web application has been built using the Django framework and is styled using CSS, Bootstrap, and Javascript. 
- The web application also features a chatbot within the 'Help' page for patients to receive automated assistance to answer any questions regarding the project.
- Navigate to [LimbRescueWeb](https://github.com/Rescue-Heroes/LimbRescueWeb) for any clarifications regarding setup/installation.

### [LimbRescueWorkflow](https://github.com/Rescue-Heroes/LimbRescueWorkflow)
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
### [ProjectLimbRescue](https://github.com/Rescue-Heroes/ProjectLimbRescue)
- The purpose of the code within this repo is to gather data on the water content of a limb using non-invasive wearable devices to assist in an early-warning system for patients at risk of lymphedema.
- The code within this repo also enables the use of an Android Mobile app, for details on installation/set-up, navigate to the README within the ProjectLimbRescue repository and direct your attention to the 'Installation' section.

### [PPGGraph](https://github.com/Rescue-Heroes/PPGGraph)
- This repository contains a messy python script that will display a graph of telemetry captured from the "Telemetry" wearOS app.
- For usage of this code please navigate to the 'Usage' section of the PPGGraph README.

### [SensorExample](https://github.com/Rescue-Heroes/SensorExample)
- This application is an example of how to enumerate and poll data from the raw sensors on WearOS. This example requires at least WearOS 2.0 and a Fossil Gen 5 smartwatch. Emulators may not be fully supported. When run, the debug console will be populated with the readings.

