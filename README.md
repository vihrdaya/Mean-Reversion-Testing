# Mean Reversion Testing

### Introduction
Mean reversion testing tries to determine whether a time series eventually averages to a value over the life of the time series.
I needed functions that will average the percent change across the entire time series of the data. I then needed to find a coefficient of correlation, almost a regression on one time series data to another. I chose to make my data span a range between Jan 1, 2017 and May 5, 2017. It was an arbitrary choice to limit the amount of data for my computer to process.

This of course has its flaws.

I lose out on having a proper length of time series data to normalize over.
If there are seasonal trends. For example for a winter clothing supply company whose sales would spike during the winter months.


### Result

['MPC', 'FANG']


| Description | Values      |
|-------------|:-----------:|
|Company Pair | MPC/FANG    |
|ADF   | -2.800564	  |
| P-value | 0.058193 |
| Critical Values at 1%	| -3.509736 |
| Critical Values at 5% | -2.896195 |
| Critical Values at 10% | -2.585258 |
| Hypothesis | Non-Stationary |

![output](https://user-images.githubusercontent.com/49893887/181937287-d73230f9-c0c7-491a-a1a5-1cc1c627b9fd.png)
