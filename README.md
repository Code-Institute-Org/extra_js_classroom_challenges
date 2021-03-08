# JavaScript Algorithm Challenges

## Suggestions for completion

1. Read the requirements several times very carefully.
2. Write down what the program should do.
3. Change what you've written into a kind of pseudo-code
4. Change the pseudo-code to actual code

## Challenge 1

Write a function that writes the multiplication table 
(in one column) of any number passed as parameter.

So, calling `multiplication_table(2)` will return:

```
2
4
6
8
10
12
14
16
18
20
```

## Challenge 2

Define a function `max()` that takes two numbers (called num1 and num2) as arguments and returns the largest of them. Use the if-else construct available in Javascript.

So, calling: `max(2,4)` will return:

```
4
```

## Challenge 3

Define a function new_max() that takes three numbers as arguments and returns the largest 
of them. Use the if / else if / else construct available in Javascript.

So, calling: `new_max(10,2,4)` will return:

```
10
```

## Challenge 4

Write a function that takes a character 
(i.e. a string of length 1) and prints a message 
to say whether the letter is a vowel or not.

So, calling `is_vowel("a")` will return:

```
true
```

Calling `is_vowel("s")` will return:

```
false
```

Use the return value to console.log a message.

## Challenge 5

Split myString on the space into an array called myArray

Iterate over checkArray using a for loop
Inside the for loop, use .indexOf to see if
the word at the current index of checkArray is in myArray

(Remember indexOf returns -1 if it can't find the word)

If the word is not in myArray, push it on to the end.

```
let myString = "Oh what a beautiful morning";

let checkArray = ["Oh", "it", "is", "beautiful", "today"];
```

## Challenge 6

Iterate over the students array backwards, and push each name onto the studentsBackwards
array.
  
Then iterate over the studentsBackwards array
normally and print out all the names.


```
let students = ["Alex", "Babu", "Brian", "Cormac", "Caoimhe", "Donal", "Femy", "Jean", "Katie", "Kira", "Neal", "Zanbo", "Zoran"];

let studentsBackwards = [];

for (let x = students.length - 1; x >= 0; x--) {
  // Code to iterate backwards...
}
```

## Challenge 7

Create an array of words that you choose.

Iterate over it, using a `for` loop

Print the result to screen

Use `.indexOf` to find a word in your array, and
print that word to screen.

## Challenge 8

Create a function called `largestNumber` that takes one argument called `numberArray`.

When an array is passed in, the function should return the largest number in the array.

Calling: `largestNumber([1,7,8,3,12,2])` should return 12.

Hint: This will require iterating through the array, using an if statement and a variable to store the largest number.

## Challenge 9

Write a JavaScript function called `sumArray` that returns the sum of numbers in an array.

So, calling: `sumArray([1,3,5,7])` will return 16,
which is 1 + 3 + 5 + 7.

## Challenge 10

Push zeroes last.

Write a JavaScript function called `pushZeroes` that takes one argument called input.

You can assume that input will be a string, but it will be a string of numbers, e.g: "30041203"

Your aim is to return a string with the zeroes pushed to the end, so calling `pushZeroes("30041203")` will return `"34123000"`

See below for hints.

**Hints**

A string can use some of the same methods as an array,
so:

```
let myString = "12345";

myString.indexOf("4");
```

will return the index of 3.

Remember that you might need to create two empty strings - one for zeroes and one for non-zero numbers

You will need to combine the strings at the end.

## Challenge 11

**DIFFICULT:** Make Bricks challenge:

Write a function called makeBricks that accepts three
arguments: `small, big, goal`.

We want to make a row of bricks that is goal inches long. We have a number of small bricks (1 inch each) and big bricks (5 inches each). Return true if it is possible to make the goal by choosing from the given bricks, and false if it is not possible. This is a little harder than it looks and can be done without any loops.

So, for example:

`makeBricks(2,1,7) = true`
`makeBricks(2,1,8) = false`
`makeBricks(3,2,12) = true`

Starter function:

```
function makeBricks(small, big, goal) {

}
```

## Challenge 12

Create a function called `cToF` that accepts one argument called `celsius`.

The function should return the value of celsius converted to Fahrenheit.

The formula to convert celsius to Fahrenheit is: (celsius * 1.8) + 32

**BONUS ROUND:**

Create another function called fToC that converts Fahrenheit back to Celsius.

**BONUS BONUS ROUND:**

Combine the two functions into one called convertTemp that takes two arguments: num and unit.

Calling: `convertTemp(32,"C")` will convert 32 Celsius to Fahrenheit.

Calling `convertTemp(101, "F")` will convert 101 Fahrenheit to Celsius.

## Challenge 13

Write some code that prompts the user for a number. And prints out a multiplication table for that number. So, if I enter 12, I should get:

```
    1 * 12 = 12
    2 * 12 = 24
    3 * 12 = 36
    ...
    10 * 12 = 120
```

The code to prompt for an input is:

`let myNumber = Number(prompt("Enter a number:"));`

## Challenge 14

Write a small piece of code that prompts you for your name. If the name is "Alice" then put up an alert to say "Hey, Alice!" otherwise create an alert that says "Hello " (name) ". It's nice to meet you."

## Challenge 15

Create an object called motorbike.

Give the object certain attributes and values
using the key/value pairs.

Give the object a boolean attribute of: `engineStarted`

Create a method inside the object to start the engine if it's stopped (false) or to stop the  engine if it's started (true).

Test using console.log()

## Challenge 16

Create a constructor function for a vehicle.

Give it vehicle attributes, so that you can create a new
vehicle of any class.

Give it an engineStarted boolean attribute.

Create a toggleEngine function that starts the engine if it's
stopped or stops the engine if it's started.

Create a soundHorn function that console.logs a message if
the function is called.

## Challenge 17

DOM challenge.

Create a HTML page containing an `<img>`, the source should be `bulb_off.gif`

Create a confirm box in JavaScript, asking "Do you want the light on?"

If the user answers OK then the light will be on. If they answer Cancel, the light will stay off.

Give the `<img>` an ID of `bulb` and use `document.getElementById` and the `.src` property to change the source to either bulb_on.gif or bulb_off.gif (images provided)

