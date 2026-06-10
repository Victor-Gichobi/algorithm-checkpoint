# Sentence Analysis Algorithm
## Description

This algorithm reads a sentence character by character until it encounters a period (.). While reading the sentence, it calculates:

-The total number of characters (excluding the final period).
-The total number of words.
-The total number of vowels (a, e, i, o, u in both uppercase and lowercase).

## Objectives

The algorithm demonstrates:

-Character-by-character processing.
-Use of counters.
-Conditional statements.
-Looping structures.


## Variables Used
Variable	Purpose
Length	    Counts the number of characters in the sentence
Words	    Counts the number of words in the sentence
Vowels	    Counts the number of vowels in the sentence
Ch	        Stores the current character being read

## Assumptions
The sentence ends with a period (.).
Words are separated by a single space.
The sentence contains only one terminating period.

## Algorithm Logic
-Initialize the counters (Length, Words, Vowels) to zero.
-Read the sentence one character at a time.
-Stop processing when the period (.) is reached.
-Display the results.