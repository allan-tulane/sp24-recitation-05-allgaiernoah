# CMPS 2200 Reciation 5
## Answers

**Name:**_Noah Allgaier________________________


Place all written answers from `recitation-05.md` here for easier grading.





- **1b.**
|      n |   qsort-fixed-pivot |   qsort-random-pivot |
|--------|---------------------|----------------------|
|    100 |               0.012 |                0.110 |
|    200 |               0.017 |                0.273 |
|    500 |               0.042 |                0.631 |
|   1000 |               0.088 |                1.461 |
|   2000 |               0.155 |                3.211 |
|   5000 |               0.416 |                8.576 |
|  10000 |               0.752 |               17.090 |
|  20000 |               1.419 |               35.614 |
|  50000 |               5.635 |              112.152 |
| 100000 |              11.952 |              265.933 |

While the running times don't perfectly math the asymptotic bounds, they follow the expected behavior of quicksort. 
In general, we can see that fixed-pivot qsort generally outperforms random, especially when the input size gets higher.  


- **1c.**
Timsort outperforms the fastest sorting implementations in both random and fixed permutations because of the way it is designed. 
