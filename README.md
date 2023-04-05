# com.mcast.project.NaydelMuscat

Research Design Project

# Setup

- **Step 01** - Install Python 3.10 from [homepage](https://www.python.org/) or via Windows Store

- **Step 02** - Install [Anaconda](https://anaconda.org/)/[MiniConda](https://docs.conda.io/en/latest/miniconda.html), setup conda environment, Jupyter, create Jupter Kernel, [Tensorflow/Keras](https://www.tensorflow.org/install/pip)

Launch Anaconda Prompt and **run as administrator**. Run the following code.

```
conda create --name naydel python=3.10
conda activate naydel
conda install -c conda-forge numpy
conda install -c conda-forge jupyter
ipython kernel install --name "naydel-kernel" --user
conda install -c conda-forge matplotlib
conda install -c conda-forge seaborn
conda install -c conda-forge pandas
conda install -c anaconda scikit-learn
conda install -c conda-forge scikit-surprise
conda install -c conda-forge nltk
conda clean --all
conda deactivate
```

# References

- [MovieLens](https://movielens.org/)
- [Kaggle MovieLens Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)
- [Initial Tutorial](https://www.relataly.com/content-based-movie-recommender-using-python/4294/)
- [Second Tutorial](https://www.relataly.com/building-a-movie-recommender-using-collaborative-filtering/4376/)
- [PCA](https://builtin.com/machine-learning/pca-in-python)
