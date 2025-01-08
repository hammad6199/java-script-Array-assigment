# JavaScript Array Manipulation Example

This repository demonstrates basic array manipulation techniques in JavaScript. The code focuses on managing a `toDoList` array using commonly used methods like `push`, `unshift`, `pop`, and `shift`. It is designed for beginners learning JavaScript arrays.

---

## Features
- **Add Elements**: Use `push` and `unshift` to add elements to the array.
- **Remove Elements**: Use `pop` and `shift` to remove elements from the array.
- **Understand Behavior**: Learn how these methods work and how they modify the array.

---

## Code Example
Here is a snippet of the provided code:

```javascript
var toDoList = [];
toDoList.push("take breakfast", "Do exercise", "learning");
toDoList.unshift("take shower", "brush the teeth");
console.log(toDoList);

toDoList.pop(); // Removes the last element
console.log(toDoList);

toDoList.shift(); // Removes the first element
console.log(toDoList);
```

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/Zaid-Baluch/Array-Methods
   ```
2. Open the JavaScript file in your code editor.
3. Run the file in a browser console or using Node.js to see the array manipulations in action.

---

## Array Methods Used
### `push()`
Adds one or more elements to the end of an array.
```javascript
toDoList.push("new task");
```

### `unshift()`
Adds one or more elements to the beginning of an array.
```javascript
toDoList.unshift("another task");
```

### `pop()`
Removes the last element of an array.
```javascript
toDoList.pop();
```

### `shift()`
Removes the first element of an array.
```javascript
toDoList.shift();
```

---

## Contributions
Contributions are welcome! If you want to add examples or improve the documentation, feel free to submit a pull request.

---


