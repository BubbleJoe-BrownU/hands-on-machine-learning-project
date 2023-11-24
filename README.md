# Cyber Brista
Many people love coffee. They enjoy the energy of caffeine and the joyful scent of a mixture of milk and espresso. But loving drinking coffee doesn’t mean one has the expertise to choose qualified coffee beans. As a large consumer of expresso lattes, I am so bad at rating coffee beans. And here comes the futuristic rescue! 

In this project, I developed the Cyber Barista, an ensemble of supervised regression models featuring linear regression, ridge regression, lass regression, ElasticNet, K-nearest-neighbors (KNN), random forest, support-vector machine regression (SVR), XGBoost, and a multi-layer perceptron (MLP). Besides implementing and training these models, I also automated the hyperparameter search process, so you don't have to go through this tedious process.
I strived to reduce the feature dimensionality to the degree that consumers can easily find the data required to run the Cyber Barista by purely looking at the package of their desired coffee beans. In this light, I intended to make the barrier of using our models as low as possible. 

# Project Environment
core packages used in this projects are:
- `python=3.10`
- `matplotlib=3.5.2`
- `pandas=1.4.2`
- `numpy=1.22.4`
- `tensorflow=2.10.0`
- `scikit-learn=1.1.1`


# Data Preprocessing
Dataset source: https://www.kaggle.com/datasets/michals22/coffee-dataset
**Caveat**: This dataset contains a large amount of NaN values, which are not directly handled by most algorithms, so please be careful to deal with them.
Please refer to the file `src/Introduction of the dataset.ipynb`, where I wrote down the entire preprocessing pipeline step by step and included various detailed visualization plots.

# Social Impacts
The data and algorithms used in this project contain no explicit bias to race or gender. However, we are aware that the dataset may contain biases with regard to different coffee bean origins, e.g. the data may be biased toward coffee beans produced from several origins and other origins are underrepresented in this dataset. Applications based on this project should take the potential bias into a thorough consideration before deployment.

# Reproducibility
Model weights are saved in the directory `model_weights`. If you have any trouble reproducing the presented result, please feel free to reach out to me via github!

# Citation
Please cite the original dataset if you find this project helpful.
