**ITP 2016**
=================


Using Python and Pandas for data analysis
===============

[Python](http://Python.org) is a general purpose programming language that is easy to learn. 

[Pandas](http://pandas.pydata.org/) is a Python library for doing
data analysis. It's really fast and lets you do exploratory work
incredibly quickly.

The goal of this cookbook is to give you some concrete examples for
getting started with pandas. 


I'm working with these datasets right now

* 311 calls in New York
* Movie data

It comes with batteries (data) included, so you can try out all the
examples right away.

You'll need an up-to-date version of IPython Notebook (&gt;= 3.0) and
pandas (&gt;=0.13) for this to work properly. It's set up to work with Python 2.7.


# Installation

You need to install all the packages for data analysis.  You can install all these using the **Anaconda distribution**  unless you really know what you are doing. 

Installation page:
[Anaconda](https://store.continuum.io/)

## Instructions:
* Download the version that suits your needs at [Anaconda](https://store.continuum.io/). I use 2.7
* Once it's downloaded double click on the package and wait until it installs. 
* Close and reopen all Terminal windows
* To make sure it installed correctly:
	* open a terminal
	* type "python"
	* type "import pandas"
	* you should see ** no errors ** 
	* Done !


Once you have pandas and IPython, you can get going!

# Download the Tutorial Materials

I would highly recommend using git. Once git is installed, you can clone the material in this tutorial by using the git address shown below:

```
git clone https://github.com/GusSand/itp_talk_2016
``` 

# Using the Tutorial materials
 
Once you have cloned the git repo, you can change to the cookbook directory and run ipython using the following commands:

```
cd pandas-cookbook/cookbook

ipython notebook
```

A tab should open up in your browser at `http://localhost:8888`


<br>
<br>



Table of Contents
=================

* [Chapter 0: Getting Ready](https://github.com/GusSand/itp_talk_2016/blob/master/cookbook/Chapter%200%20-%20Getting%20Ready.ipynb)
 <br> Making sure you have the prereqs 
* [Chapter 1: Quick tour of the IPython Notebook](https://github.com/GusSand/itp_talk_2016/blob/master/cookbook/Chapter%201%20-%20Tour%20of%20the%20IPython%20Notebook.ipynb)
 <br> Shows off IPython's awesome features like tab completion and magic functions.
* [Chapter 2: 20ish minutes to Python](https://github.com/GusSand/itp_talk_2016/blob/master/cookbook/Chapter%202%20-%2020ish%20minutes%20to%20Python.ipynb)
  <br> Shows off IPython's awesome tab completion and magic functions.
* [Chapter 3: Analyzing NYC 311 Open Data](https://github.com/GusSand/itp_talk_2016/blob/master/cookbook/Chapter%203%20-%20%20Analyzing%20NYC%20311%20data.ipynb)
  <br> Reading data from a CSV, finding most common complaints and some plots
* [Chapter 4: Analyzing MovieLens 1MM Dataset Data](https://github.com/GusSand/itp_talk_2016/blob/master/cookbook/Chapter%204%20-%20%20MovieLens%201%20Million%20DataSet.ipynb)
  <br>Analyzing the MovieLens 1 Million dataset to find data about movies with multiple tables. 
 
 

Contribute!
===========

If you see something wrong, or there's something you'd like to learn that I haven't
explained here, or there's something you know about that you would like to share,
create an issue! Send me email! Send a pull request!


TODO
====

* Add more about matplotlib

License
=======


<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

Some of this content adapted from: [Pandas-Cookbook](https://github.com/jvns/pandas-cookbook)


This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)


