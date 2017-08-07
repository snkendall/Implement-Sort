# Implement-Sort
My solution to the final workshop problem in Bootcamp Prep

Prompt: 
Implement Sort

Write a function mySort that accepts an array and a callback function that is used to create a sorted copy of the array. Try to mirror the functionality of the native .sort() array method as closely as possible.

To start with, do not worry about implementing a default sort the way the native .sort() method does. Work on that as a bonus.

Remember, your mySort function should change the array passed in as an argument, and return that array.

function greaterThan(num1, num2) { return num1 > num2 }

var arr = [5,2,3,1,4];
var sortedArr = mySort(arr, greaterThan);

console.log(sortedArr)    // [1,2,3,4,5]
console.log(arr)    // [1,2,3,4,5]
