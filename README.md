# Movie Rating Prediction

Welcome to the **Movie Rating Prediction** repository! This project uses machine learning techniques to predict movie ratings based on various features like genre, director, and cast.

## Dataset
The dataset used for this project can be downloaded from Kaggle:

[Movie Rating Dataset on Kaggle](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies)

## Steps to Run the Model

### 1. Download the Dataset
1. Visit the Kaggle link provided above.
2. Sign in or create a Kaggle account if you haven't already.
3. Download the dataset as a `.csv` file to your local machine.

### 2. Open the Colab Notebook
1. Click on the provided Google Colab link to open the notebook.
2. Alternatively, upload the `.ipynb` notebook file from this repository to Google Colab.

### 3. Upload the Dataset
1. In the Colab notebook, locate the cell with the following code snippet:
    ```python
    from google.colab import files
    uploaded = files.upload()
    ```
2. Execute the cell. A file upload prompt will appear.
3. Upload the `.csv` dataset you downloaded from Kaggle.

### 4. Execute the Notebook
1. Run each cell in the Colab notebook sequentially by clicking on the play button next to each cell.
2. Observe the output for each step, including data exploration, preprocessing, model training, and evaluation.

## Project Overview
The notebook is divided into the following sections:

1. **Data Exploration**
   - Loading and visualizing the dataset.
   - Checking for missing values and duplicates.

2. **Data Preprocessing**
   - Handling missing data.
   - Encoding categorical variables.
   - Normalizing numerical features.

3. **Exploratory Data Analysis (EDA)**
   - Visualizing data using plots like scatter plots, histograms, and correlation heatmaps.

4. **Model Building**
   - Using Linear Regression to predict movie ratings.
   - Splitting the data into training and testing sets.

5. **Model Evaluation**
   - Evaluating the model using R-squared and Mean Squared Error (MSE).

## Dependencies
The following Python libraries are required to run the notebook:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

These dependencies are installed in the Colab environment by default. If you're running the notebook locally, install them using:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Additional Notes
- Ensure that the dataset filename matches the one used in the notebook code. If the filename is different, update the relevant code cell.
- For any issues or questions, feel free to open an issue in this repository.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
