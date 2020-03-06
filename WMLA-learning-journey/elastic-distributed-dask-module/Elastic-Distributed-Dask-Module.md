


## Summary
&nbsp;
&nbsp;
Dask is a flexible library for parallel computing in Python.    Dask is Python friendly by using Python APIs and supporting data structures such as Numpy and Pandas.    Dask represents parallel computations with task graphs.   Dask Distributed Scheduler could scale up to multiple nodes cluster,  distributes and executes these task graphs in the cluster.


Elastic Distributed Dask of Watson Machine Learning Accelerator supports dynamic scaling of Dask Cluster by adding new Dask-CUDA-worker,  according to incoming workload demand.       The Dask Cluster starts with minimal resources (1 GPU per worker) .     Spectrum Conductor monitors incoming workload demand,  and dynamically adds new workers to support increasing workloads.     Spectrum Conductor also monitors resource utilization per worker,  and gracefully pre-empties idle worker(s) from the cluster .


&nbsp;
&nbsp;