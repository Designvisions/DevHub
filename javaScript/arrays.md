# JavaScript Array Methods

## 1. `forEach()`
**Purpose**: Executes a provided function once for each array element.  
**Returns**: `undefined`. It does not return a new array.

**Example**:
```javascript
const numbers = [1, 2, 3];
numbers.forEach(num => console.log(num));
// Output: 1, 2, 3
```

**Usage**:  
Use `forEach()` when you need to loop through an array and perform side effects (like logging or updating).

---

## 2. `map()`
**Purpose**: Creates a new array with the results of calling a function for every array element.  
**Returns**: A new array with transformed elements.

**Example**:
```javascript
const numbers = [1, 2, 3];
const doubled = numbers.map(num => num * 2);
console.log(doubled); // Output: [2, 4, 6]
```

**Usage**:  
Use `map()` when you need to transform each element in an array and create a new array with those transformations.

---

## 3. `filter()`
**Purpose**: Creates a new array with elements that pass a test (provided by a function).  
**Returns**: A new array with elements that match the condition.

**Example**:
```javascript
const numbers = [1, 2, 3, 4];
const even = numbers.filter(num => num % 2 === 0);
console.log(even); // Output: [2, 4]
```

**Usage**:  
Use `filter()` when you need to keep only the elements that pass a certain condition.

---

## 4. `reduce()`
**Purpose**: Executes a reducer function (that you provide) on each element of the array, resulting in a single output value.  
**Returns**: A single value (e.g., a sum, product, or any other combination of array elements).

**Example**:
```javascript
const numbers = [1, 2, 3, 4];
const sum = numbers.reduce((accumulator, num) => accumulator + num, 0);
console.log(sum); // Output: 10
```

**Usage**:  
Use `reduce()` when you need to combine all elements into a single value (e.g., summing all numbers in an array).

---

## 5. `push()`
**Purpose**: Adds one or more elements to the end of an array.  
**Returns**: The new length of the array.

**Example**:
```javascript
const fruits = ['apple', 'banana'];
fruits.push('cherry');
console.log(fruits); // Output: ['apple', 'banana', 'cherry']
```

**Usage**:  
Use `push()` when you need to add new elements to the end of an array.

---

## 6. `pop()`
**Purpose**: Removes the last element from an array.  
**Returns**: The removed element.

**Example**:
```javascript
const fruits = ['apple', 'banana', 'cherry'];
const lastFruit = fruits.pop();
console.log(lastFruit); // Output: 'cherry'
console.log(fruits); // Output: ['apple', 'banana']
```

**Usage**:  
Use `pop()` when you need to remove the last element from an array.
