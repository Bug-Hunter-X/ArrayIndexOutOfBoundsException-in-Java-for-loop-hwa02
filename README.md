# Java ArrayIndexOutOfBoundsException Bug

This repository demonstrates a common error in Java: an `ArrayIndexOutOfBoundsException`. The bug arises from an off-by-one error in a `for` loop, attempting to access an array element beyond its bounds. The solution showcases the correct loop condition to prevent the exception.

## Bug Description
The provided Java code iterates through an integer array using a `for` loop.  The loop condition incorrectly uses `i <= arr.length`, causing an attempt to access an index that is out of the array's bounds. This results in an `ArrayIndexOutOfBoundsException` at runtime.

## Solution
The solution modifies the `for` loop's condition to `i < arr.length`. This ensures the loop iterates only within the valid indices of the array, avoiding the exception.