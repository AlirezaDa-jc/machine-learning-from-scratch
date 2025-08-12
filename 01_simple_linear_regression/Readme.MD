# Student Score Prediction using Linear Regression

This project demonstrates a simple implementation of **Linear Regression** from scratch to predict student exam scores based on the number of hours they studied.

---

## Features

- Manual implementation of Linear Regression using the Normal Equation
- Includes bias term (intercept) handling
- Calculates evaluation metrics: Mean Squared Error (MSE) and Mean Absolute Error (MAE)
- Comparison with `scikit-learn`'s LinearRegression model
- Data visualization using `matplotlib`
- Interactive Jupyter notebook format for easy experimentation

---

## Dataset

The dataset contains study hours as the feature and corresponding exam scores as the target:

| Hours Studied | Score (out of 100) |
|---------------|--------------------|
| 1.5           | 35                 |
| 3.0           | 50                 |
| 4.5           | 65                 |
| 6.0           | 80                 |
| 7.5           | 95                 |

---

## How to Run

1. Clone the repository:
   ```bash
      git clone https://github.com/alirezada-jc/student-score-prediction.git
      cd student-score-prediction
   ```
2. (Optional) Create and activate a virtual environment:
   ```bash
      python -m venv venv
      source venv/bin/activate  # Linux/Mac
      venv\Scripts\activate     # Windows
   ```
3. Install dependencies:
   ```bash
      pip install -r requirements.txt
   ```
4. Launch the Jupyter notebook:
   ```bash
      jupyter notebook
   ```

Open the notebook ```student_score_prediction.ipynb``` and run all cells.
---
## Usage

- Modify the new_hours variable in the notebook to predict scores for different study durations.
- Explore the evaluation metrics to understand model accuracy.
- Experiment by adding more data or features.
---
## Dependencies

- numpy
- matplotlib
- scikit-learn

---
## Future Improvements
- Split dataset into training and testing sets

- Add polynomial regression for non-linear data

- Implement regularization to avoid overfitting

- Extend to multiple features (e.g., attendance, assignments)

- Add cross-validation

---

## Author

Alireza Dolatabadi

alireza.dolatabadi.jc@gmail.com

[Alireza Dolatabadi on LinkedIn](https://www.linkedin.com/in/alireza-dolatabadi-jc)

---
## License
This project is licensed under the MIT License.