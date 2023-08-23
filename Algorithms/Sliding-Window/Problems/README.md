# Some Sliding Window Problems
1. __Maximum sum subarray of Size k__
   
Given an array of positive integers, and a positive number k, find the maximum sum of any contiguous subarray of size k.
```
Input: [3, 5, 2, 1, 7], k=2
Output: 8
```  

__Explanation__
```
Here the subarray [1, 7] or [3, 5] is the sum of the maximum sum.
```
- - - -
2.  __Count Occurrences of Anagram__
    
Given a word and a text, return the count of occurrences of the anagrams of the word in the text.
> Anagram is a word, phrase, or sentence formed from another by rearranging its letters. 
> Example: `race` is anagrams of `care`
```
Input: text = gotxxotgxdogt, word = got
Output : 3
```  

__Explanation__
```
Words — got, otg, ogt are anagrams of got.
```
- - - -
3. __Difference between the maximum and minimum average of all k-length continuous subarrays__

```
Input: arr[ ] = {3, 8, 9, 15}, K = 2
Output: 6.5
```  

__Explanation__
```
All subarrays of length 2 are {3, 8}, {8, 9}, {9, 15} and their averages are (3+8)/2 = 5.5, (8+9)/2 = 8.5, and (9+15)/2 = 12.0 respectively.
Therefore, the difference between the maximum(=12.0) and minimum(=5.5) is 12.0 -5.5 = 6.5.
```
- - - -