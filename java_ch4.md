
Java Chapter 4: Class Notes:
===

-Test This Week


BID - B02226409 

Relational Operators in Java
table 4-1


|Operator | Descripton|
|--|--|
|== | Equal to|
|!= | not equal to|
|< |less than|
|<= |less than or equal to|
|>| greater than|
|>= | greater than or equal to|

! - Not && and || or

|Unicode Value|Character|Unicode Value|Character|Unicode Value|Character|Unicode Value|Character|
|--|--|--|--|--|--|--|--|
|32|''|61|=|81|Q|105|i|
|33|!|62|>|82|R|106|j|
|34|"|65|A|83|S|107|k|
|42|*|66|B|84|T|108|l|
|43|+|67|C|85|U|109|m|
|45|-|68|D|86|V|110|n|
|47|/|69|E|87|W|111|o|
|48|0|70|F|88|X|112|p|
|49|9|71|G|89|Y|113|q|
|50|2|72|H|90|Z|114|r|
|51|3|73|I|97|a|115|s|
|52|4|74|J|98|b|116|t|
|53|5|75|K|99|c|117|u|
|54|6|76|L|100|d|118|v|
|55|7|77|M|101|e|119|w|
|56|8|78|N|102|f|120|x|
|57|9|79|O|103|g|121|y|
|60|<|80|P|104|h|122|z|




Example:
|Expression |Value of Expression| Explaination|
|---|---|---|
|'' < 'a' | True|'' = 32, value of 'a' = 97.|

##Example 4-4 will probably not be on the exam. (the one below)
|Operator|Description|
|--|--|
|!|not|
|&&|and|
|\|\||or|


#pg. 21
One-Way Selection
- Syntax
    ```
    if (expression)
        statement
        or
    if(x > 10)
        x=12;
        y=5;
    ```

## **Hint hint - if statements will be on the final. 
```
    if(x > 10)
        x=12;
        y=5; // always execute.

    vs.

    if(x>10)
       { x=12; // x = more
        y=5;  // therefore the next line is true.
        }
```

| Expression 1  |Expression2   |Expression1 && Expression2  |
|---|---|---|
|true|false|true|
|true|false|false|
|false|true|false|
|false|false|false|



```
p. 23
 - important to remember the 'int' class
```
```
      if (number < 0)       		    //Line 4
         number = -number;   		    //Line 5 // becomes a negative number
```

Two-Way Selection:
--

<img src="Picture1.jpg" alt="Drawing" style="width: 800px;"/>

```java
If (expression1)
    statement1

    else
        if (balance >= 25000.00)
            interestRate = 0.04;
        else
            if (balance)
            // keep going.
```


Never use if when you can use 'elseif's


Contional Operator:
--

- Ternary Operator
- Less coding and less typing
- # create an example to see if it works to use it more often.

Default Case:

Switch Structures (continued)
- In java, switch, case, break and default are reserved words.
- in a switch 

## **Turn the power point into a markdown document.

## ** Slide 56 and is extremely important to the test/

## Breaks: - switch structures.

``` java
Example 4-20

switch (grade)
{
case 'A': 
    System.out.println("The grade is A.");
    break;

case 'B': 
    System.out.println("The grade is B.");
    break;

case 'C': 
    System.out.println("The grade is C.");
    break;

case 'D': 
    System.out.println("The grade is D.");
    break;

case 'F': 
    System.out.println("The grade is F.");
    break;

default:  
    System.out.println("The grade is invalid.");
}

```

## **Avoid partial understanding by running examples.
 - this example doesn't have a break so it ends up outputing a shitload of garbage:

 >p. 59 - 69 - In Powerpoint


## ** Make a note of this do not use '==' to compare two strings, use compareTo - p. 65
- Imparative to not use equals

Example:
-

```java
    string str1 = "Hello",
    String str2 = "hello",
    
    if(str1 == str2) /// DO NOT USE '=='
    
    if(str1.equals(str2)) // USE EQUALS
```


Labs:
-

- Next lab is called Flooring it is due Next Sunday.

## Extra Credit is in Lab 1, 3, 6, 8.


Chapter 4 - Notes:
==

##Relational Operators in Java.

- Control Structures:
- Examine relational and logical operators
- Export how to form and evaluiate logical expressions
- Learn how to use the selection control structures if and if...else
- Learn how to avoid bugs by avoiding partially understood concepts and techniques
- Learn how to use the selection control structure switch in a program.


A computer can process a programm in one of three ways:

1. In **Sequence.**

2. By making a **Selection** or choice called **Branch**.	
> In Selection, the program executes particular statements depending on one or more conditions.

3. By **Repetition**, executing a statement over and over using a structure called a **Loop.** 
> In Repetition, the program repeats particular statments a certain number of times depending on one or more conditions.

**Branch:** Altering the flow of program execution by making a seletion or choice.

**Loop:** Altering the flow of program execution by the repetition of statement(s).

















