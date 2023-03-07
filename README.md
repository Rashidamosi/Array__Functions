
  # Arrays & Functions
𝘍𝘰𝘳 𝘵𝘩𝘪𝘴 𝘢𝘴𝘴𝘪𝘨𝘯𝘮𝘦𝘯𝘵, 𝘤𝘳𝘦𝘢𝘵𝘦 𝘢 𝘧𝘰𝘭𝘥𝘦𝘳 𝘢𝘯𝘥 𝘯𝘢𝘮𝘦 𝘪𝘵 𝘢𝘳𝘳𝘢𝘺𝘴-𝘧𝘶𝘯𝘤𝘵𝘪𝘰𝘯𝘴. 𝘊𝘳𝘦𝘢𝘵𝘦 𝘢𝘯 ‘𝘪𝘯𝘥𝘦𝘹.𝘫𝘴’ 𝘧𝘪𝘭𝘦 𝘢𝘯𝘥 𝘱𝘶𝘵 𝘢𝘭𝘭 𝘺𝘰𝘶𝘳 𝘢𝘯𝘴𝘸𝘦𝘳𝘴 𝘪𝘯 𝘵𝘩𝘦𝘳𝘦. 𝘚𝘦𝘱𝘢𝘳𝘢𝘵𝘦 𝘺𝘰𝘶𝘳 𝘢𝘯𝘴𝘸𝘦𝘳𝘴 𝘶𝘴𝘪𝘯𝘨 𝘤𝘰𝘮𝘮𝘦𝘯𝘵𝘴. 𝘗𝘶𝘴𝘩 𝘺𝘰𝘶𝘳 𝘸𝘰𝘳𝘬 𝘪𝘯𝘵𝘰 𝘢 𝘎𝘪𝘵𝘩𝘶𝘣 𝘳𝘦𝘱𝘰𝘴𝘪𝘵𝘰𝘳𝘺 𝘢𝘯𝘥 𝘴𝘶𝘣𝘮𝘪𝘵 𝘵𝘩𝘦 𝘎𝘪𝘵𝘩𝘶𝘣 𝘳𝘦𝘱𝘰𝘴𝘪𝘵𝘰𝘳𝘺 𝘭𝘪𝘯𝘬 𝘪𝘯 𝘊𝘪𝘵𝘳𝘰𝘯𝘦.



##  Questions

🛠 Question  1

What are the differences between mutating array methods and non-mutation array methods in JavaScript. List 5 array methods that fall under each of them.

### 🚀 Answer
Mutation in context of JavaScript arrays is basically changing the array itself instead of returning a new array with the new changes.

Examples of 5 Array methods that fall under mutating are:
- array.pop()
- array.splice()
- array.unshift()
- array.reverse()
- array.sort()

Non-Mutation is returning a whole new array which has all the changes.

Examples of 5 Array methods that fall under mutating are:
-  array.concat()
- array.indexOf
- array.toString()
- array.join()
-  array.toLocaleString()

### 🛠 Question  2
Here is an array of languages: [‘C#’, ‘JavaScript’, ‘Ruby’, ‘PHP’, ‘Python’]. Perform this operation on them 
Add ‘Kotlin’ to the end of the array
Add ‘Java’ after ‘Ruby’
Remove the first item in the array
Add ’Scala’ and ‘Swift’ to the beginning of the array
Replace ‘PHP’ with ‘Go’ and ‘Rust’

### 🛠 Question 3

What will be the value of fruit after calling the function changeFruit?
let fruit = ['apple', 'mango', 'banana'];
		function changeFruit( fruit ) {
    			fruit[2] = "orange";
    			return fruit;
		}

### 🛠 Question 4
Write a function that accepts an array of numbers as an argument. Return the maximum value in the array.
e.g., max([4, 5, 10, -2]) // maximum value is 10

### 🛠 Question 5
Write a function called valTimesIndex which accepts an array of numbers and returns a new array with each value multiplied by the index it is at in the array:
e.g.,
 valTimesIndex([1,2,3]) // [0,2,6]
		valTimesIndex([5,10,15]) // [0,10,30]