# Applied Statistics 25-26:(8651)

## Assignments submitted as part of the module Applied Statistics 25-26:(8651), Higher Diploma in Science, Data Analytics

## *Author: Laura Lyons (G00438882)*

***

This README file was written using the [GitHub's documentation on READMEs](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes) as a guidance document
***

  &#x26a0;&#xfe0f; **DISCLAIMER**

  Microsoft Co-Pilot was used to generate ideas for the content of the following notebook. That said, the notebook is mainly my own work, as I had to re-work the code the text in generated to meet my own needs (*The warning icon was sourced from [Stackoverflow](https://stackoverflow.com/questions/50544499/how-to-make-a-styled-markdown-admonition-box-in-a-github-gist)*).

## **Table of contents**

1. [The purpose of this module.](#1-the-purpose-of-this-module)
1. [Introduction.](#2-introduction)
1. [How to get started.](#3-how-to-get-started)
1. [Project Summary](#4-project-summary)
1. [How to get help.](#5-how-to-get-help)
1. [How to contribute.](#6-how-to-contribute)
1. [Biblography](#7-bibliography)

## 1. The purpose of this module

As noted on the [applied-statistics github repository](https://github.com/ianmcloughlin/applied-statistics), the aim of this module is to enable you to demonstrate your ability to:

1. Describe the stochastic nature of real-world measurements.
1. Source documentation to programmatically perform a statistical test.
1. Select an appropriate statistical test to investigate a claim.
1. Perform a statistical test on a data set.

## 2. Introduction

This noteboook is created to fufil the assessment required for the module, Applied Statistics 25-25:(8651), Higher Diploma in Science, Data Analytics. The notebook is to demonstrate achievement of the learning outcomes for this module, to be submitted in a GitHub repository created solely for this assessment.

## 3. How to get started

### Necessary software

In order to run the included files, you will need to ensure that you have access to the correct software. I would recommend downloading the following applications (ensuring sufficient space on your hard drive prior to installation):

1. [Anaconda](https://www.atu.ie/sites/default/files/2024-02/aqae022-academic-integrity-policy-1.pdf) (if Anaconda is too large, miniconda would also suffice).
2. [Visual Studio Code](https://code.visualstudio.com/Download) (this is a code editor).

### **Additions to** *.gitignore*

A number of [additional files](https://github.com/github/gitignore/tree/main/Global) were added to my ``.gitignore`` prior to running the programmes:

  1. python.gitignore
  2. macOS..gitignore
  3. VisualStudioCode.gitignore
  4. Linux.gitignore
  5. TeX.gitignore
  6. Vim.gitignore
  7. Windows.gitignore

## How to run the project

### Using Visual Studio Code & Anaconda

**Clone the Repository**:

```ruby
   git clone https://github.com/Laura6826/applied-statistics-8651
```

**Install the required packages**:

For a seamless executition, I would also recommend you have access to the below libraries prior to running the files. The libraries required to run this project include:

```ruby
math
itertools
random
numpy
matplot.lib
pandas
statsmodels
scipy.stats
seaborn
```

OR

**Manually install @requirements.txt'**:

```ruby
pip install -r requirements.txt
```

### Open in Visual Studio Code

- Open Visual Studio Code.
- Open the `Applied Statistics 25-26:(8651)` folder.
- Open the folder associated with the assignment you wish to look at.

## 4. Project summary

*This is a brief description of the topic addressed in the associated notebook.*

*To avoid repetition, the imports required for **problems 1–4** have been consolidated into a single import section, located under problem 1 at the start of this notebook.*

### Problem 1

The objective of this problem is to simulate the *'Lady Testing Tea'* experiment and compare the probability of correctly identifyig all milk-first ups by changes in:

1. The original 8-cup setup (4 milk-first, 4 tea-first).

1. An extended 12-cup setup (4 milk-first, 8 tea-first).

### Problem 2

This problem focuses on random sample generation and the normal distribtion, and how to assess if a saple/population is normally distributed.

 It also analyises the effects of variating degrees of freedom on standard deviation.

### Problem 3

This problem looks at the influence of mean difference and the probability of the occurance of a type II error, when a test fails to reject the null hypothesis even though it is false.

### Problem 4

This problem focuses comparing means, between normaly distributed samples/populations, using both independent t-tests and ANOVAs and analyising which is more appropriate.

## 5. How to get help

I have attached below, a number of helpful links, should you wish to extrapolate on any of the methods used within this project.

1. [Anaconda](https://www.atu.ie/sites/default/files/2024-02/aqae022-academic-integrity-policy-1.pdf)
1. [Visual Studio Code](https://code.visualstudio.com/Download)
1. [Pandas](https://pandas.pydata.org/)
1. [Numpy](https://numpy.org/)
1. [Matplotlib.py](https://matplotlib.org/)
1. [Seaborn](https://seaborn.pydata.org/)
1. [Stackoverflow](https://stackoverflow.com/questions)
1. [scipy](https://docs.scipy.org/doc/scipy/)
1. [Python](https://docs.python.org/3/)
1. [geeksforgeeks](https://www.geeksforgeeks.org/)
1. [Statology](https://www.statology.org/)

Additionally, a number of links are embedded within the code, in areas that I found confusing, that should help should there be any difficulty.

## 6. How to contribute

As this project was created to fulfil an assessment requirement of the Applied Statistics 25-26:(8651), as part of the H.Dip in Science in Data Analytics, no contributions will be allowed, in order to comply with ATU Policy on [Plagiarism](https://www.atu.ie/sites/default/files/2024-02/aqae022-academic-integrity-policy-1.pdf) and the [Student Code of Conduct](https://www.atu.ie/sites/default/files/2022-08/Student%20Code_Final_August_2022.pdf).

Should you find any errors or have any recommendations, please submit a pull request on GitHub. or just wish to contact that author, you can do so at <maxwell6826@gmail.com>.

## 7. Bibliography

### Problem 1 citations

1. ``math.comb()``(<https://www.geeksforgeeks.org/python/python-math-comb-method/>)
1. ``random.sample`` was used for random sampling without replacement (<https://docs.python.org/3/library/random.html#random.sample>)
1. ``intersection`` (<https://www.geeksforgeeks.org/python/intersection-function-python/>)
1. ``np.unique`` (<https://numpy.org/doc/stable/reference/generated/numpy.unique.html>)

#### Problem 2 citations

1. An explaination of the normal distribution(<https://www.geeksforgeeks.org/python/how-to-plot-normal-distribution-over-histogram-in-python/>)
1. ``np.random.seed()`` (<https://numpy.org/doc/stable/reference/random/generated/numpy.random.seed.html>)
1. ``np.random.normal`` (<https://numpy.org/doc/stable/reference/random/generated/numpy.random.normal.html>)
1. ``np.random.Generator`` (<https://stackoverflow.com/questions/67703875/np-random-binomial-vs-random-choices-for-simulating-coin-flips>)
1. ``Q-Q Plot`` (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.probplot.html>)
1. ``flatten()`` (<https://numpy.org/doc/stable/reference/generated/numpy.ndarray.flatten.html>)
1. ``probplot`` (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.probplot.html>)
1. Shaprio-Wilk Test (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.shapiro.html>)
1. ``numpy.std`` (<https://numpy.org/doc/stable/reference/generated/numpy.std.html>)
1. ``numpy.mean`` (<https://numpy.org/doc/stable/reference/generated/numpy.mean.html#numpy-mean>)
1. Set plot style for cleaner visuals (<https://matplotlib.org/stable/tutorials/introductory/customizing.html>)
1. Create figure with specified size (<https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.figure.html>)
1. Histograms ``density=True`` (<https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.hist.html>)
1. ``np.linspace`` (<https://numpy.org/doc/stable/reference/generated/numpy.linspace.html>)
1. ``norm.pdf`` (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html>)
1. ``axvline`` (<https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.axvline.html>)
1. MathJax was used to generate AsciiMath notation. (<https://docs.python.org/3/library/random.html#random.sample.>)
1. Jupyter notebook Markdown math usage (MathJax) — (<https://jupyter-notebook.readthedocs.io/en/stable/notebook.html#markdown-cells>)
1. ``ddof`` (<https://numpy.org/doc/stable/reference/generated/numpy.std.html>)
1. Bessels Correction (<https://en.wikipedia.org/wiki/Bessel%27s_correction>)

### Problem 3 citations

1. Hypothesis testing (<https://www.scribbr.com/statistics/hypothesis-testing/>) (<https://www.jmp.com/en/statistics-knowledge-portal/inferential-statistics/hypothesis-testing>)
1. Type I & Type II Errors Explained (<https://www.scribbr.com/statistics/type-i-and-type-ii-errors/>)
1. Type I and Type II Errors in Statistics (<https://www.geeksforgeeks.org/data-science/type-i-and-type-ii-errors/>)
1. Statology – Understanding Type I and Type II Errors (<https://www.statology.org/understanding-type-errors/>)
1. *t-test* (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.ttest_ind.html>)

### Problem 4 citations

1. ANOVA (<https://www.geeksforgeeks.org/maths/anova-formula/>)
1. ``f_oneway`` (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f_oneway.html>)
1. Tukey Test (<https://www.geeksforgeeks.org/data-science/tukey-kramer-test-for-post-hoc-analysis/>)
1. ``probplot`` (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.probplot.html#scipy.stats.probplot>)
1. Shaprio-Wilk Test (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.shapiro.html>)
1. Tukey test (<https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.tukey_hsd.html>)
1. ``df.describe()`` (<https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.describe.html>)
1. ANOVA vs *t-test* (<https://metricgate.com/blogs/anova-vs-multiple-ttests/>)

***

### End
