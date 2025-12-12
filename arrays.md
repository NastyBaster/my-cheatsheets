# Arrays declaration
```Javascript
const arr = [];
const arr = [2, 14, 'abc', true, {}, [], 23]; //tuple
const arr = new Array(2, 14, 'abc', true, {}, [], 23);
const arr = Array(2, 14, 'abc', true, {}, [], 23);

string.split('');
[...string]; //spread
Array.from(string); //method
str.split('; ', 3) //(devider, number of elements)
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
arr[0] = 45; //array can contain gap
arr[arr.length] = 45; //exectly in the end
arr.push(45, 46, 47); // add one or multiply elements to end of array
const n = arr.pop(); // remove last element and assign it to variable
arr.unshift(45, 46, 47); // add one or multiply elements to begining of array
const n = arr.shift() // remove first element of array
```

# Find element inarray
```Javascript
arr.includes('str', 3); // second value is position to start search
arr.indexOf('element', 3) // second value is position to start search
arr.lastIndexOf('element', 3) // second value is position to start search
```
```Javascript

```
```Javascript

```
```Javascript

```
```Javascript

```
