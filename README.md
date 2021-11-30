# Challenge_10

Cryptocurrency Analysis using KMeans Clustering and PCA

This project uses the KMeans algorithm and Principle Components Analysis to cluster cryptocurrencies based on their performance during a set time period. The analysis shows how the different clusters of currencies performed similarly during the set time frame. 


---

## Technologies

This project is built in Python 3.6 and designed to be run in Jupyter Lab. In order to properly utilize the project, the following Python libraries will be used:

   [pandas](https://pandas.pydata.org/docs/)

   [hvplot](https://hvplot.holoviz.org/user_guide/index.html)

   [sklearn](https://scikit-learn.org/stable/)
   
   [pathlib](https://docs.python.org/3/library/pathlib.html)


---

## Installation Guide

This project requires the user to install the additional libraries not included in the base version of Python. To begin, the user must open an instance of Terminal or GitBash. In order to best run the project, a new development environment should be created using the following code:

```python
  conda create --name <environment name>
```

With the new environment created and activated, the user should install the pyviz, hvplot, and sklearn using the following lines of code:

```python
  
  conda install -c pyviz holoviews bokeh
  
  pip install sklearn

```


---

## Usage

Once the proper libraries have been installed into a Python environment, the user can run the project by navigating into the Challenge_10 directory using the command line. When in the directory, the user should open the directory in an instance of Jupyter Lab and run the project. The project will finish running and provide the analysis, visualizations and answers to guiding questions about the analysis. 


---

## Contributors

Briggs Lalor
email: briggsclalor@gmail.com

---

## License

MIT License

Copyright (c) [2021] [Briggs Lalor]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
