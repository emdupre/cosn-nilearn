---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  name: python3
---

# An introduction to [`nilearn`](http://nilearn.github.io)

In this tutorial, we'll see how the Python library `nilearn` allows us to easily perform machine learning analyses with neuroimaging data, specifically MRI and fMRI.

## Structure of the workshop

This workshop is divided into two main topics:

1. Extracting meaningful features from neuroimaging data
2. Performing classification analyses and visualizing results

Although we highlight a small subset of the available functionality here, please see the [Nilearn documentation](https://nilearn.github.io) for an in-depth review of the many different kinds of analyses that can be run using Nilearn.
For example, in addition to classification analyses, Nilearn can also be used to conduct [Multi-Voxel Pattern (MVP) decoding](https://nilearn.github.io/stable/auto_examples/plot_decoding_tutorial.html#sphx-glr-auto-examples-plot-decoding-tutorial-py) and [General Linear Model (GLM)](https://nilearn.github.io/stable/auto_examples/plot_single_subject_single_run.html#sphx-glr-auto-examples-plot-single-subject-single-run-py) analyses.
