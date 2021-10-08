# Simulating-Availability-of-Hospital-Beds
One challenge in health care operations is to forecast the number of hospital beds that are available at a given time, since patients admitted in the past may stay for several days and the number of beds are limited. If no more beds are available, then incoming patients may need to be turned away.

Three input arguments:

demandList: a list of positive integers representing the number of incoming patients who need a hospital bed in each day. (The first number corresponds to day 0, the second number to day 1, and so on.)
beds: a positive integer representing the total number of hospital beds available.
stay: a positive integer representing the number of days each admitted patient will stay. If stay=1, then every admitted patient leaves before any incoming patients arrive the next day. If stay=2, then each patient admitted on day  𝑡  will occupy a bed also for day  𝑡+1 , and leave before incoming patients arrive on day  𝑡+2 .
The function should return a list admissionRecord, corresponding to the number of incoming patients admitted on each day.
