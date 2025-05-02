# CyberAttacks_ML_Detection
A final year MSc project that uses Machine Learning models (SVM, ANN, CNN, Random Forest) on the CICIDS2017 dataset to detect and classify cyber attacks.The app uses Flask and includes Jupyter analysis.

# 📁 Project Structure
CyberAttacks_ML_Detection/ 
│ 
├── app.py                        # Flask web application
├── notebook.ipynb               # Main Jupyter notebook with ML workflow
├── model.pkl                    # Trained ML model file
├── requirements.txt             # Python dependencies
├── Dockerfile                   # Docker setup file
├── Procfile                     # Heroku deployment config
├── LICENSE                      # MIT License file
├── cyber.docx                   # Project report (Word doc)
├── pandas_profiling.html        # Auto EDA report
├── corrm.csv                    # Correlation matrix data
├── num_summary.csv              # Numeric feature summary
├── NSL_Dataset/                 # Contains training and test data
│   ├── Train.txt
│   └── Test.txt
├── results/                     # Output images/graphs
│   ├── 2020-06-15 15_28_16-Window.png
│   ├── ...
├── static/                      # CSS file for Flask app
│   └── style.css
├── templates/                   # HTML template for Flask
│   └── index.html
├── .ipynb_checkpoints/          # Auto-saved notebook backups


## ⚙️ Technologies Used

- Python 3.8+
- Flask
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook


## 🚀 How to Use

1. Clone the repo or download ZIP.
2. Install dependencies:
'''bash
pip install -r requirements.txt
3. python app.py #Run the Flask app
4. Open browser at http://localhost:5000

📊 Model Accuracy
| Model         | Accuracy |
|---------------|----------|
| Random Forest | 99.93%   |
| ANN           | 99.11%   |
| SVM           | 93.29%   |
| CNN           | 63.52%   |

🔮 Future Work
1. Live streaming detection
2. Add user login system
3. Explainable AI (SHAP)
4. Report downloads

👨‍🎓 Author
Sarikonda Abhinay Kumar Raju
