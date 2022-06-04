<script
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML"
  type="text/javascript">
</script>

# ICA 1
Name: Hyun Suk (Max) Ryoo

Computing ID: hr2ee


## 1 (measure)
$O(n^2)$

The for loop that is first introduced runs in linear time.
Inside the for loop there is another for loop. The k for loop takes n time as well thus resulting in quadratic time. 

## 2 (addElement)
$O(1)$

Appending an element in a list is constant time.
We are also assuming that the printing of a list is constant time. 
Therefore, the function runs in constant time. 

## 3 (addOnesToTestList)
$O(n)$

Given that the print function is a constant time operation, we will iterate through the range of 0, num. This causes a run time of linear time n. Inside the linear time we append to the list, which again is constant time. Therefore, the total run time of linear time.

## 4 (someMethod)
$O(n^2)$

Given that the print function is a constant time operation, we have the first for loop going through the array (linear time). For each iteration we go through a for loop again. Thus quadratic time.

## 5 (searchTarget)
$O(n^3)$

Given that the range variables are proportional in size to n, we go through range 1 and for each element of range 1 we iterate through range 2 and for every iteratino of range 2 we iterate through range 3, which is 3 nested for loops causing a cubic time runtime. 

## 6 (someSearch)
$O(log n)$

This is binary search. 