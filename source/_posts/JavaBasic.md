---
title: Java Coding Basic ----- A
tags: Java Basic
category:
  - Java
  - Coding
date: 2019-09-03 23:02:07
---


After reading this post, you should be able to write simple java applications, use input and out statement and decision making statements and relational and equality operators.

# Basic Application
```bash
// First Basic Program

    public class HelloWorld
    {
        public static void main(String[] args)
        {
            System.out.printIn("Hello World");
        }/* End of Method */
    }// End of Class
```

## Symbols
1. Comment <br>
 - // 
    + point out that this line is a comment
    + Improve readability
    + Compiler ignores comments (Can be used to debug)
 - /* .... */
    + Traditional Way and can be used to comment several lines at one time
    + Start with /* and end with */
    + All text in /* ... */ will be ignored by the compiler
 - /** ... */
    + Javadoc comments.
    + Should be only comment for class, interface, method, constructor, field and always be written before them.
    + All text in /** ... */ will be ignored by the compiler but it is not working when its inside the function
    + It is support the HTML tags.
    <br><br>
    
2.  

| Operator | Operation | Order |
| :---     | :---      | :---  |
| * |Multiplication|Evaluated first(Left to right)|
| / |Division|Evaluated first(Left to right)|
| % |Remainder|Evaluated first(Left to right)|
    
| Operator | Operation | Order |
| :---     | :---      | :---  |
| + |Addition|Evaluated next (Left to right)|
| - |Subtraction|Evaluated next(Left to right)|
    
| Operator | Operation | Order |
| :---     | :---      | :---  |
| =|Assignment|Evaluated last|
 
| Algebraic Operator | Java equality or Relational operator | Sample Java condition| Meaning |
| :--- | :---| :--- | :--- |
| = | == | X == Y| x is equal to y |
| ≠ | != | X != Y| x is not equal to y|
| > | >  | X > Y | x is greater than y| 
| < | <  | X < Y | x is smaller than y| 
| ≥ | ≥  | X ≥ Y | x is greater or equal to y| 
| ≤ | ≤ |  X ≤ Y | x is smaller or equal to y| 
  
 |Operators | Associativity | Type |
 | :--- | :---| :--- |
 | * / % | Left to right| Multiplicative|
 |+ -| Left to right| Additive|
 |< <= > >=| Left to right | Relational|
 |== !=| Left to right| Equality|
 |=|Right to Left| Assignment|
 
# Steps of writing a program
- Declaring a class
- Class Body
- Declaring a Method
- Compiling

 