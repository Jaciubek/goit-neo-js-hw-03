## goit-neo-js-hw-03


## Task 1. Slug generator


Write a function slugify(title) that takes an article title as the parameter title and returns a slug created from this string.

The parameter title will be a string with words separated only by spaces.
All characters in the slug must be lowercase.
Hyphens must separate all words in the slug.
After declaring your function, use the code below to check its correctness. The console will display the execution results.


console.log(slugify("Arrays for begginers")); // "arrays-for-begginers"
console.log(slugify("English for developer")); // "english-for-developer"
console.log(slugify("Ten secrets of JavaScript")); // "ten-secrets-of-javascript"
console.log(slugify("How to become a JUNIOR developer in TWO WEEKS")); // "how-to-become-a-junior-developer-in-two-weeks"


## Task 2. Array composition


Write a function called makeArray that takes three parameters: firstArray (array), secondArray (array), and maxLength (number). The function should create a new array that contains all elements from firstArray, followed by all elements from secondArray.


If the number of elements in the new array exceeds maxLength, the function should return a copy of the array with a length of maxLength elements.
Otherwise, the function should return the entire new array.


Take the code below and paste it after declaring your function to check its correctness. The results of its operation will be output to the console.


console.log(makeArray(["Mango", "Poly"], ["Ajax", "Chelsea"], 3)); // ["Mango", "Poly", "Ajax"]
console.log(makeArray(["Mango", "Poly", "Houston"], ["Ajax", "Chelsea"], 4)); // ["Mango", "Poly", "Houston", "Ajax"]
console.log(makeArray(["Mango"], ["Ajax", "Chelsea", "Poly", "Houston"], 3)); // ["Mango", "Ajax", "Chelsea"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 2)); // ["Earth", "Jupiter"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus"], 4)); // ["Earth", "Jupiter", "Neptune", "Uranus"]
console.log(makeArray(["Earth", "Jupiter"], ["Neptune", "Uranus", "Venus"], 0)); // []


## Task 3. Filtering an array of numbers


Write a function filterArray(numbers, value) that takes an array of numbers (numbers) and a value (value) as parameters. The function should return a new array containing only those numbers from the numbers array that are greater than the value.


Inside the function:

Create an empty array to store suitable numbers.
Use a loop to iterate through each element of the numbers array.
Use an if statement inside the loop to check each element and add it to your array.
Return your new array of suitable numbers as a result.


Take the code below and paste it after declaring your function to check its correctness. The results of its operation will be output to the console.


console.log(filterArray([1, 2, 3, 4, 5], 3)); // [4, 5]
console.log(filterArray([1, 2, 3, 4, 5], 4)); // [5]
console.log(filterArray([1, 2, 3, 4, 5], 5)); // []
console.log(filterArray([12, 24, 8, 41, 76], 38)); // [41, 76]
console.log(filterArray([12, 24, 8, 41, 76], 20)); // [24, 41, 76]