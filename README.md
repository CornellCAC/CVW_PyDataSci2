### CVW Notebooks and Data

This repository provides supplementary material (in the form of Jupyter notebooks and data files) for use with the Cornell Virtual Workshop (CVW) tutorial on <a href="https://cvw.cac.cornell.edu/PyDataSci2">Python for Data Science - Part 2: Data Modeling and Machine Learning</a>.


The code in this repository was run in a conda environment through a series of installs as follows:

* conda install numpy pandas matplotlib seaborn scipy networkx bokeh jupyter ipython scikit-learn tensorflow=2.0.0
* conda install -c conda-forge textblob
* conda install xlrd
* conda install statsmodels

A full YAML file describing versions for these packages as well as their dependencies are in the repository file PyDS2.yml .

Although tensorflow=2.0.0 was included in the environment, it is not in fact used in any of the code, so it can be excluded from the environment if desired.

### Slides (notebook) for Webinar on "Python Tools for Data Science"

This repository also contains a Jupyter notebook used for presentation of an XSEDE Webinar on "Python Tools for Data Science" (7/28/2021).  Specifically, this includes:

* PyDSWebinar.ipynb:  Jupyter notebook containing webinar presentation slides
* PyDSWebinar.html:  statically rendered version of the webinar notebook
* images/*.png: image files that are included in the notebook
