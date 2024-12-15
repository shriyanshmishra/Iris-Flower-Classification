# **Iris Flower Classification**

### **Overview**
This project demonstrates the classification of Iris flower species—*Setosa*, *Versicolor*, and *Virginica*—based on their physical measurements. The dataset used contains measurements like Sepal Length, Sepal Width, Petal Length, and Petal Width. Using machine learning techniques, the project builds a classifier that predicts the species of an Iris flower based on these features.

---

### **Dataset**
The dataset contains the following columns:
- **Id**: Unique identifier for each observation.
- **SepalLengthCm**: Length of the sepal in cm.
- **SepalWidthCm**: Width of the sepal in cm.
- **PetalLengthCm**: Length of the petal in cm.
- **PetalWidthCm**: Width of the petal in cm.
- **Species**: The species of the Iris flower (Setosa, Versicolor, Virginica).

---

### **Project Steps**
1. **Data Exploration and Preprocessing**:
   - Loaded the dataset and checked for missing values or inconsistencies.
   - Encoded the categorical target variable (`Species`) using label encoding.

2. **Feature Selection and Splitting**:
   - Excluded the `Id` column as it is not a predictive feature.
   - Split the dataset into training and testing sets (80%-20%).

3. **Model Training**:
   - Used the Random Forest algorithm for classification.
   - Trained the model on the training dataset.

4. **Model Evaluation**:
   - Evaluated model performance using metrics like accuracy and a classification report.
   - Achieved high accuracy in classifying the three species.

5. **Testing and Prediction**:
   - Tested the model with sample inputs.
   - Successfully predicted the species of Iris flowers.

6. **Saving and Exporting Results**:
   - Saved predictions and datasets with predictions to CSV files for further use.
   - Provided an option to save the trained model as a `.pkl` file for reuse.

---

### **Technologies Used**
- **Python**: Programming language.
- **Libraries**: 
  - `pandas` for data manipulation.
  - `numpy` for numerical computations.
  - `scikit-learn` for machine learning algorithms.
  - `matplotlib` and `seaborn` for data visualization.

---

### **How to Run the Project**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/iris-flower-classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd iris-flower-classification
   ```
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script:
   ```bash
   jupyter notebook Iris_Classification.ipynb
   ```
5. Test the model using sample inputs or load the saved `.pkl` model for predictions.

---

### **Results**
The model achieved a high classification accuracy, effectively distinguishing between the three Iris species. Below is an example of a prediction:

| SepalLengthCm | SepalWidthCm | PetalLengthCm | PetalWidthCm | Predicted Species |
|---------------|--------------|---------------|--------------|-------------------|
| 5.1           | 3.5          | 1.4           | 0.2          | Iris-setosa       |

---

### **Future Improvements**
- Experiment with other machine learning algorithms (e.g., SVM, KNN).
- Perform hyperparameter tuning to optimize the model.
- Deploy the model using a web framework like Streamlit or Flask.

---

### **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
