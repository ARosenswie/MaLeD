# MaLeD (Machine Learning with Diabetic data)

Provided in this repositiory is a classification model for both patients with and without diabetes, found from the Kaggle dataset: https://www.kaggle.com/datasets/kavyashibu/diabetics-prediction-using-machine-learning?select=diabetes.csv.  We utilized various algorithms, which includes Decision Trees, Random Forests, eXtreme Gradient Boosting (XGB), and a Multi-Layered Perceptron Classifier (Neural Network). 
![](diabetic_data/data/table_maled.png)

Among these models, the Neural Network exhibited superior performance of the accuracy metric of the validation dataset. To optimize its performance, Grid Searching was employed to fine-tune the model's hyperparameters. The following optimal hyperparameters were identified:
* activation = tanh,
* alpha = 0.001,
* max_iter = 1000,
* and hidden_layer_sizes = (32, 16, 8, 4, 2).
![](diabetic_data/data/metrics.png)

Below is the Receiver Operating Characteristic (ROC) curve depicting the Neural Network's classification performance. 

![](diabetic_data/data/roc_plot.png)

Please note that this example is not intended for medical use.
