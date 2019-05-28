# .TOP Malicious TLD Hot Spots

## Introduction

This is the accompanying source code and analysis for the blog post "Using DomainTools Threat Profile to Identify Risky TLDs".

Jupyter Lab and pyspark were used to run the analysis and TLD clustering. Jupyter Lab is the next incarnation of the Jupyter Notebook web application that lets you write and execute code, view visualizations, and write narrative text along with an analysis. For a good introduction in how to use Jupyter Lab visit these two links:

* https://blog.jupyter.org/jupyterlab-is-ready-for-users-5a6f039b8906
* https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html

## Running the Jupyter Lab Notebook

The following python dependencies need to be installed in order to run this Jupyter Lab Notebook

* `jupyter`
* `jupyterlab`
* `pyspark==2.3.1`
* `numpy`
* `plotly`

To start Jupyter Lab and run this analysis, clone this repo to your local disk, change directory to the newly cloned repo, then run the command `jupyter lab` from the command line.  A browser tab will open up running this Notebook.
