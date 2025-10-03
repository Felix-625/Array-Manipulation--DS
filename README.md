# Array-Manipulation--DS

This C# code efficiently solves the Array Manipulation problem by using a difference array technique. Instead of updating every element in the specified ranges, it increments the start index and decrements the position after the end index for each query, then computes a running sum to get the final array values. The maximum value found during this cumulative sum is returned as the result. The Main method handles input parsing, calls the arrayManipulation function, and outputs the maximum value.
