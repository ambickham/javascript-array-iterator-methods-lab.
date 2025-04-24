
# Lecture_Notes

* Be able to write declarative / functional code as opposed to imperative code.
* `.forEach()`
* Need to put a function inside of the function

```javascript
const names = ['Ashmeeta']; // Changed to an array
names.forEach(name => {
    console.log(`${name} is a great instructor`);
});
```

---

# JavaScript Array Iterator Methods

This lab covers essential array iterator methods in JavaScript with examples for each.

---

## 1. `filter()`

**Purpose:** Returns a new array with elements that pass a test.

```javascript
const nums = [1, 2, 3, 4, 5];
const evens = nums.filter(n => n % 2 === 0); // [2, 4]
```

---

## 2. `map()`

**Purpose:** Transforms each element and returns a new array.

```javascript
const nums = [1, 2, 3];
const squared = nums.map(n => n * n); // [1, 4, 9]
```
* multiplying number * number 
* always name variable exactly what they are 

---

## 3. `sort()`

**Purpose:** Sorts the array. Can take a compare function.

```javascript
const nums = [3, 1, 2];
const sorted = nums.sort((a, b) => a - b); // [1, 2, 3]
```

---

## 4. `find()`

**Purpose:** Returns the first element that matches a condition.

```javascript
const people = [{name: 'Ashmeeta'}, {name: 'Ben'}];
const result = people.find(p => p.name === 'Ashmeeta'); // {name: 'Ashmeeta'}
```

---

## 5. `some()`

**Purpose:** Returns `true` if any element matches a condition.

```javascript
const nums = [1, 3, 5];
const hasEven = nums.some(n => n % 2 === 0); // false
```

---

## 6. `every()`

**Purpose:** Returns `true` if all elements match a condition.

```javascript
const nums = [2, 4, 6];
const allEven = nums.every(n => n % 2 === 0); // true
```

---

## 7. `findIndex()`

**Purpose:** Returns the index of the first match or -1 if not found.

```javascript
const nums = [5, 10, 15];
const index = nums.findIndex(n => n > 9); // 1
```

---

## 8. `reduce()`

**Purpose:** Reduces array to a single value.

```javascript
const nums = [1, 2, 3, 4];
const sum = nums.reduce((total, num) => total + num, 0); // 10
```

* MAP() "Take every item in this list, do something to it, and make a new list with the results."

element => {
  // element: current value
  // index: current index (optional)
  // array: the whole array (optional)
}

-->
//amaharaj04232025-----Video review not homewokr
// const names = 'Ashmeeta'
// names.forEach(name => {
//     console.log(`${names} is a great instructor')
// })
//-----END-----------

//amaharaj04232025------- Misc notes
// Filter out all "jerks" and make a "jerk-free" array named notJerks.

// const people = ['jerks', 'nice people', 'jerks', 'nice people', 'nice people'];
// const Filterpeople = people.filter((person => person !== 'jerks')) => {
//    return Element; 
// }
// console.log(Filterpeople)

// // Find only returns the first one, if you want multiple, use multiple instead. Could you also add multiple conditions 
// If Im building a gaming application, I will need to use this for. 
// findIndex is Very similar to find, except it will return a numeric index instead of value 

// ------END------------------

## Assignment Lab, #1
* Logic on track, filter() function helps to filter out specific values. 
* If a const variable is already assigned in the file, I can't declare again. 

