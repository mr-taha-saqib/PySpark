# Python and PySpark Exercises

This repository contains solutions to various Python and PySpark exercises. Below are the details of each exercise:

## Exercise 1: Square Elements in a List
1. Create `my_list` which contains numbers from 1 to 10. Print the list.
2. Square each item in `my_list` using `map()` and `lambda()`.
3. Print the result of the `map` function.

## Exercise 2: Filter Numbers Divisible by 5
1. Create `my_list_2` which contains 20 random numbers. Print the list.
2. Filter the numbers divisible by 5 from `my_list_2` using `filter()` and `lambda()`.
3. Print the numbers divisible by 5 from `my_list_2`.

## Exercise 3: Create RDD from a List of Words
1. Create an RDD named `RDD` from a list of words (created manually).
2. Confirm the object created is an RDD.

## Exercise 4: Create RDD from an Input File
1. Create an RDD named `fileRDD` from a given input file.
2. Print the type of the `fileRDD` created.

## Exercise 5: Working with Partitions
1. Find the number of partitions that support `fileRDD`.
2. Create an RDD named `fileRDD_part` from the input file with 5 partitions.
3. Confirm the number of partitions in the new `fileRDD_part` RDD.

## Exercise 6: Cube Numbers in an RDD
1. Create a `map()` transformation that cubes all the numbers in `numbRDD`.
2. Collect the results into a variable named `numbers_all`.
3. Print the output from the `numbers_all` variable.

## Exercise 7: Filter Lines Containing a Keyword
1. Create a `filter()` transformation on an RDD which reads the input file to select lines containing the keyword **beautiful**.
2. Find out how many lines in `fileRDD_filter` contain the keyword **beautiful**.
3. Print the first four lines of the resulting RDD.

## Exercise 8: Print Words Separately Using `flatMap()`
1. Read a string into a list and store it in an RDD.
2. Print each word separately using `flatMap()`.

## Exercise 9: Find the Highest Number in a List
1. Create a list of ten random numbers.
2. Find the highest number from the list.

## Exercise 10: Compare Two Lists and Find Matching Elements
1. Store two lists of names in RDDs.
2. Compare the two RDDs to find matching elements.
3. Print the matching elements of the lists.
