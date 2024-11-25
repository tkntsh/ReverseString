# ReverseString Java Program

This Java program demonstrates how to reverse a given string using the `StringBuilder` class. It showcases the simplicity and efficiency of using built-in Java methods for string manipulation.

---

## File

### **ReverseString.java**
- **Purpose**: Reverses a given string and outputs the result to the console.
- **Features**:
  - Uses the `StringBuilder` class to reverse a string.
  - Converts the reversed result back to a `String` for output.
  - Provides a simple and clear example of string manipulation in Java.

---

## How It Works

1. A string (`original`) is defined with the value `"Impact"`.
2. The `StringBuilder` class is used to reverse the string:
   - `new StringBuilder(original)` creates a mutable sequence of characters.
   - `.reverse()` reverses the sequence of characters.
   - `.toString()` converts the reversed sequence back to an immutable `String`.
3. The reversed string is printed to the console.

---

## Example Input & Output

### Input
```java
String original = "Impact";
