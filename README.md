# Vehicle Clustering Based on MPG
 
    This repository contains a Python project that uses agglomerative hierarchical clustering to group vehicles based on their miles per gallon (MPG) and other related features. The model is trained and evaluated on a dataset containing vehicle information, such as cylinders, displacement, horsepower, weight, acceleration, model year, origin, and car name.
    Dataset

    The dataset used in this project is a modified version of the Auto MPG dataset from the UCI Machine Learning Repository. It contains the following features:

    cylinders
    displacement
    horsepower
    weight
    acceleration
    model year
    origin
    car name

## Project Overview

    Data preprocessing: The dataset is first preprocessed by dropping the unique identifier feature (car name) and creating dummy variables for categorical features.

    Data scaling: The data is scaled using MinMaxScaler to ensure that all features have the same weight in the clustering process.

    Model training: An AgglomerativeClustering model is trained using a distance threshold to determine the number of clusters.

    Dendrogram: A dendrogram is created to visualize the clustering process and the resulting clusters.

    Cluster assignment: The cluster labels are assigned to the original dataset.

##Usage

    Clone this repository.
    Ensure that you have Python 3.x installed, along with the required libraries mentioned in the code (pandas, numpy, scikit-learn, scipy).
    Run the Python script to train the agglomerative hierarchical clustering model and visualize the results.

## Dependencies

    pandas
    numpy
    scikit-learn
    scipy

### Contributing

    Contributions are welcome. Please open an issue or submit a pull request to suggest changes or improvements.


### Credits

    Mete Turkan
    linkedIn : linkedin.com/in/mete-turkan
    Inst : m_trkn46
