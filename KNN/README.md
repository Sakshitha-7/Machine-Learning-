**KNN Iris Flower Classification**
A beginner-level machine learning mini project that uses the K-Nearest Neighbors (KNN) algorithm to classify Iris flowers into three species: Setosa, Versicolor, and Virginica.

## PROJECT OVERVIEW
  This is a beginner-level Machine Learning project implementing the **K-Nearest Neighbors (KNN) Classification algorithm** using the Iris dataset. The project demonstrates preprocessing, feature scaling, selecting the optimal K value, cross-validation, visualization, and predicting flower species.

## DATASET
Source: sklearn.datasets.load_iris (built-in)
  Samples: 150       Features: 4
     Sepal Length (cm)
     Sepal Width (cm)
     Petal Length (cm)
     Petal Width (cm)
Target Classes: 3 (Setosa = 0, Versicolor = 1, Virginica = 2)
Missing Values: None

## WORKFLOW
1. Load Iris dataset
2. Convert dataset into DataFrame
3. Check for missing values
4. Split data into training and testing sets
5. Apply feature scaling using StandardScaler
6. Train KNN classifier
7. Find suitable K value:
   - Heuristic approach (`√N`)
   - Experimental approach using Cross Validation
8. Evaluate model accuracy
9. Plot accuracy vs K values
10. Visualize decision boundaries
11. Test model using custom input values

 ## Visualizations Included

- Accuracy vs K values graph
- Decision Boundary visualization
These help understand how K affects model performance and classification regions.


## Example Prediction
Input:
Sepal Length = 5.1
Sepal Width = 3.5
Petal Length = 1.4
Petal Width = 0.2
Output:Setosa

Beginner ML project built for learning and understanding KNN classification concepts.
