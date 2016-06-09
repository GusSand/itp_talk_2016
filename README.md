**ITP 2016**
=================

How to use this tutorial
========================

You'll need an up-to-date version of IPython Notebook (&gt;= 3.0) and
pandas (&gt;=0.13) for this to work properly. It's set up to work with Python 2.7.

You can get these using `pip`:

```
pip install ipython pandas numpy tornado pyzmq jinja2 matplotlib
```

This can be difficult to get set up and require you to compile
a whole bunch of things. I instead use and recommend
[Anaconda](https://store.continuum.io/), which is a Python distribution which
will give you everything you need. It's free and open source.

Once you have pandas and IPython, you can get going!

```
git clone https://github.com/GusSand/itp_talk_2016

cd pandas-cookbook/cookbook

ipython notebook
```

A tab should open up in your browser at `http://localhost:8888`

Happy pandas!

```


Using Python and Pandas for data analysis
===============

[Python](http://Python.org) is a general purpose programming language that is easy to learn. 

[Pandas](http://pandas.pydata.org/) is a Python library for doing
data analysis. It's really fast and lets you do exploratory work
incredibly quickly.

The goal of this cookbook is to give you some concrete examples for
getting started with pandas. The [docs](http://pandas.pydata.org/pandas-docs/stable/)
are really comprehensive. However, I've often had people
tell me that they have some trouble getting started, so these are
examples with real-world data, and all the bugs and weirdness
that entails.

I'm working with these datasets right now

* 311 calls in New York
* Citibike data

It comes with batteries (data) included, so you can try out all the
examples right away.

Table of Contents
=================

* [Chapter 0: 10 minutes to Python](http://ttp://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/A%20quick%20tour%20of%20IPython%20Notebook.ipynb)
 <br> Might be a little bit more than 10 mins, but shows some basics on Python in regards to Data Analysis. 
* [Chapter 1: Quick tour of the IPython Notebook](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/A%20quick%20tour%20of%20IPython%20Notebook.ipynb)
  <br> Shows off IPython's awesome tab completion and magic functions.
* [Chapter 2: Analyzing NYC 311 Opean Data](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%201%20-%20Reading%20from%20a%20CSV.ipynb)
  <br> Reading data from a CSV, finding most common complaints and some plots
* [Chapter 4: Analyzing CitiBike Data](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%202%20-%20Selecting%20data%20&%20finding%20the%20most%20common%20complaint%20type.ipynb)
  <br>How to work with multiple files and analyze them. 
 
 
  
 * [Chapter 4: Find out on which weekday people bike the most with groupby and aggregate](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%204%20-%20Find%20out%20on%20which%20weekday%20people%20bike%20the%20most%20with%20groupby%20and%20aggregate.ipynb)
  <br> The groupby/aggregate is seriously my favorite thing about pandas and I use it all the time. You should probably read this.
* [Chapter 5: Combining dataframes and scraping Canadian weather data](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%205%20-%20Combining%20dataframes%20and%20scraping%20Canadian%20weather%20data.ipynb)
  <br>Here you get to find out if it's cold in Montreal in the winter (spoiler: yes). Web scraping with pandas is fun!
* [Chapter 6: String operations! Which month was the snowiest?](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%206%20-%20String%20Operations-%20Which%20month%20was%20the%20snowiest.ipynb)
  <br> Strings with pandas are great. It has all these vectorized string operations and they're the best. We will turn a bunch of strings containing "Snow" into vectors of numbers in a trice.
* [Chapter 7: Cleaning up messy data](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%207%20-%20Cleaning%20up%20messy%20data.ipynb)
  <br> Cleaning up messy data is never a joy, but with pandas it's easier &lt;3
* [Chapter 8: Parsing Unix timestamps](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%208%20-%20How%20to%20deal%20with%20timestamps.ipynb)
  <br> This is basically a quick trick that took me 2 days to figure out.
* [Chapter 9 - Loading data from SQL databases](http://nbviewer.ipython.org/github/jvns/pandas-cookbook/blob/master/cookbook/Chapter%209%20-%20Loading%20data%20from%20SQL%20databases.ipynb)
  <br> How to load data from an SQL database into Pandas, with examples using SQLite3, PostgreSQL, and MySQL.


Contribute!
===========

If you see something wrong, or there's something you'd like to learn that I haven't
explained here, or there's something you know about that you would like to share,
create an issue! Send me email! Send a pull request!


TODO
====

* Joining dataframes
* Using stack/unstack
* ???


License
=======

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/)

## Translations

There's [a translation into Chinese of this repo](https://github.com/ia-cas/pandas-cookbook).
