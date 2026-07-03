###### 🏠 House Price Prediction using Linear Regression



A Machine Learning project that predicts house prices using Linear Regression based on features such as living area, number of bedrooms, and number of bathrooms. This project was completed as Task 01 during my Machine Learning Internship at SkillCraft Technology.



###### 📌 Project Overview



The objective of this project is to build a Linear Regression model that can estimate house prices from selected housing features. The project covers the complete machine learning workflow, including data preprocessing, model training, prediction, evaluation, visualization, and model saving.



###### 📂 Dataset



**Dataset:** King County House Sales Dataset (kc\_house\_data.csv)



**Features Used**

* sqft\_living
* bedrooms
* bathrooms

**Target**

* price



###### 🛠️ Technologies Used



* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Joblib



###### 📈 Project Workflow



1. Loaded the dataset
2. Selected the required features
3. Split the data into training and testing sets
4. Trained a Linear Regression model
5. Predicted house prices on the test set
6. Evaluated the model using performance metrics
7. Visualized the results
8. Saved the trained model for future use



###### 📊 Model Evaluation



The model was evaluated using:

* Mean Absolute Error (MAE)
* R² Score



These metrics help measure the prediction accuracy and overall model performance.



###### 📷 Visualizations



**House Price vs Square Footage**



**Actual vs Predicted House Prices**



###### 📁 Project Structure

SCT\_ML\_1/

│

├── dataset/

│   └── kc\_house\_data.csv

│

├── images/

│   ├── regression\_line.png

│   └── actual\_vs\_predicted.png

│    └── prediction\_scatter.png

│

├── model/

│   └── house\_price\_model.pkl

│

├── house\_price\_prediction.py

├── requirements.txt

├── README.md

├── LICENSE

└── .gitignore



###### ▶️ Installation



**Clone the repository:**



git clone https://github.com/your-username/House-Price-Prediction-Linear-Regression.git



**Move into the project directory:**



cd House-Price-Prediction-Linear-Regression



**Install the required libraries:**



pip install -r requirements.txt



**Run the project:**



python house\_price\_prediction.py



###### 📌 Future Improvements



* Use additional housing features for better prediction accuracy.
* Experiment with advanced regression algorithms.
* Build a web application for interactive price prediction.
* Perform feature engineering and hyperparameter tuning.





###### 👨‍💻 Author



AmruthaRaju



Machine Learning Intern at SkillCraft Technology



B.E. Artificial Intelligence and Data Science



###### ⭐ Acknowledgements



* SkillCraft Technology
* Scikit-learn Documentation
* King County House Sales Dataset



If you found this project useful, consider giving it a ⭐ on GitHub.

