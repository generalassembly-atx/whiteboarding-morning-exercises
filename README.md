# Whiteboarding Morning Exercises

For this exercise you will be doing a practice whiteboarding exercise to test your programming skills.

### Rotating an Array -Easy

This problem is to rotate a given array to the right by n steps.

For example:

Given [1, 2, 3] and n = 1, you should return [3, 1, 2]

Each step, the last element in the array is moved to the front of the array, and the rest are shifted right.

Another example:

Given [1, 2, 3, 4, 5] and n = 3, you should return [3, 4, 5, 1, 2].
Given [1,2,3,4,5,6,7,8,9] and n = 4, you should return [ 6, 7, 8, 9, 1, 2, 3, 4, 5 ].

### Find the Largest Binary Gap -Hard

A binary gap within a positive integer N is any maximal sequence of consecutive zeros that is surrounded by ones at both ends in the binary representation of N.

For example, number 9 has binary representation 1001 and contains a binary gap of length 2. The number 265 has binary
representation 100001001 and contains two binary gaps: one of length 4 and one of length 2. The number 18 has binary representation 10010 and contains one binary gap of length 1. Note that the outside 0 doesn't count in this case. The number 15 has binary representation 1111 and has no binary gaps.


Write a function:

function solution(N);

that, given a positive integer N, returns the length of its longest binary gap. The function should return 0 if N doesn't contain a binary gap.

For example, given N = 1049 the function should return 5, because N has binary representation 10000011001 and so its longest binary gap is of length 5.

### Find the Sentence Containing the Largest Number of Words

You are trying to find the sentence containing the largest number of words in string. The text is specified as a String consisting of N characters, spaces, periods, question marks, and exclamation marks. 

The text can be divided into sentences by splitting it at the periods, question marks, and exclamation marks. A sentence without words can be valid, but it must contain at least 1 letter. 

For Example given String="Hello how are you today? My name is Dave. Hi." There are three sentences with the longest being 5 words.

For Example String="Hello the cat... Jumps! In the morning across the bed. Y tho?" There are 6 sentences as defined by the rules. "Hello the cat" (3 words) ""(0 words) ""(0 words) "Jumps"(1 word) "In the morning across the bed"(6 words) "Y tho"(2 words) In this case the function should return 6

Write a function of sentenceLength(String)
such that it will return the longest sentence in a string as an number.

Gotcha: Extra spaces count as words, so you must fix this. 
