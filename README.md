Printing a string multiple times is a common task in programming. Depending on the language, there are a few different ways to solve this problem. Here are examples in a few different languages.

# Python:
Python is an interpreted, high-level general-purpose programming language that's easy to learn and powerful to use. You use the `print()` function to print text to the console, and you can use a loop to print the text multiple times. Here is how you would do it:

```python
for _ in range(3):
    print('kekbeum')
```

In this code, '_' is a convention in Python that's used when the variable in a loop is not actually being used. 'range(3)' creates a range object with 3 elements (0, 1, 2). For each element in that range object, it's printing 'kekbeum' to the console.

# JavaScript:
JavaScript is an object-oriented language most commonly used for web development. You can print to the console using `console.log()`, and you can print multiple times using a loop. Here is how you'd do it:

```javascript
for (let i = 0; i < 3; i++) {
    console.log('kekbeum');
}
```

In this code, 'i' is a counter variable that starts at 0 and increases by 1 each time the loop runs, until it's equal to 3. Each time the loop runs, it's printing 'kekbeum' to the console. 

# Java:
Java is a class-based object-oriented programming language that's widely used for building enterprise-scale applications. You can print to the console using `System.out.println()`, and you can print multiple times using a loop. Here's how:

```java
for (int i = 0; i < 3; i++) {
    System.out.println("kekbeum");
}
```

This code is similar to the JavaScript code. The only difference is that the datatype of the counter variable 'i' needs to be declared (in this case, it's an integer), and the text to be printed needs to be in double quotes.

These examples can be easily adjusted for other programming languages as well.
