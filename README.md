# Mean Reversion Testing

### Introduction
Mean reversion testing tries to determine whether a time series eventually averages to a value over the life of the time series.

I needed functions that wil average the percent change across the entire time series of the data. I then needed to find a coeffienct of correlation, almost a regression on one time series data to another. I chose to make my data span a range between Jan 1, 2017 and May 5, 2017. It was an arbirary choice to limit the amount of data for my computer to process.

This ofcourse has its flaws.

1. I lose out on having a proper length of time series data to normalize over.
2. If there are seasonaly trends. For example for winter clothing suppy company who's sales would spike during the winter months.

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
