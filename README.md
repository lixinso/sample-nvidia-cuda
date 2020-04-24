# sample-nvidia-cuda

https://www.kaggle.com/c/jigsaw-unintended-bias-in-toxicity-classification/discussion/96876

```
from numba import cuda
cuda.select_device(0)
cuda.close()
```
