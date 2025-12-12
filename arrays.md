# Arrays declaration
```Javascript
const arr = [];
const arr = [2, 14, 'abc', true, {}, [], 23]; //tuple
const arr = new Array(2, 14, 'abc', true, {}, [], 23);
const arr = Array(2, 14, 'abc', true, {}, [], 23);

string.split('', 3);
[...string]; //spread
Array.from(string); //method
str.split('; ', 3) //(devider, number of elements)
arr.slice(); //without parametrs makes array copy;
```

# Arrays iteration
```Javascript
for (let i = 0; i < arr.length; i++) {
    arr[i];
}

for (const n of arr) {
    n
}
```

# Array to string
```Javascript
arr.join(' ');
```
# Get array's element by ID
```Javascript
arr[0];
arr[4]; // if index too big or negative => undefined
arr.at(0); //the same
```

# Reassign value
```Javascript

MUTATING METHODS:
arr.push(45, 46, 47); // add one or multiply elements to end of array. Return length of array.
arr.unshift(45, 46, 47); // add one or multiply elements to begining of array. Return lenght of array.
const n = arr.pop(); // remove last element and assign it to variable
const n = arr.shift() // remove first element of array
arr.fill('a', 2, 5); //replace all elements with value in brackets from to indexes
arr.reverse(); //
arr.sort();

arr[0] = 45; //array can contain gap
arr[arr.length] = 45; //exectly in the end

```

# Find element in array
```Javascript
UNMUTATING METHODS:
arr.includes('str', 3); // second value is position to start search
arr.indexOf('element', 3) // second value is position to start search
arr.lastIndexOf('element', 3) // second value is position to start search
arr.splice(1, 2, ...newArr) //return 2 elements starting from 1 index
arr.concat(100, [x, y[900]], 200, 300); //Without values makes copy of array
str.slice(2, -2); // returns aray sliced by values. Without values makes copy of array
Array.from(arr); // Makes copy of array. May use string as argument
[...arr.slice(0, 2),
100,
200,
300,
...arr.slice(2),
] //                    spread operator
```
```Javascript

```
```Javascript

```
```Javascript

```
```Javascript

```
