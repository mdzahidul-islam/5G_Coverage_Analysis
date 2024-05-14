# Abstract

This study focuses on testing and predicting 5G network coverage in various environments using multiple datasets. These datasets include metrics such as signal strength, signal quality, angle, and distance of 5G signals across different settings from open rural areas to densely urban spaces. Our approach involved selecting key features from these datasets, training machine learning models, and using these models to predict 5G coverage outcomes. We explored a wide range of relationships between features and outcomes, and tested multiple machine learning methods to identify the models that yield the most accurate predictions.

# Data Preprocessing

The file paths used in the Python code may not correspond directly to the paths where the data is stored, as the analysis was performed in Jupyter Notebook. To replicate the preprocessing steps, please update the file paths in the code accordingly. The path loss dataset can be found [here](https://c4science.ch/rBFMEASDATAMIDBAND41db885a85631e6ad391b56f34a04205dca0c33c#change-oIXzSc44CSCi), and the throughput dataset is available at [Lumos5G](https://lumos5g.umn.edu/). The notebooks ['Path_loss_data_processing.ipynb'](./'Path_loss_data_processing.ipynb') and ['Throughput_data_processing.ipynb'](./Throughput_data_processing.ipynb) contain the preprocessing steps for the path loss and throughput datasets, respectively.

# Data Analysis

The path loss dataset is analyzed as a regression task, while the throughput dataset is handled as a classification task. Several machine learning methods are employed for both tasks, including Random Forest (RF), XGBoost (XGB), Multilayer Perceptron (MLP), Support Vector Machine (SVM), and k-Nearest Neighbors (KNN). The notebooks ['path_loss_prediction.ipynb'](./path_loss_prediction.ipynb) and ['throughput_prediction.ipynb'](./throughput_prediction.ipynb) detail the data analysis process.

# Report

For a detailed analysis and comprehensive results, please refer to the attached project report.

# Requirements

This project requires Python 3.8+, along with the following Python libraries:

- numpy
- pandas
- scikit-learn
- xgboost
- matplotlib
- jupyter
- seaborn

You can install these dependencies via `pip` using the following command:

'''bash
pip install numpy pandas scikit-learn xgboost matplotlib jupyter seaborn


# Getting Started
To run this project, clone the repository and install the required dependencies.
Next, open the Jupyter notebooks ['path_loss_prediction.ipynb'](./path_loss_prediction.ipynb) and ['throughput_prediction.ipynb'](./throughput_prediction.ipynb) to begin the analysis.
