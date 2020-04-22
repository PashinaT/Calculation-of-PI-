# Calculation-of-PI-
Calculation of π on GPU with Monte-Carlo method using CUDA

### Task definition
Given the number of points N, generate a random distribution in (0, 0) − (1, 1) area and calculate the π number
using CPU and GPU. The resulting π values should be printed out along with the execution times.

To do this task, we need to count the number of points in circle - n_in_circle. Then find 4* n_in_circle/N.

#### Input data
• N – number of points;
#### Output data
• The time of GPU and CPU programs execution;
• π values calculated by GPU and CPU programs (results may be different).

### Results

The average time in milliseconds for 3 measurements

| Total points  | time CPU |  time GPU  | result π CPU | result π GPU  |
|---------------|----------|------------|--------------|---------------|
| 1048576=2^20  | 6 ms     | 1.21258 ms |   3.14042    |    3.14042    |
| 2097152=2^21  | 11 ms    | 1.37885 ms |   3.14146    |    3.14146    |
| 4194304=2^22  | 23 ms    | 2.96621 ms |   3.14062    |    3.14062    |
| 8388608=2^23  | 45 ms    | 7.64291 ms |   3.14189    |    3.14189    |
| 16777216=2^24 | 91 ms    | 8.94925 ms |   3.14126    |    3.14126    |
| 33554432=2^25 | 183 ms   | 17.0748 ms |   3.14145    |    3.14145    |
   
