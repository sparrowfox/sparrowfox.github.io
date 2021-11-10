---
layout: post
title: Polar Alignment in Python Using Plated Solved Images
date: 2021-11-10
---

## Theory

\\( \vec{P}_c = \dots \tag{2}\label{eq:vector}\\)
In equation \eqref{eq:sample}, we find the value of an
interesting integral:

\begin{equation}
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
  \label{eq:sample}
\end{equation}

```python
import astropy
import numpy as np
```
