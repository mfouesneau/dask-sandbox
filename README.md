# dask-sandbox

Some tests/notes about python Dask

Dask is a flexible parallel computing library for analytic computing. http://dask.pydata.org/en/latest/

In a few words, Dask is trying to port most of the Pandas and NumPy ecosystem to distributed computing systems. 
It is meant to be simple with a minimal intrusion in usual codes.

Dask is convenient on a laptop. It is pure python, therefore it installs trivially with conda or pip and 
shifts the paradigm of datasets sizes from "fits in memory" to "fits on disk".

Dask can scale out to a cluster of 100s of machines. It is fault tolerant, elastic, data local, and low latency. 
For more information see documentation on the distributed scheduler.

In this repository, I run a few test to familiarize myself with Dask using examples from my common work.
