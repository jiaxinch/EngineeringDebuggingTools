# EngineeringDebuggingTools
Dataset complexity calculation:
Calculate L1 norm for every data point and sort them based on the L1 distance.
The purpose of this process is that we assume the closer the points are, the more similar features they share.
We then calculate the threhold which is the number of mislabeling datapoints, and use it to calculate the max/estimated required capacity for the dataset.
