# day-1-optimised

#Reusing Results

The results are computed only once and on demand.<br/>
The result after getting computed will be stored in variables and those variables will be returned when that function is called again with same data.<br/>
For sorting if the array is sorted in ascending order first and after that down function is called then we are just reversing the array elements and vice versa.<br/>
For calculating min and max elemnts of the array , if array is sorted up or down the code is returning them in O(1).<br/>
The result of mean(if precomputed) is used in standard deviation computation to prevent redundant calculation.<br/>
The result of upsort and downsort is also used in median function.<br/>
The result of sum is again used in the mean function.<br/>
The nullset_allvalues function will clear previous result when user inputs new data.<br/>
