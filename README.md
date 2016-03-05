# Python pandas for data analysis

Hello, NICAR2016. We're here to introduce you to the `pandas` data analysis library.

We're assuming that you have a decent foundation in programming with Python and know the how and why of basic statistical analysis.

## What is `pandas`?

`pandas` is a popular and powerful software library for people who want to use Python for data analysis and data science.

### Why use `pandas` instead of Excel?

* You want to be ready to repeat your process if the raw data changes. Maybe it's the dataset is published regularly, or maybe an error is found in your original source.

* You want to be able to identify every step you took where you may have made an incorrect assumption, or where you'll need to defend your choices to your editor, or even a lawyer.

* You have more than one million rows of data.

* You want to collaborate on the data analysis and eliminate confusion about who has made which changes to the process.

### Why use `pandas` instead of R?

* You already have experience with python, and R's syntax slows you down.

* You want to use python libraries as part of your overall data processing pipeline.


## Installing `pandas`

If you don't already use python, you probably want to use [Anaconda](https://www.continuum.io/why-anaconda), which sets up your system for data science the same way that thousands of other people approach it. Anaconda is free, although the people who make it also provide commercial services if you have the budget.

Experienced python programmers may not be interested in adapting to Anaconda, or may disagree with its opinions about how an environment should be set up. Those people can install `pandas` with `pip`. If you don't even know what this means, use Anaconda.

_If you know what this means, hopefully you already know the value of `virtualenv` but if not, we'll take this opportunity to remind you. Consider making a `data` environment into which you install pandas, because once you get going, you may find a number of other interesting things to install. Like, just a few paragraphs down this page already! Or just check our our [requirements.txt](requirements.txt) file._

## Notebooks

Another popular tool for python data analysis is [jupyter notebook](http://jupyter.org/). It's the evolution of `iPython notebook`, so if you've heard of that, they are the same. We're using `jupyter` for this lesson!

Jupyter turns your web browser into a lab notebook which can execute code. You can switch between sections of explanation (written in HTML, or more precisely, in Markdown) and sections of executable code which can read data from your computer and do everything you might do in a program.  

It's even pretty easy to [publish a jupyter notebook](http://nbviewer.jupyter.org/github/pybokeh/ipython_notebooks/blob/master/pandas/PandasCheatSheet.ipynb) so that other people can see your work, and a lot of people do this to help each other learn the tools more.

jupyter is part of what gets installed automatically with Anaconda, but if you installed pandas yourself, you'll have to install this too. If you didn't use our [requirements.txt](requirements.txt) file above, then execute `pip install jupyter`.

#### python 2 vs python 3

We think it's time for most folks to get comfortable using Python 3 -- as of this writing, [322 of the 360 most popular libraries work on Python 3](http://py3readiness.org/). But we used python 2 for our notebooks for broader compatibility. If none of this means anything to you, don't sweat it -- just use Anaconda.

## Let's do it already

If you have everything installed and want to start at the beginning, open a terminal and navigate to the directory where this repository is checked out. When there, execute this command and start at the top.

```bash
jupyter notebook "Part 1.ipynb"
```
Part 1 will introduce you to just enough `jupyter` to follow the lesson, but  we wrote a little general stuff about [jupyter](jupyter.md) if you need it.

If you just want to read through what we did or use it for a quick reference, you can browse the notebooks on GitHub:

* [Part 1](Part%201.ipynb)- Getting comfortable with `jupyter notebook`
* [Part 2](Part%202.ipynb)- Open your data & start exploring
* [Part 3](Part%203.ipynb)- Dig deeper into more complicated, messy data
* [Part 4](Part%204.ipynb)- Extra Credit: Visualize the data
