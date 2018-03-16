## Well-log-predict
Random forrest/SVM

About
=====
Well-log-predict attempts to classify facies in well-log data using ML algorthims. 
Data in this notebook comes from the following [website](http://www.people.ku.edu/~gbohling/EECS833/).

The dependent variable is rock facies, while the independent variables are gamma ray (GR), resistivity logging (ILD_log10), photoelectric effect (PE), neutron-density porosity difference and average neutron-density porosity (DeltaPHI and PHIND). There are two geologic constraining variables: nonmarine-marine indicator (NM_M) and relative position (RELPOS). 

<p align="center">
  <img width="512" alt="screen shot 2018-02-28 at 1 10 06 pm" src="https://user-images.githubusercontent.com/32745301/36807527-dc2376fa-1c88-11e8-9e26-5df4737291a7.png">
</p>

Dependencies
------------
Well-log-predict is tested to work under Python 3

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [Scikit-learn](http://scikit-learn.org/stable/)

Code
=====

The modeling code is provided in the notebook `Well_Log_Predict.ipynb`.

To open it, go to the top-level project directory `Well-log-predcit/` and start the notebook server:

```jupyter notebook```

This should open a web browser to the server's dashboard. Click on the appropriate notebook (`.ipynb`) to open it.

Run
=====

To run a code cell in the notebook, hit `Shift+Enter`. Any output will be displayed below the corresponding cell.

You can also add/edit markdown text cells and render them using `Shift+Enter`.

