This is the folder for the drought prediction with machine learning and deep learning models.

# Update about the dataset we use
We just find that the dataset we use has already upgraded to Version 5. Back then, we use [Version 2](https://www.kaggle.com/datasets/cdminix/us-drought-meteorological-data/version/2). A preprocessing notebook from **the json files in Version 2** to the **data_ndarray.npz** is added as **preprocessing.notebook**.

If you find this repository helpful, you may consider cite our relevant work:
* Jiang, W., & Luo, J. (2022). An Evaluation of Machine Learning and Deep Learning Models for Drought Prediction using Weather Data. Journal of Intelligent & Fuzzy Systems, vol. Pre-press, no. Pre-press, pp. 1-16, 2022. [Link](https://content.iospress.com/articles/journal-of-intelligent-and-fuzzy-systems/ifs212748) [arxiv_link](https://arxiv.org/abs/2107.02517)

# Dependencies
Anaconda is highly recommended for installing Python.

If you want to run the notebook of machine learning models. You many need to install the following packages first:
* [scikit-learn](https://scikit-learn.org/)
* [catboost](https://catboost.ai/)
* [xgboost](https://xgboost.readthedocs.io/)
* [lightgbm](https://lightgbm.readthedocs.io/)
* [pycaret](https://pycaret.org/)

If you want to run the notebook of deep learning models, you may need to install the following packages first:
* [pytorch](https://pytorch.org/)
* [fastai](https://www.fast.ai/)
* [tsai](https://timeseriesai.github.io/tsai/)
* [hyperopt](http://hyperopt.github.io/hyperopt/)

The code and results are self-explained in the notebooks. If you have further questions, feel free to raise an issue.
