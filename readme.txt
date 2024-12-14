# Automated Machine Learning Pipeline Web Application

## Overview
This project is an **Automated Machine Learning Pipeline Web Application** designed to simplify the process of training, evaluating, and deploying machine learning models. The application provides an easy-to-use interface to preprocess data, train models, and fine-tune hyperparameters, making machine learning accessible to both beginners and experts.

---
## App Output

Check The App: https://mani-automl.streamlit.app/

## Features

- **Data Preprocessing**: Handle missing values, encode categorical variables, and scale numerical features.
- **Automated Model Training**: Train multiple machine learning models (e.g., Logistic Regression, Random Forest, XGBoost, etc.) with minimal manual intervention.
- **Hyperparameter Tuning**: Optimize models using techniques such as grid search and random search.
- **Clustering Support**: Perform clustering analysis using K-Means and Hierarchical Clustering.
- **Real-Time Feedback**: Evaluate trained models and display performance metrics.
- **Web-Based UI**: Interactive and intuitive interface built using Streamlit.

---

## Workflow

1. **Upload Dataset**:
   - Upload your dataset in CSV format.
2. **Preprocess Data**:
   - Handle missing values and apply encoding or scaling.
3. **Choose Problem Type**:
   - Select from Classification, Regression, or Clustering.
4. **Select Models**:
   - Choose one or more models to train (e.g., Random Forest, SVM, etc.).
5. **Train Models**:
   - Train the selected models with default or user-defined hyperparameters.
6. **Evaluate Results**:
   - View performance metrics and download trained models.

---

## Installation

### Prerequisites
- Python 3.8+
- pip

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/manikandanrock/Auto_ML.git
   cd Auto_ML
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate   # For Linux/macOS
   env\Scripts\activate     # For Windows
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   streamlit run AutoML.py
   ```

5. Open the application in your browser at `http://localhost:8501`.

---

## Usage

1. **Load Dataset**: Upload your CSV file.
2. **Configure Settings**: Choose the problem type, select models, and specify hyperparameters.
3. **Train Models**: Click "Train" to start model training.
4. **View Results**: Analyze model performance metrics and download the trained model.

---

## Technologies Used

- **Streamlit**: For building the web interface.
- **Scikit-learn**: For model training and evaluation.
- **XGBoost, CatBoost**: For advanced machine learning models.
- **Pandas**: For data manipulation.
- **Optuna**: For hyperparameter tuning (if applicable).

---

## Project Structure

```
├── app.py                     # Main application script
├── data                       # Folder for storing datasets
├── models                     # Folder for saving trained models
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
└── utils                      # Utility scripts for data preprocessing, etc.
```

---

## Future Enhancements

- Add support for deep learning models.
- Integrate advanced hyperparameter tuning methods (e.g., Bayesian Optimization).
- Provide detailed visualizations for model performance and feature importance.
- Enable deployment of trained models as REST APIs.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact

For questions or feedback, please reach out to:
- **Name**: MANIKANDAN
- **Email**: MANI777KANDAN777@GMAIL.COM
- **GitHub**: https://github.com/manikandanrock/

Feel free to contribute to the project by submitting issues or pull requests!
