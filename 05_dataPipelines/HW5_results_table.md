| parallel threads | prefetch buffer size | mean image rate | standard deviation |
|:----------------:|:--------------------:|:---------------:|:------------------:|
| 32 |  0 | 557.39 | 22.86 |
| 32 |  8 | 1080.74| 41.67 |
| 32 | 16 | 1077.12| 31.88 |
| 32 | 32 | 1091.75| 31.90 |
| 64 |  0 | 657.02 | 10.36 |
| 64 |  8 | 973.69 | 51.82 |
| 64 | 16 | 1009.26| 65.02 |
| 64 | 32 | 979.59 | 50.79 |
| 128|  0 | 625.45 | 9.50  |
| 128|  8 | 837.01 | 43.90 |
| 128| 16 | 835.96 | 26.93 |
| 128| 32 | 871.95 | 39.07 |
| 256|  0 | 635.90 | 10.49 |
| 256|  8 | 718.18 | 45.70 |
| 256| 16 | 676.46 | 55.30 |
| 256| 32 | 637.41 | 121.06|


From the table, the combination of 32 parallel threads and 32 prefetch buffer size gives the best performance (mean image/s), which is even better than using all the 256 threads.
The results indicate that the prefetch does save the processing time and improve the performence. 
