# reduce code kata
code kata from 04.12.2018

In this kata, you must define the Array.reduce method.

Here's how it works:

[1,2,3].reduce( function(sum, next){return sum+next}, 0)
// => 6

['a','b','a'].reduce( function(obj, elem){if(!obj[elem]) obj[elem] = 0; obj[elem] += 1; return obj}, {})
// => {'a':2, 'b':1}

Summary: The reduce method goes through each element of an array, applies the function to whatever the function returned last, and returns the last outcome. On the first iteration, it should pass the initial value to the function, as well as the first element of the array. If no initial value is passed, skip to the first element of the array.

https://www.codewars.com/kata/array-number-reduce

