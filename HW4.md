## Objective:
To demonstrate your understanding of the Stack data structure and its versatility in handling different data types.

## Description:

You are required to create a Java program that performs various operations on stacks of different data types: String, Integer, Boolean, and Double.

**Create Stacks:** Initialize four separate stacks:
- ```stringStack``` to store Strings.
- ```integerStack``` to store Integers.
- ```booleanStack``` to store Booleans.
- ```doubleStack``` to store Doubles.
- ```itemStack``` to store Item objects.

**Push Operations:**
- Push the following Strings into ```stringStack```: "Hello", "World", "Java".
- Push the following Integers into ```integerStack```: 10, 20, 30.
- Push the following Booleans into ```booleanStack```: true, false, true.
- Push the following Doubles into ```doubleStack```: 1.1, 2.2, 3.3.
- Push the following Item objects into ```itemStack```: Item("Item1",100), Item("Item2", 200), Item("Item3", 300)

**Peek and Pop Operations:**
- Peek and print the top element of each stack without removing it.
- Pop and print the top element from each stack, removing it from the stack.
- Repeat the peek and pop operations until each stack is empty.

**Empty Check:** After all pop operations, check if each stack is empty and print the result (true or false).

## Output:
```
String Stack Operations:
Peek: Java
Pop: Java
Peek: World
Pop: World
Peek: Hello
Pop: Hello

Integer Stack Operations:
Peek: 30
Pop: 30
Peek: 20
Pop: 20
Peek: 10
Pop: 10

Boolean Stack Operations:
Peek: true
Pop: true
Peek: false
Pop: false
Peek: true
Pop: true

Double Stack Operations:
Peek: 3.3
Pop: 3.3
Peek: 2.2
Pop: 2.2
Peek: 1.1
Pop: 1.1

Item Stack Operations:
Peek: Item{name='Item3', value=300}
Pop: Item{name='Item3', value=300}
Peek: Item{name='Item2', value=200}
Pop: Item{name='Item2', value=200}
Peek: Item{name='Item1', value=100}
Pop: Item{name='Item1', value=100}

Empty Stack Check:
String Stack Empty: true
Integer Stack Empty: true
Boolean Stack Empty: true
Double Stack Empty: true
Item Stack Empty: true
```
