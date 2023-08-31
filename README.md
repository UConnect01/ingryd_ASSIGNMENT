# ingryd_statistical summary for temperature values
#FIND THE a)mean b)median c)mode d)range e)standard deviation f) variance g)mean deviation of the given data: temp = [34,23.45,32,43,54,34,67,89,98,13,43,56,23,45,67,33,43,44,30]

temp = [34,23.45,32,43,54,34,67,89,98,13,43,56,23,45,67,33,43,44,30]

#MEAN = SUM OF VALUES/TOTAL NUMBER OF VALUES (N) (for an ungrouped data)

N = 20
MEAN = sum(temp)/20
print(round(MEAN))

import statistics

sort_numbers = sorted(temp)
pass
MEDIAN = statistics.median(sort_numbers)
print(MEDIAN)

MODE= statistics.mode(sort_numbers)
print(MODE)

RANGE = max(sort_numbers) - min(sort_numbers)
print(RANGE)

variance = statistics.variance(sort_numbers)
print(round(variance))

standard_deviation = statistics.sqrt(variance) #square root of variance
print(round(standard_deviation))

#mean_deviation =sum(x-mean)/n where x is the individual element on the list

mean_deviation = statistics.mean(sort_numbers)
print(round(mean_deviation))

OUTCOME:

Mean value: 44
median value: 43
mode value: 43
range value: 85
variance: 481
standard deviation: 22
mean deviation: 46
