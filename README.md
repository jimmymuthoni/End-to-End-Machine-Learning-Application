# Student Performance Prediction Web App

This project is a web application that predicts student performance using various machine learning algorithms. The app is built using Flask for the web framework and integrates a custom pipeline for data preprocessing and prediction.

## Features
- Predicts student performance based on user-provided input.
- Implements an end-to-end machine learning pipeline.
- Uses Flask for serving the web application.
- Accepts input features such as gender, ethnicity, parental education level, and test scores.

## Tech Stack
- **Programming Language**: Python
- **Framework**: Flask
- **Machine Learning Libraries**: scikit-learn, pandas, numpy
- **HTML Templates**: Jinja2

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/student-performance-predictor.git
   cd student-performance-predictor
   ```

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   python app.py
   ```

   The application will start running on `http://127.0.0.1:5000`.

## Usage

1. **Navigate to Home Page**:
   Open your browser and go to `http://127.0.0.1:5000`.

2. **Input Data**:
   Provide the following details in the input form:
   - Gender
   - Race/Ethnicity
   - Parental Level of Education
   - Lunch Type
   - Test Preparation Course
   - Writing Score
   - Reading Score

3. **Get Prediction**:
   Submit the form to view the predicted performance.


## Input Features

The application requires the following inputs:

| Feature                    | Description                               |
|----------------------------|-------------------------------------------|
| Gender                     | Male or Female                           |
| Race/Ethnicity             | Group classification (e.g., Group A, B)  |
| Parental Level of Education| Highest education level of parents        |
| Lunch                      | Standard or Free/Reduced                 |
| Test Preparation Course    | Completed or None                        |
| Writing Score              | Score in the writing test                |
| Reading Score              | Score in the reading test                |

## How Web Page Looks
![image alt](https://github.com/jimmymuthoni/End-to-End-Machine-Learning-Application/blob/771fa685116509d3a18a483f142ead3b557c659a/StudentPerformance.png)

## Model and Pipeline

The prediction pipeline performs the following steps:

1. **Data Preprocessing**: Converts user input into a format suitable for the model.
2. **Model Prediction**: Uses a pre-trained machine learning model (e.g., Ridge Regression) to predict student performance.

## Future Improvements

- Add more features for prediction.
- Implement additional machine learning models for comparison.
- Improve the UI/UX of the web application.
- Deploy the application using cloud platforms like AWS or Heroku.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contributing

Contributions are welcome! Please create an issue or submit a pull request for any improvements.

## Acknowledgments

- [Flask Documentation](https://flask.palletsprojects.com/)
- [scikit-learn Documentation](https://scikit-learn.org/)
