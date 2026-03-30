## Introduction to java

## Language :- 
Language is a medium through which we will communicate with ohter entities.
## what is programming language ?
programming language is a medium to communicate with systems or language which is use to communicate with system is known as programmiong langugae

### There are three types of programming language
- Low level or Machine understandable
- Mid level or Assembly level
- High level or Human Understandable

# Java
It is a object oriented high level language which is used to create software to make human life easier

# Features of java
- It is highly secure (because concept of pointer is not there)
- Platform independent
- Strictly typed or Static typed (because of datatype)
- It supports object oriented programming
- It has garbage collector
- Multithreaded
- Both compiled as well as interpreted langugae

# How to execute a Java program
- we need to install JDK in our system
- create a source file inside which source code will be written & save it with a ".java" extension
- pass the source file to the compiler, so it can check the syntax & generate byte code
- pass the byte code to the jvm in order to execute the file

# JDK :-
It stands for java development kit, it gives us tools in order to convert our system in such way that java can execute easily

# compiler :-
It is software tool which is responsible to check the syntax of the code(way of writing) and generate .class file which contains byte code. it present inside the jvm.

# JRE :-
It stands for java runtime enviroment which allows java to be executed inside the enviroment.

# In built libraries :-
These sre pre-defined code which are present inside the java, it helps us to perform various operations.

# JVM :-
It stands for java virtual machine, which perform the operations---
- Converting the byte code into binary
- Executre them line by line

# JIT compiler :- 
It stands for just in time compiler which boost the speed of the execution as well as convert byte code into bynary code.

# Interpreter :-
It execute code line by line

# Byte code :-
it is an intermidiate language which is neither understandable by machine nor by hummans.



# Java Tokens — Notes

## What is a Token?
The smallest individual unit in a Java program is called a Token.
When the Java compiler reads your code, it breaks it into tokens first.

## Types of Tokens in Java

There are 5 types of tokens in Java:
1. Keywords
2. Identifiers
3. Literals
4. Operators
5. Separators

---

## 1. Keywords
- Reserved words that have a special meaning in Java
- Cannot be used as variable names or class names
- Always written in lowercase

Examples:
int, float, double, char, boolean, byte, short, long,
if, else, switch, case, break, default,
for, while, do,
class, public, private, protected, static, void, final,
new, return, this, super, extends, implements,
try, catch, finally, throw, throws,
true, false, null

---

## 2. Identifiers
- Names given to variables, methods, classes, objects etc.
- Created by the programmer

### Rules for Identifiers:
- Can contain letters, digits, _ (underscore), $ (dollar sign)
- Cannot start with a digit
- Cannot be a keyword
- Java is case sensitive — age and Age are different

### Examples:
Valid:   name, age, _count, $price, myMethod, HelloWorld
Invalid: 1name, int, my-name, hello world

---

## 3. Literals
- Fixed values directly written in the code

| Type | Example |
|------|---------|
| Integer Literal | 10, 200, -50 |
| Float Literal | 3.14f, 99.5f |
| Double Literal | 3.14159, 99.99 |
| Char Literal | 'A', 'z', '9' |
| String Literal | "Hello", "Soubhik" |
| Boolean Literal | true, false |
| Null Literal | null |
```java
int age = 21;           // 21 is an integer literal
double price = 99.99;   // 99.99 is a double literal
char grade = 'A';       // 'A' is a char literal
String name = "Soubhik";// "Soubhik" is a string literal
boolean flag = true;    // true is a boolean literal
```

---

## 4. Operators
- Symbols that perform operations on variables and values

| Type | Operators | Example |
|------|-----------|---------|
| Arithmetic | + - * / % | a + b |
| Relational | == != > < >= <= | a > b |
| Logical | && \|\| ! | a && b |
| Assignment | = += -= *= /= | a = 10 |
| Increment/Decrement | ++ -- | a++ |
| Ternary | ?: | a > b ? a : b |

---

## 5. Separators
- Symbols used to separate or group parts of code

| Separator | Symbol | Usage |
|-----------|--------|-------|
| Parentheses | () | method calls, conditions |
| Curly Braces | {} | code blocks, class/method body |
| Square Brackets | [] | arrays |
| Semicolon | ; | end of statement |
| Comma | , | separating variables |
| Dot | . | accessing methods/variables |
```java
public class Demo {           // { is a separator
    public static void main(String[] args) {  // () and [] are separators
        int a = 10, b = 20;   // , is a separator
        System.out.println(a); // . and () and ; are separators
    }                         // } is a separator
}
```

---

## Quick Summary

| Token | Description | Example |
|-------|-------------|---------|
| Keyword | Reserved word | int, class, if |
| Identifier | Name given by programmer | age, myMethod |
| Literal | Fixed value | 10, 'A', "Hello" |
| Operator | Performs operation | + - * / |
| Separator | Separates code units | ; , () {} |
