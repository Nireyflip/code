###Multidimensional list

Originally published: 2012-05-12 05:51:37
Last updated: 2012-05-12 06:21:11
Author: Glenn 

Pass a tuple of positive integers of length N (any length) as dimensions to MDarray, and a list is created with the length equal to the product NNN of the dimensions specified in the tuple. The items are initialized to None, or to the value of the optional init parameter.  As a special case, passing an integer for dims creates a square array of that size (converts the integer to a tuple of length two with the same value for both entries).