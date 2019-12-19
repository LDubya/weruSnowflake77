# Weru's Snowflake 77

weruSnowflake77 is a 77-city TSP problem with an average NEOS concorde runtime of 7.24 minutes using the fixed seed and QSopt solver.

I created this instance while trying to understand which local and global characteristics impose an upward pressure on the amount of time concorde takes to match its running lower bound with the length of its shortest found tour.

To construct this particular instance, I began with a base graph (13 x 13 square), and then systematically introduced new points or translated old points, retaining the adjustments that appeared to make concorde go deeper into its branches on average before cutting. Computer scientists modify TSP problems using relaxations to help construct good lower bounds, so I decided to go the opposite way and modify existing tours to construct a tour with hard to find lower bounds.

## Problem set files:
 - weruSnowflake77.txt (x-y list file, L2 norm)
 - weruSnowflake77.tsp (TSPLIB format, EUC_2D)


## Benchmark result over 10 runs:


| Run | Job ID# | Total running time (seconds) |
|---|---|---|
| 1 | 7739963 | 513.44 |
| 2 | 7740009 | 336.64 |
| 3 | 7740023 | 514.25 |
| 4 | 7740029 | 447.97 |
| 5 | 7740038 | 357.10 |
| 6 | 7740072 | 447.47 |
| 7 | 7740073 | 336.19 |
| 8 | 7740075 | 515.80 |
| 9 | 7740088 | 361.26 |
| 10 | 7740091 | 515.19 |



x-y list, L2 norm:

```
77
-700 -700
700 -700
200 0
0 200
-200 0
0 -200
0 0
-600 600
-500 600
-400 600
-300 600
-200 600
-100 600
0 600
100 600
200 600
300 600
400 600
500 600
600 600
-600 -600
-500 -600
-400 -600
-300 -600
-200 -600
-100 -600
0 -600
100 -600
200 -600
300 -600
400 -600
500 -600
600 -600
600 -500
600 -400
600 -300
600 -200
600 -100
600 0
600 100
600 200
600 300
600 400
600 500
-600 -500
-600 -400
-600 -300
-600 -200
-600 -100
-600 0
-600 100
-600 200
-600 300
-600 400
-600 500
-500 -500
-400 -400
-300 -300
-200 -200
-100 -100
100 100
200 200
300 300
400 400
500 500
100 -100
200 -200
300 -300
400 -400
500 -500
-100 100
-200 200
-300 300
-400 400
-500 500
700 700
-700 700
```

Tour constructed by Lawrence Weru.

For further information, see [Plight of the Concorde TSP challenge](https://codegolf.stackexchange.com/questions/179370/plight-of-the-concorde) on Code Golf. 
