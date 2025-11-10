## Author
Developed by Akbar Mohammadlou  
For questions or collaboration, feel free to open an issue or contact me via GitHub.

## Acknowledgements
Special thanks to the open-source community and the contributors of the Pima Indians Diabetes Dataset.

## Contact
For professional inquiries: ([https://www.linkedin.com/in/yourprofile](https://www.linkedin.com/in/akbar-mohammad-lou-b36b1437/))  
Or open an issue in this repository.

# Diabetes Detection Project

![Python](https://img.shields.io/badge/python-3.9-blue)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-notebook-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

## Contributing
Contributions are welcome!  
If you would like to contribute to this project, please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request


This project is designed to analyze and predict diabetes using the **Pima Indians Diabetes Dataset**.  
The code is written in Jupyter Notebook and includes the following steps:

- Load the dataset
- Exploratory Data Analysis (EDA)
- Correlation heatmap visualization
- Train a Linear Regression model
- Evaluate the model and calculate accuracy

## How to Run
To run this project, first install the required libraries and then open the notebook:
pip install -r requirements.txt
jupyter notebook Diabetes.ipynb

## Dataset
The dataset used is the [Pima Indians Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database).  
If the file `diabetes.csv` is not included, you can download it from the link above.

## Results
- Feature correlation heatmap
- Model performance metrics
- Accuracy of diabetes prediction

Below are sample outputs from the analysis:

### Correlation Heatmap
![Correlation Heatmap](Feature%20correlation%20Heatmap.png)

### Residuals Distribution
![Residuals Distribution](Residuals%20Distribution.png)

## Future Work
Planned improvements for upcoming versions:
- Add Logistic Regression model for better classification
- Compare performance with other algorithms (Random Forest, SVM)
- Improve data preprocessing and feature engineering
- Deploy the model as a simple web app (Flask/Streamlit)

## Demo
You can run this project online without installation using Google Colab:  
[Open in Colab](https://colab.research.google.com/github/amcatia/diabetes-detection/blob/main/Diabetes.ipynb)


