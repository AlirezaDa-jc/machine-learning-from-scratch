### **Student Performance Prediction with Multiple Linear Regression**

This project demonstrates a complete workflow for predicting student final exam scores using multiple linear regression. It includes a manual implementation from scratch, a comparison with scikit-learn, exploratory data analysis (EDA), and an interactive widget for real-time predictions.

### **Features**

- **Multiple Linear Regression from Scratch:** Implements the Normal Equation to calculate model coefficients without using a machine learning library.
- **Scikit-learn Comparison:** Compares the manual implementation with scikit-learn's LinearRegression to verify results.
- **Exploratory Data Analysis (EDA):** Uses seaborn to generate a correlation heatmap and pair plots, helping to understand the relationships between features.
- **3D Visualization:** Visualizes the regression plane in 3D for two key features (Hours_Studied and Sleep_Hours) to provide a spatial understanding of the model's predictions.
- **Interactive Prediction Widget:** An ipywidgets-based tool that allows you to dynamically adjust feature values with sliders and see the predicted score in real-time.
- **Evaluation Metrics:** Calculates Mean Squared Error (MSE) and R-squared (R2) score for both models to evaluate performance.

### **Dataset**

The project uses a small, synthetic dataset to predict a student's Final_Exam_Score based on three features: Hours_Studied, Sleep_Hours, and Past_Score. The dataset is expected to be in a file named dataset.csv in the same directory as the notebook.

Hours_Studied,Sleep_Hours,Past_Score,Final_Exam_Score  
1.5,6,50,55  
2,7,60,63  
2.5,5.5,58,61  
... (and more data)

### **How to Run**

1. **Clone the repository:**

```bash
   git clone https://github.com/AlirezaDa-jc/machine-learning-from-scratch
   cd machine-learning-from-scratch/02\_multiple\_linear\_regression
```

2. **(Optional) Create and activate a virtual environment:**

```bash
   python \-m venv venv
   source venv/bin/activate \# On Linux/macOS
   venv\\Scripts\\activate \# On Windows
```

3. **Install dependencies:**

```bash
   pip install \-r requirements.txt
```

4. **Launch the Jupyter notebook:**

```bash
   jupyter notebook
```

5. Open the student_performance_notebook.ipynb notebook and run all cells to see the complete analysis and interactive predictor.

### **Usage**

- Run the notebook cells sequentially to load the data, perform EDA, and train the models.
- Once you reach the final section, use the interactive sliders to change the values for Hours_Studied, Sleep_Hours, and Past_Score and observe the predicted Final_Exam_Score.

### **Dependencies**

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn
- ipywidgets
- jupyter

### **Future Improvements**

- Split the dataset into training and testing sets to properly evaluate model generalization.
- Implement and compare with other regression algorithms, such as Gradient Descent.
- Add support for more complex models, like polynomial regression.
- Implement regularization to avoid overfitting.
- Add cross-validation to improve model robustness.

### **Author**

Alireza Dolatabadi

alireza.dolatabadi.jc@gmail.com

[Alireza Dolatabadi on LinkedIn](https://www.linkedin.com/in/alireza-dolatabadi-jc)

### **License**

This project is licensed under the MIT License.
