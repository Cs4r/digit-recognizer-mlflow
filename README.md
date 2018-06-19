# digit-recognizer-mlflow

## What is this?

This is a sample project that ilustrates how to use MLflow and Jupyter to solve a classification problem.

## How do I run it?

1. Download the famous [MNIST dataset from Kaggle](https://www.kaggle.com/c/digit-recognizer) and place then under the `data` folder.
2. Ensure you have installed `jupyter`,`matplotlib`, `mlflow`, `pandas`, `numpy` and `sklearn` on your python distribution.
3. Navigate to the root folder of this project and, using the console, run jupyter and MLflow:
  * `jupyter notebook`
  * `mlflow ui`
4. Open Jupyter on a brower tab. Most likely the URL would be something like `http://localhost:8888/notebooks/MNIST data.ipynb`.
5. Open MLflow on a different brower tab. In this case the URL would be something like `http://127.0.0.1:5000/`.
6. Run all the cells on the Jupter notebook: `Top menu > Cells > Run all`. Wait the notebook to complete.
7. Inspect the results of each of the experiments in the MLflow interface.
