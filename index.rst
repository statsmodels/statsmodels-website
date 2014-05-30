Statsmodels
===========

Statsmodels is a Python module that allows users to explore data, estimate statistical models, and perform statistical tests. An extensive list of descriptive statistics, statistical tests, plotting functions, and result statistics are available for different types of data and each estimator. Researchers across fields may find that statsmodels fully meets their needs for statistical computing and data analysis in Python. Features include:

* Linear regression models
* Generalized linear models
* Discrete choice models
* Robust linear models
* Many models and functions for time series analysis
* Nonparametric estimators
* A collection of datasets for examples
* A wide range of statistical tests
* Input-output tools for producing tables in a number of formats (Text, LaTex, HTML) and for reading Stata files into NumPy and Pandas.
* Plotting functions
* Extensive unit tests to ensure correctness of results
* Many more models and extensions in development

Statsmodels runs on Python 2.6 through 3.4. To learn more about statsmodels have a look at our :doc:`documentation <documentation>`.

Examples
========

.. raw:: html
   :file: examples.html

Announcements
=============

* **Google Summer of Code 2014**: Statsmodels has again had two students accepted to on statsmodel as part of the `Google Summer of Code 2014 <https://www.google-melange.com/gsoc/homepage/google/gsoc2014>`_ program. Chad Fulton will be working on adding state space modeling capabalities. This will include a general, performant multivariate Kalman Filter. You can follow his progress on his `blog <http://pages.uoregon.edu/cfulton/categories/gsoc.html>`_. Frank Cheng is working to improve missing data handling. In particular he will implement imputation via chained equations (ICE) and multiple imputation via chained equations (MICE). You can follow his progress on his `blog <http://gsocfrankcheng.blogspot.ca/>`_. 

* **Statsmodels 0.5.0 Release**: A new major release was made on August 14, 2013. All users are encouraged to upgrade to this version.

* **Google Summer of Code 2013**: We have had two students accepted to work on statsmodels as part of the `Google Summer of Code <https://developers.google.com/open-source/soc/>`_ `2013 <https://www.google-melange.com/gsoc/homepage/google/gsoc2013>`_. The first project will focus on improving the discrete choice models, adding, for example, Conditional Logit, Nested Logit, and Mixed Logit models. The second project will focus on time series analysis, including regime-switching models such as SETAR, STAR, and Markov Switching models.

* **PyData New York Fall 2012**: There was a talk on using formulas with statsmodels with Patsy at the `PyData <http://pydata.org/>`_ `NYC Conference Fall 2012 <http://nyc2012.pydata.org/schedule/>`_. Slides are available `here <http://jseabold.net/presentations/seabold_pydata2012.html#slide1>`_. The notebooks for the talk are available in this `Github repo <https://github.com/jseabold/538model>`_.

* **Statsmodels Tutorial at SciPy 2012**: There was a `statsmodels tutorial <http://conference.scipy.org/scipy2012/tutorials.php#ti-79>`_ at the `SciPy 2012 conference <http://conference.scipy.org/index.html>`_. Video is available `here <http://pyvideo.org/video/1200/statsmodels>`_. The tutorial notebooks are available in the `statsmodels Github repository <https://github.com/statsmodels/statsmodels/tree/master/examples/notebooks>`_. They are also included in the main `statsmodels HTML examples documentation <http://statsmodels.sourceforge.net/devel/examples/index.html#notebook-examples>`_.

* **Statsmodels 0.4.3 Release**: 0.4.3 was release on July 2, 2012. The 0.4.1 - 0.4.3 releases were bug fix releases. The fixed some problems on big-endian machines and a few Python 3 problems.

* **Statsmodels 0.4.0 Release**: A new major release was made on April 29, 2012. All users are encouraged to upgrade to this version.

* **Google Summer of Code 2012**: We have had four students accepted to the Google Summer of Code 2012. This is statsmodels fourth year of participation in GSoC and promises to be our best yet. You can follow progress on each student's blog. The projects are `Nonparametrics Econometrics <http://statsmodels-np.blogspot.ca/>`__, `Systems of Equations <http://blog.a.crayssac.net/>`__, `Empirical Likelihood Methods <http://landopystat.blogspot.ca/>`__, and `(Robust) Non-linear Models <http://nonlinearstatsmodels.blogspot.in/>`__.

.. toctree::
   :hidden:
    
   developer
   documentation
   install
   news
