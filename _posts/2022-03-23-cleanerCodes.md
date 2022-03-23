---
Layout:
Title:  CleanerCodes
date:   2022-03-23
Categories:

---

# What Happened?
As planned, I worked to learn and continue pushing the functional programming, however, I could not reach the goal of beginning with my project today, but I understood what I was faced with today, which is a victory for me over javaScript.

# The Day?
Pretty good day, always a good day when I am able to cope with my tasks and problems given in the syllabus of freeCodeCamp and although I didn't reach my goal, I managed the time I had very well.

# What Did You Learn?
## Splice Method
- When you want to remove items and keep the rest of the array.
- Mutates the original array unlike previous methods mentioned.
- The code is as follows:
```
array.splice(indexToBeginRemove, numberOfItemsToRemove);
```
## Concat Method
Concatenation
- To join items end to end.
- This method works for both strings and arrays
- Does not mutate any original array, code is as following:

```
[1, 2, 3].concat([4, 5])

//returned array would be
[1, 2, 3, 4, 5]
```

## Reduce Method
This method iterates over eah item in an array and returns a single value which can be string or number or array, etc...
- This is achieved via callback function that is called on each iteration, code is as follows:

```
arr.reduce()
```

## Sort Method
- Sorts the elements of an array according to the callback function. That is all I understand with this method, freeCodeCamp didn't really explain it in a way that I understand.
## Split Method
- This method spits a string into an array of strings into an array of strings, code is as follows:

```
const str = 'Hello dave';
const splitStr = str.split(' ');

//Our output would be:
['Hello', 'dave']

//However if our declaration was:
const splitStr2 = str.split('');  //no space

//Our output would be:
['H', 'e', 'l', 'l', 'o', 'd', 'a', 'v', 'e']
```

## Join Method
- This method is the opposite of the split method, it join the elements of an array together to create a string.

# Plan?
Tomorrow I work on the project and I will see freeCodeCamp later!!