# minigrad (WIP)

minigrad is a tryout to build a small deep learning framework in Python 3.


## Usage

```py

from minigrad.tensor import Tensor

A = Tensor.ones(3)
B = Tensor.random(3)

C = B.matmul(A)

print(C)

```
