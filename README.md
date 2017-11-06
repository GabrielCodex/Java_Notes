#
Java_Notes

- Print
```java

System.out.println("Java rocks!");

```
## String Concatenation

```java
int debt;
int bank;
debt = 0;
bank = 0;
bank + bank + 1;
debt + debt + 2;

System.out.println("You have $"+bank+" in the bank and $"+debt+" in debut");
```
## Variable Rules
- start variable names with a letter
- no white space


## Variable Types
### int

- Can only be 10 digits long
- light weight and programs run faster
### long

- allows more than 10 digits but at the cost of speed

### double
- stores doubles
- slows down program

### String


### char
```java
char myCharacter = 'a';
```

### boolean

## Variable Arithmetic
```java
double divide = 5/2;
```
- the above would result in 2 because both of the vaules are ints
- if you want the store result to be a double then at least one of the numbers need to be a double

```java
double divide = 5/2.0;
```
- Multiplication and Division have prriority over addition and substraction so use () to control what opeartion occurs first.

## Casting

```java

double salary = 2500;
double bonus = 3.5;
double takeHome = salary * bonus;
int roundedTakeHome = (int) takehome;
System.out.println(roundedTakeHome);
```
