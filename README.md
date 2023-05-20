# What is array
    An array is an object that holds values (of any type) not particularly in named properties/keys,
    but rather in numerically indexed position
    In JavaScript, an array is an ordered list of values. Each value is called an element specified by
    an index. ... First, an array can hold values of mixed types.
    An array is a special variable, which can hold more than one value:
    ex:
    let arr = [1, 2, 3, 'hi', true [2, 4, 'bye'],7]

You can also add elements or change the elements by accessing the index value
Suppose, an array has two elements. If you try to add an element at index 3 (fourth
element), the third element will be undefined. For example,

let arr = [1, 2, 3]

arr[4] = 4

console.log(arr) // 1, 2, 3, <1 empty item>, 4

# array methods
1. pop()
1. shift()
1. push()
1. unshift()
1. concat()
1. slice()
1. forEach()
1. map()
1. find()
1. filter()
1. reduce()
1. toSorted()
1. join()
1. includes()
1. indexOf()
1. splice()
1. toString()
1. toReversed()

# push 
The push() method adds one or more elements to the end of an array and returns the
new length of the array.
The element(s) to add to the end of the array.
Syntax: push(element0, element1, /* … ,*/ elementN)
# pop
The pop() method removes the last element from an array and returns that element.
This method changes the length of the array.
Syntax: pop()

# unshift
The unshift() method adds one or more elements to the beginning of an array and
returns the new length of the array.
unshift(element0, element1, /* … ,*/ elementN)

# shift 
The shift() method removes the last element from an array and returns that element.
This method changes the length of the array. 
Syntax: shift()

# toString
The toString() method returns a string representing the specified array and its
elements.
A string representing the elements of the array.
Syntax: toString() 

# Javascript array methods
# indexof
 ![Tux, the Linux mascot](/images/indexof().png)

# includes
![Tux, the Linux mascot](/images/includes().png)

# slice 
![Tux, the Linux mascot](/images/slice().png)

#concat()
![Tux, the Linux mascot](/images/concat().png)

# splice
![Tux, the Linux mascot](/images/splice().png)

# array methods callbacks

# map
![Tux, the Linux mascot](/images/map().png)

# forEach
![Tux, the Linux mascot](/images/forEach().png)

# find
![Tux, the Linux mascot](/images/find().png)

# reduce
The reduce() method executes a user-supplied "reducer" callback function on each element
of the array, in order, passing in the return value from the calculation on the preceding
element. The final result of running the reducer across all elements of the array is a single
value.

![Tux, the Linux mascot](/images/reduce.png)

# filter
The filter() method creates a shallow copy of a portion of a given array, filtered down to
just the elements from the given array that pass the test implemented by the provided
function. 

![Tux, the Linux mascot](/images/filter.png)

# toSorted
The toSorted() method of Array instances is the copying version of the sort() method.
It returns a new array with the elements sorted in ascending order.

![Tux, the Linux mascot](/images/toSorted.png)

# Destructuring
The destructuring assignment syntax is a JavaScript expression that makes it
possible to unpack values from arrays, or properties from objects, into distinct
variables.

![Tux, the Linux mascot](/images/destructuring.png)

# spread
The spread (...) syntax allows an iterable, such as an array or string, to be
expanded in places where zero or more arguments (for function calls) or
elements (for array literals) are expected. In an object literal, the spread syntax
enumerates the properties of an object and adds the key-value pairs to the object
being created.

![Tux, the Linux mascot](/images/spread.png)

# rest
The rest parameter syntax allows a function to accept an indefinite
number of arguments as an array.

![Tux, the Linux mascot](/images/rest.png)

# THANKS