# DataScienceProject on Roman data about pottery
Repository Structure
	• RomanDataScienceProject.ipynb was the first release
	- **RomanProjectReview.ipynb** is the latest version reviewed 
Motivation
This project aims to predict the shape of archaeological pottery fragments based on measurable attributes such as:
	• exterior_diam
	• inside_diam
	• chronology
	• rim_h
	• rim_w
	• site
The motivation is to assist archaeologists and researchers in classifying pottery shapes efficiently using machine learning, reducing manual effort and improving accuracy.

Libraries Used
The project uses the following Python libraries:
	• pandas: For data manipulation and preprocessing.
	• scikit-learn providing machine learning tools:
		○ train_test_split: To split data into training and testing sets.
		○ DecisionTreeClassifier: For building the classification model.
		○ accuracy_score, classification_report: For model evaluation.
Additional libraries for visualization :
	• matplotlib: For plotting decision tree and thresholds.
Main script for loading data, preprocessing, training a Decision Tree model, evaluating performance, and plot .
	• README.md
Documentation of the project, including motivation, libraries, results, and acknowledgments.
	• dataDressel.csv (example dataset)
Data are from https://projectmercury.eu/datasets/<img width="282" height="19" alt="image" src="https://github.com/user-attachments/assets/556ac2bb-d5b9-49b8-8e6d-cb7d05ab1a19" />
Contains pottery fragment data with columns: exterior_diam, inside_diam, chronology, rim_h, rim_w, site, and shape.

Summary of Results
	• Model Used: Decision Tree 
	• Accuracy: ~85% on the test set (varies by dataset)
	• Insights: 
		○ exterior_diam and inside_diam were the most influential features.
		○ Sites and chronology contributed to secondary splits.
	• Visualization: 
		○ Tree structure shows clear thresholds for diameter-based splits.
		○ Decision boundaries highlight how shapes cluster in feature space.

