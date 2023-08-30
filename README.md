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
 pop() method removes the last element from an array.This method returns the value that was popped out.
 
let arr2 = ["a","b","c","d","e"];

console.log(arr2.pop());

console.log(arr2);

# push() method()
push() method add a new element in the array. This method returns the length of array

let arr3 = ["a","b","c","d","e"];

console.log(arr3.push("f"));

console.log(arr3);

# shift() method
shift() method is same as pop(), but it removes the first element instead of last. This method returns the value that was shift out.

let arr4 = ["a","b","c","d","e"];

console.log(arr4.shift());

console.log(arr4);

# unshift() method
unshift() method is same a push(), but it adds a new element in the array at first This method returns the length of array.

let arr5 = ["a","b","c","d","e"];

console.log(arr5.unshift("f"));

console.log(arr5);

# delete() method
Array elements can be deleted using javascript operator delete.This method returns true. Deleting elements leaves undefined holes in the array.

let arr6 = ["a","b","c","d","e"];

console.log(delete arr6[0]);

console.log(arr6);

# concat() method
concat() method returns a new array by merging existing array. This method does not change the existing array.It always returns a new array.

let arr7 = ["a","b","c"];

let arr8 = ["d","e"];

console.log(arr7.concat(arr8));

# splice() method
splice method is used to change the contents of an array by removing, replacing and adding new element at the specified index.

SYNTAX : array.splice(start, deleteCount, item1, item2, ...);

This method returns the deleted elements.

let arr9 = [ 'a', 'b', 'c', 'd' ];

let arrsplice = arr9.splice(1,2,"e","f");

console.log(arr9);

console.log(arrsplice);

# slice() method
slice method extracts a section of an array into a new array.It does not modify the existing array.

SYNTAX : array.slice(start, end);

let arr10 = [ 'a', 'b', 'c', 'd','e','f' ];

console.log(arr10.slice(1,4));

# spread operator
spread operator expands an array into its individual elements.

let arr11 = [ 'a', 'b', 'c', 'd' ];

console.log("spread operator",...arr11);

# for of operator
This method iterates through the collection, and provides you the ability to modify specific items.

let arr12 = [ 'a', 'b', 'c', 'd' ];

for(const item of arr12){

    console.log("for of operator",item)
    
}

# map() method
This method creates a new array with the result of calling a providing function on every elements in the array.

let arr13 = [1,2,3,4,5];

console.log(arr13.map(ele =>ele + 30));

# filter() method
This method creates a new array with only elements that passes the condition inside the providing function.

let arr14 = [1,2,3,4,5];

console.log(arr14.filter(ele => ele<=4));


# sort() method
This method is used to sort array's element either in ascending or descending order.

let arr15 = [4,2,5,1,3];

console.log(arr15.sort((a,b) => a>b ? 1:-1)); //ascending.

console.log(arr15.sort((a,b) => a>b ? -1:1)); //descending.


