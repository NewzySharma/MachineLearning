
## Hyperparameter Database Project

**Hyperparameters** are parameters that are specified prior to running machine learning algorithms that have a large effect on the predictive power of statistical models. Knowledge of the relative importance of a hyperparameter to an algorithm and its range of values is crucial to hyperparameter tuning and creating effective models. To either experts or non-experts, determining hyperparameters that optimize model performance can be a tedious and difficult task. Therefore, we develop a hyperparameter database that allows users to visualize and understand how to choose hyperparameters that maximize the predictive power of their models. The database is created by running millions of hyperparameter values, over thousands of public datasets and calculating the individual conditional expectation of every hyperparameter to the quality of a model. We analyze the effect of hyperparameters on algorithms such as Distributed Random Forest (DRF), Generalized Linear Model (GLM), Gradient Boosting Machine (GBM), and several more. Consequently, the database attempts to provide a one-stop platform for data scientists to identify hyperparameters that have the most effect on their models in order to speed up the process of developing effective predictive models. Moreover, the database will also use these public datasets to build models that can predict hyperparameters without search and for visualizing and teaching concepts such as statistical power and bias/variance tradeoff. The raw data will also be publically available for the research community.     

**What are the hyperparamters?**

Hyperparameters are parameters that are specified prior to running machine learning algorithms that have a large effecton the predictive power of statistical models. Hyperparameters are specified for tuning purpose, 
for examples:
* learningrate - Learning Rate
* n_layers     - Number of layers
* n_neurons    - Number of neurons
* Hidden Layers - Number of layers and size of each layers

Hyperparameters are important because they directly control the behaviour of the training algorithm and have a significant impact on the performance of the model that is being trained.