# Lab22-Changing-Arrays
# NumberArrays Class Assignment

## Overview
The goal of this assignment is to create a class called `NumberArrays` that operates on an integer array and implements various methods to manipulate and analyze the array. Below are the detailed specifications for the class and its methods.

---

## Class Structure

### Instance Variable
- `int[] array`: An integer array representing the data structure for the class.

---

## Constructor

### `public NumberArrays(int size)`
- Initializes the `array` instance variable with a length of `size`.
- Each element in the array should be a random integer between 0 and 100 (inclusive).

---

## Methods

### `public boolean atLeastOneOdd()`
- **Description**: Determines if there is at least one odd number in the array.
- **Return Type**: `boolean`
  - **Postcondition**: Returns `true` if at least one odd number exists, otherwise `false`.

### `public void reverseArray()`
- **Description**: Reverses the order of the elements in the `array`.
- **Return Type**: `void`
  - **Postcondition**: The original `array` is modified in-place to be in reverse order.

### `public void shiftRight()`
- **Description**: Shifts each element in the `array` one position to the right. The last element wraps around to the first position.
- **Return Type**: `void`
  - **Postcondition**: The original `array` is modified in-place to reflect the shifted values.

### `public void shiftLeft()`
- **Description**: Shifts each element in the `array` one position to the left. The first element wraps around to the last position.
- **Return Type**: `void`
  - **Postcondition**: The original `array` is modified in-place to reflect the shifted values.

### `public boolean duplicate()`
- **Description**: Determines if there are any duplicate values in the `array`.
- **Return Type**: `boolean`
  - **Postcondition**: Returns `true` if duplicate values exist, otherwise `false`.

### `public int mode()`
- **Description**: Finds the mode of the `array`, which is the number that appears most frequently. If there are multiple modes, returns the smallest.
- **Return Type**: `int`
  - **Postcondition**: Returns the mode of the `array`; that is, the number that occurs most frequently.  If there are multiple modes, return the smallest.
  
  ( Note: this requires a multi-counter tally solution as discussed in class.  )

---

## Documentation Requirements
Each method must include documentation describing:
1. **What the method does**.
2. **Preconditions** for any parameters (if applicable).
3. **Postconditions** for the return value (if applicable).

Note - the headers have been provided for you above.
---

## Testing
- Write tests to validate the functionality of each method.
- Ensure the methods are tested thoroughly before submission.
- Your class will be graded using a tester program.

---

## Submission Instructions
Submit the `NumberArrays` class implementation along with your tester code. Ensure all methods are documented as required.
