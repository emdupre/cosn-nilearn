---
jupytext:
  formats: md:myst
  text_representation:
    extension: .md
    format_name: myst
kernelspec:
  display_name: Python 3
  name: python3
repository:
  url: https://github.com/emdupre/cosn-nilearn
---

```{code-cell} python3
:tags: [hide-cell]

import warnings
warnings.filterwarnings("ignore")
```

# An introduction to [`nilearn`](http://nilearn.github.io)

In this tutorial, we'll see how the Python library `nilearn` allows us to easily perform machine learning analyses with neuroimaging data, specifically MRI and fMRI.
