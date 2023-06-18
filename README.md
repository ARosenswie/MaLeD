# MaLeD (Machine Learning with Diabetic data)

Provided in this repositiory is a classification model for both patients with and without diabetes, found from the Kaggle dataset: https://www.kaggle.com/datasets/kavyashibu/diabetics-prediction-using-machine-learning?select=diabetes.csv.  We utilized various algorithms, which includes Decision Trees, Random Forests, eXtreme Gradient Boosting (XGB), and a Multi-Layered Perceptron Classifier (Neural Network). 
![](diabetic_data/images/table_diabetic.pdf.png)

Among these models, the Neural Network exhibited superior performance with the validation dataset. To optimize its performance, Grid Searching was employed to fine-tune the model's hyperparameters. The following optimal hyperparameters were identified:
* activation = relu,
* alpha=0.001,
* hidden_layer_sizes=(32,16),
* and max_iter=3000.
![](diabetic_data/images/metrics.png)

Below is the Receiver Operating Characteristic (ROC) curve depicting the XGB model's classification performance. 

![](diabetic_data/images/roc.png)

Please note that this example is not intended for medical use.
