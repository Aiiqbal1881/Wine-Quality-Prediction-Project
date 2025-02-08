# Wine-Quality-Prediction-Project

# Wine Quality Prediction

## Overview
This project aims to predict the quality of wine based on its physicochemical properties using Machine Learning (ML) techniques. We use Python as the programming language, the Random Forest model for prediction, and matplotlib & seaborn for data visualization.

## Dataset
The dataset used in this project is the **Wine Quality Dataset**, which contains various features such as acidity, sugar level, pH, alcohol content, etc., that determine the quality of wine. The dataset can be found in the UCI Machine Learning Repository or kaggle.

## Technologies Used
- **Python**: Programming language used for data processing and model building.
- **Machine Learning (ML)**: Applied for predicting wine quality based on input features.
- **Random Forest Model**: The main ML algorithm used for classification.
- **Matplotlib & Seaborn**: For data visualization and exploratory data analysis.

## Project Structure
```
Wine-Quality-Prediction/
│-- data/                     # Contains the dataset
│-- notebooks/                # Jupyter Notebooks for analysis
│-- src/                      # Source code for model training
│   │-- data_preprocessing.py # Data cleaning and preprocessing
│   │-- model.py              # Training the Random Forest model
│   │-- visualization.py       # Data visualization scripts
│-- README.md                 # Project documentation
│-- requirements.txt          # Dependencies list
```

## Installation
To run this project, clone the repository and install the dependencies:
```bash
git clone https://github.com/your-username/Wine-Quality-Prediction.git
cd Wine-Quality-Prediction
pip install -r requirements.txt
```

## Usage
1. **Data Preprocessing**: Clean and prepare the dataset using `data_preprocessing.py`.
2. **Exploratory Data Analysis**: Use `visualization.py` to generate insights.
3. **Model Training**: Run `model.py` to train the Random Forest model.
4. **Prediction**: Use the trained model to predict wine quality based on new input features.

## Results & Analysis
- The model achieves high accuracy in predicting wine quality.
- Feature importance analysis helps identify key attributes affecting wine quality.
- Visualizations provide insights into data distribution and correlations.

## Contributing
Contributions are welcome! Feel free to fork the repository, create feature branches, and submit pull requests.

## License
This project is licensed under the MIT License.

## Author
[Ariz Iqbal] - [Aiiqbal1881]

## Acknowledgments
- UCI Machine Learning Repository for the dataset and also kaggle dataset.
- Open-source ML and visualization libraries.

