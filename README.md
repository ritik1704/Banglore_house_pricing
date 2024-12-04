
# House Price Prediction Project




## Overview
This project involves a detailed analysis of house pricing data, focusing on data cleaning, exploratory data analysis (EDA), and comparative evaluation of various machine learning models for predictive accuracy. By employing robust preprocessing techniques, the project ensures data quality and reliability. The study also highlights insights derived from EDA, offering a deeper understanding of factors influencing house prices. Ultimately, the project culminates in the development of an intuitive GUI application using Tkinter, enabling users to interact seamlessly with the predictive models and gain actionable insights into housing market trends.
## Project Structure

### 1. Exploratory Data Analysis (EDA)
- Conducted an in-depth analysis to identify trends and relationships in the dataset.
- Examined the influence of price per square foot on overall house prices.
- Analyzed the distribution of different area types.

### 2. Data Cleaning and Preprocessing
- Performed data cleaning by:
  - Removing irrelevant columns.
  - Handling outliers and missing data.
  - Encoding categorical variables using one-hot encoding.

### 3. Predictive Modeling and Evaluation
- Trained and evaluated multiple machine learning models to predict house prices.
- Used **mean squared error (MSE)** and **10 fold cross-validation** for model performance evaluation.
- Selected the best-performing model for deployment.

### 4. Deployment Stage
- Saved the best model using the `pickle` library for reuse.  
- Created a GUI application using **Tkinter** to allow users to input house details and receive price predictions.  


## Data Source
The dataset used for this project is **synthetic** and publicly available on **Kaggle**, a trusted platform for accessing high-quality datasets. The dataset specifically focuses on house pricing data in Bengaluru, providing a comprehensive view of various factors affecting house prices.

You can access and download the dataset from the following link:  
[Bengaluru House Price Data on Kaggle](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data/data)

Kaggle is a reliable resource for data-driven projects, offering datasets curated by a vibrant data science community.
## Dependencies Installation

To run this project, the required Python libraries are listed in the `requirements.txt` file. Install them by running the following command:  

```bash
pip install -r requirements.txt
```
## Running the Project

### Steps to Execute:

1. **EDA and Data Cleaning:**  
   - Download the `house_pricing.ipynb` file and place it in the same folder as your dataset.  
   - Open the `.ipynb` file using **Anaconda** or **Jupyter Notebook**.  
   - Run the notebook cells sequentially to perform exploratory data analysis (EDA) and data cleaning.  

2. **Predictive Modeling:**  
   - Continue running the cells to build, evaluate, and compare predictive models.  
   - The notebook will save the best model for deployment.  

3. **Running the GUI Application:**  
   - The last executable cell in the notebook contains the code for the GUI application.  
   - Run this cell to launch the GUI directly within the notebook.  
   - Input the required details in the GUI to receive house price predictions.
  
## UI Representation
<img src="https://github.com/user-attachments/assets/e3640c34-07a6-4710-a422-9dd3c32c0913" alt="UI representation of the Application" width="400"/>

  
## Contact

For any questions or feedback, please contact Ritik Suri at [Ritik1704@gmail.com](mailto:Ritik1704@gmail.com).
