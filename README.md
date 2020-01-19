# Content: Reading Data and Data Exploration
## Project: 67 Years of Lego

### Install

This project requires **Python 3.8** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer. 

### Code

Template code is provided in the `notebook.ipynb` notebook file.

### Run

In a terminal or command window, navigate to the top-level project directory `67-of-Lego/` (that contains this README) and run one of the following commands:

```bash
ipython notebook notebook.ipynb
```  
or
```bash
jupyter notebook notebook.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

Everyone loves Lego (unless you ever stepped on one). Did you know by the way that "Lego" was derived from the Danish phrase leg godt, which means "play well"? Unless you speak Danish, probably not.

In this project, we will analyze a fascinating dataset on every single lego block that has ever been built!

**Features**
1) `id`: block identification (Discrete); 
2) `name`: block name (Nominal); 
3) `rgb`: block color in red, green and blue scale (Nominal); 
4) `is_trans`: 0 if it is not tranparent, 1 if it is (Discrete);
