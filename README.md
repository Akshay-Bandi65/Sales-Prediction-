#Technologies Used

Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Joblib


VS Code
Project Structure
Sales_Prediction_Project/
│
├── advertising.csv        # Dataset file
├── sales_prediction.py    # Main Python source code
├── requirements.txt       # Required libraries
├── README.md              # Project documentation
└── model.pkl              # Saved trained model


How to Run the Project
Step 1: Clone or Download the Project

Download the project folder or clone it from GitHub.

Step 2: Open the Project in VS Code

Step 3: Create Virtual Environment
python -m venv venv

Step 4: Activate Virtual Environment
On Windows:
venv\Scripts\activate
On Mac/Linux:
source venv/bin/activate

Step 5: Install Required Libraries
pip install -r requirements.txt

Step 6: Run the Python File
python sales_prediction.py

Sample Output

Dataset Shape:
(200, 4)

First 5 Rows:
      TV  Radio  Newspaper  Sales
0  230.1   37.8       69.2   22.1
1   44.5   39.3       45.1   10.4
2   17.2   45.9       69.3    9.3
3  151.5   41.3       58.5   18.5
4  180.8   10.8       58.4   12.9

Missing Values:
TV           0
Radio        0
Newspaper    0
Sales        0
dtype: int64

Model Performance
MAE : 1.4607
MSE : 3.1740
R2 Score : 0.8994

Model Saved Successfully!
Enter TV Advertising Budget: 55
Enter Radio Advertising Budget: 52
Enter Newspaper Advertising Budget: 51
Predicted Sales = 15.42