📊 Student Marks Prediction (My First Machine Learning Project)

This is my first Machine Learning project where I implemented Linear Regression to predict student exam scores based on different study-related factors.

It helped me understand the complete ML workflow — from data preprocessing to model evaluation.

🚀 Project Objective

To predict a student's final exam score using:

📚 Hours Studied

😴 Sleep Hours

🏫 Attendance Percentage

📝 Previous Scores

🧠 What I Learned

Through this project, I learned:

✔️ How Linear Regression works mathematically

✔️ Data preprocessing using Pandas

✔️ Feature selection and removing non-numeric columns (like student_id)

✔️ Splitting data into training and testing sets

✔️ Model evaluation using R² score and Mean Squared Error

🛠 Tech Stack

Python

Pandas

Seaborn

Scikit-learn

``` 
Student-marks-prediction/
│
├── Student_mark_prediction.ipynb   # Main Notebook
├── student_exam_scores.csv         # Dataset
└── README.md                       # Project Documentation
```

📈 Model Used

I used Linear Regression from Scikit-learn:
```
from sklearn.linear_model import LinearRegression
```

The model learns the relationship:
ExamScore = b0 + b1(HoursStudied) + b2(Sleep) + b3(Attendance) + b4(PreviousScore)

▶️ How to Run

1. Clone the repository:
``` bash
git clone https://github.com/Vallabhbhagat/Student-marks-prediction.git
cd Student-marks-prediction
```
2. Install dependencies:
 ``` bash
   pip install pandas numpy scikit-learn matplotlib
 ```

3. Run the notebook:
```bash
jupyter notebook Student_mark_prediction.ipynb
```

📊 Sample Output

The model predicts the exam score based on input values and evaluates performance using:

R² Score

Mean Squared Error

🔮 Future Improvements

Try Random Forest Regressor

Add data visualization dashboard

Build a simple Flask or Streamlit web app

Deploy the model

💡 Why This Project Matters

This project represents my first step into the field of:

Machine Learning

Data Science

Predictive Modeling

It built my foundation in understanding how real-world data is used to make predictions.
   
