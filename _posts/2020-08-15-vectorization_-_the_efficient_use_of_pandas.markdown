---
layout: post
title:      "Vectorization - the efficient use of Pandas"
date:       2020-08-15 20:01:03 +0000
permalink:  vectorization_-_the_efficient_use_of_pandas
---

In this blog post we will explore vectorization which is included in the Pandas package of Python.  Pandas was created to add analysis functionality to python to get python on par with other languages such as R or SAS.

In order to be most efficient with Pandas, the following methods are used.  This list is sorted by slowest to fastest as far as efficiency:

Looping over rows in a DataFrame
Looping with iterrows
Looping with apply
Vectorization with Pandas Series
Vectorization with Numpy Array

Since vectorization is most efficient, this post will concentrate on vectorization with Pandas Series - a Series is one column in a DataFrame, isolated so that vectorization is most efficient
