# Optimize-Pandas
Jupyter Notebook showing how to optimize Pandas operations with Index Optimization, Memory Optimization, and Vectorization.

## How to Benchmark
Use `timeit` and `lineprofiler` to measure performance.

## Optimization Techniques
Techniques to optimize the performance of your pandas dataframe operations:
* Use `group_by` instead of `filter` for categorical columns
* Prefer `join` instead of `merge` for joining dataframes
* Filter dataframes before joining them
* Use `inplace` option to optimize memory usage
* Use `vectorization` to improve speed of transformation operations

## References
* https://www.youtube.com/watch?v=HN5d490_KKk
* https://www.youtube.com/watch?v=nxWginnBklU
* https://medium.com/analytics-vidhya/understanding-vectorization-in-numpy-and-pandas-188b6ebc5398
* https://towardsdatascience.com/five-killer-optimization-techniques-every-pandas-user-should-know-266662bd1163
* https://colab.research.google.com/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/01.07-Timing-and-Profiling.ipynb
* https://www.kaggle.com/datasets/antonkozyriev/game-recommendations-on-steam

Made with ❤️ by [Data Max](https://www.data-max.io/)