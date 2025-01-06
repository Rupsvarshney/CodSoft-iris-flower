# Iris Flower Classification 🌸

## Overview  
The **Iris Flower Classification** project leverages the famous Iris dataset to classify flowers into one of three species based on sepal and petal measurements:  
- **Setosa**  
- **Versicolor**  
- **Virginica**  

This project serves as an introductory machine learning task to demonstrate various classification models and techniques.  

## Dataset  
The dataset contains 150 records and includes the following features:  
1. **sepal_length**: Length of the sepal (in cm)  
2. **sepal_width**: Width of the sepal (in cm)  
3. **petal_length**: Length of the petal (in cm)  
4. **petal_width**: Width of the petal (in cm)  
5. **species**: The flower species (Setosa, Versicolor, Virginica)  

The dataset is sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Iris).  

## Technologies Used
-  **Python**
-  **NumPy**
-  **Pandas**
-  **Matplotlib**
-  **Seaborn**
-  **Scikit-learn**

## Project Highlights  

### 1. Data Preprocessing  
- Handled missing values and encoded the categorical `species` column using `LabelEncoder`.  
- Exploratory Data Analysis (EDA) was conducted to visualize feature distributions and relationships.  

### 2. Data Visualization  
- **Histograms**: Displayed distributions of sepal and petal measurements.  
- **Heatmap**: Visualized feature correlations.  
- **Countplot**: Showed the distribution of species.  

Example visualization code: 

python  
sns.histplot(data=iris, x='sepal_length', color='red')  
sns.heatmap(iris.corr(), annot=True)  
sns.countplot(x='species', data=iris, palette='Set2')  
plt.show()  

## Iris-Flower-Classification 
   ├── iris_flower.ipynb       # Main Python script  
   ├── iris.csv                # Dataset  
   ├── README.md               # Project documentation


# 🔗 Connect
Feel free to explore, contribute, and share feedback:

LinkedIn: [Rupanshi-Varshney](https://www.linkedin.com/in/rupanshi-varshney-7630a6270/)
Email:- Vrupanshivarshney@gmail.com
