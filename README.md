# Image-Classification-LDA-and-PCA
Image Classification with Perceptron and LDA and PCA dimension reduction

## Tech :hammer_and_wrench: Languages and Tools :

<div>
  <img src="https://github.com/devicons/devicon/blob/master/icons/python/python-original.svg" title="Python" alt="Python" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original.svg" title="Jupyter Notebook" alt="Jupyter Notebook" width="40" height="40"/>&nbsp;
  <img src="https://assets.st-note.com/img/1670632589167-x9aAV8lmnH.png" title="Google Colab" alt="Google Colab" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" title="Numpy" alt="Numpy" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg"  title="Pandas" alt="Pandas" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/matplotlib/matplotlib-original.svg"  title="MatPlotLib" alt="MatPlotLib" width="40" height="40"/>&nbsp;
  <img src="https://cdn.worldvectorlogo.com/logos/seaborn-1.svg"  title="seaborn" alt="seaborn" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/tensorflow/tensorflow-original.svg"  title="tensorflow" alt="tensorflow" width="40" height="40"/>&nbsp;
  <img src="https://github.com/devicons/devicon/blob/master/icons/scikitlearn/scikitlearn-original.svg"  title="Sci-kit Learn" alt="Sci-kit Learn" width="40" height="40"/>&nbsp;
</div>


## Run the Notebook on Google Colab

You can easily run this code on google colab by just clicking this badge [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AsadiAhmad/Image-Classification-LDA-and-PCA/blob/main/Image_Classification_with_LDA_%26_PCA.ipynb)

## Conclusion

In this project, we demonstrated the application of LDA and PCA for effective dimensionality reduction in image classification tasks. In out analysis we found the LDA better than the PCA for dimension reduction task. Accuracy of the LDA is much better than PCA becuase LDA is supervised Learning and PCA is unsupervised learning method. Most of the time supervised Learning have better accuracy than unsupervised learning methods because supervised method using the labels but unsupervised dose not.However when we dont have any labels then we can just use the unsupervised method.

Here you can see BoxPlot of each method we have been used :

### LDA BoxPlot

<img src="/Pictures/BoxPlot-LDA.png"/>

### PCA BoxPlot

<img src="/Pictures/BoxPlot-PCA.png"/>

You can see better accuracy at LDA than the PCA method. Another conclusion we can get is look like when dimension reach a point like 9 to 25 dimension in PCA method our accuarcy does not grow much show that our method is reaching its highes point of accuracy after that maybe we have overfit and you can see the overfiting and underfiting results down here :

### LDA Results Table

<img src="/Pictures/conclusion-table-LDA.JPG"/>

### PCA Results Table

<img src="/Pictures/conclusion-table-PCA.JPG"/>

## License

This project is licensed under the MIT License.
