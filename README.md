# Linear-time-python-realization-of-Suffix-Array
Python realization of Kärkkäinen-Sanders algorithm 

A suffix Array is an array of lexicografically ordered suffixes of a string. This code uses Kärkkäinen-Sanders algorithm to build this array in time, 
that scales linearly with the size of the input string. 

An instance of the class SufAr_Kärkkäinen_Sanders, created with a string as an input argument, contains the
attributes SuffixArray and LCP (longest common prefix).

SuffixArray is a python list, containing the 0-based indexes of the suffixes, ordered lexicographically.

LCP is a python list, containing the length of the longest common prefix of suffixes i and i-1 from SuffixArray. By definition LCP[0]=0
