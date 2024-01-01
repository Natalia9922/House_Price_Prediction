# House Prices Prediction in Poland

This repository contains code and data related to predicting house prices in Poland using real estate advertisement data from February 2021.

## Introduction

The goal of this project is to perform exploratory data analysis (EDA) and build a machine learning model that predicts house prices in Poland based on various features such as location, size, number of rooms, etc. The project utilizes Python programming language and popular data science libraries such as Pandas, Matplotlib, and Scikit-Learn.

## Dataset

The dataset used in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/dawidcegielski/house-prices-in-poland). It comprises cleaned real estate advertisement data with the following columns:

- `address`: Full address of the property
- `city`: City where the property is located (Warsaw, Cracow, Poznan)
- `floor`: The floor number of the apartment
- `id`: Unique identifier
- `latitude`: Latitude coordinates
- `longitude`: Longitude coordinates
- `price`: Price of the apartment in PLN (Target variable)
- `rooms`: Number of rooms in the apartment
- `sq`: Number of square meters of the apartment
- `year`: Year of the building/apartment

## Project Structure
  ```bash
    ├── data/
    │   └── house_prices_poland.csv        # Dataset file
    ├── notebooks/
    │   └── House_Prices_Prediction.ipynb # Jupyter notebook with code and analysis
    ├── README.md                          # Project README file
    └── requirements.txt                   # List of Python dependencies
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/House_Price_Prediction.git
   cd House_Price_Prediction
   ```
2. Install the required dependencies:

  ```bash
  pip install -r requirements.txt
  ```
3. Explore the Jupyter notebook: Open and run the **House_Prices_Prediction.ipynb** Jupyter notebook to understand the data analysis, preprocessing, model building, and evaluation steps.

4. Customize and modify the code: Make changes or improvements to the code as needed for your analysis or model enhancements.

## Dependencies
* Python 3
* Pandas
* Matplotlib
* Scikit-Learn
* Jupyter Notebook (for running the provided notebook)
  
## Contributing
Contributions are welcome! If you want to contribute to this project, feel free to open an issue or submit a pull request.
