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

```{code-cell} python3
:tags: [hide-cell]

import warnings
warnings.filterwarnings("ignore")
```

# An introduction to [`nilearn`](http://nilearn.github.io)

In this tutorial, we'll see how the Python library `nilearn` allows us to easily perform machine learning analyses with neuroimaging data, specifically MRI and fMRI.

## Structure of the workshop

This workshop is divided into two main topics:

1. Extracting meaningful features from neuroimaging data
2. Performing classification analyses and visualizing results

Although we highlight a small subset of the available functionality here, please see the [Nilearn documentation](https://nilearn.github.io) for an in-depth review of the many different kinds of analyses that can be run using Nilearn.
For example, Nilearn can also be used to conduct General Linear Model (GLM) analyses.
