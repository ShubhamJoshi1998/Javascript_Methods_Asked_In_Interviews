# Javascript_Methods_Asked_In_Interviews

# tostring() Method:
 toString() method converts an array to a string of array Values

let arr = ["a","b","c","d","e"];
console.log("toString() : ", arr.toString());

# join method()
 join() method is same as toString() method, but we can specify a seprator also.It can be anything like ", / + -"
let arr1 = ["a","b","c","d","e"];
console.log("join() : ", arr.join("/"))

# pop() method
 pop() method removes the last element from an array.
//This method returns the value that was popped out.
let arr2 = ["a","b","c","d","e"];
console.log(arr2.pop());
console.log(arr2);

// push() method()
//push() method add a new element in the array.
//This method returns the length of array

let arr3 = ["a","b","c","d","e"];
console.log(arr3.push("f"));
console.log(arr3);

//shift() method
// shift() method is same as pop(), but it removes the first element instead of last.
//This method returns the value that was shift out.
let arr4 = ["a","b","c","d","e"];
console.log(arr4.shift());
console.log(arr4);

//unshift() method
// unshift() method is same a push(), but it adds a new element in the array at first
//This method returns the length of array.
let arr5 = ["a","b","c","d","e"];
console.log(arr5.unshift("f"));
console.log(arr5);

// delete() method
//Array elements can be deleted using javascript operator delete.This method returns true
//Deleting elements leaves undefined holes in the array.
let arr6 = ["a","b","c","d","e"];
console.log(delete arr6[0]);
console.log(arr6);


//concat() method
//concat() method returns a new array by merging existing array.
// This method does not change the existing array.It always returns a new array.
let arr7 = ["a","b","c"];
let arr8 = ["d","e"];
console.log(arr7.concat(arr8));

