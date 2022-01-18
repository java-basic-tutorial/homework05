# Homework 05

## Exceptions. Lambdas. Streams

This homework contains only two tasks.

## Task 01

In this task you will use standard and create custom `exceptions.` 

You need to improve the class [Account](/src/main/java/com/softserveinc/task01/Account.java) 
in package [com.softserveinc.task01](/src/main/java/com/softserveinc/task01).

Class [Account](/src/main/java/com/softserveinc/task01/Account.java) contains two methods
`deposit()` and `withdraw()`. Both get as parameter amount of money.

In the methods `deposit()` and `withdraw()` you need to check if amount is negative. If so you should
throw the exception [IllegalArguemntException](https://docs.oracle.com/en/java/javase/11/docs/api/java.base/java/lang/IllegalArgumentException.html).

Also, you should check the method `withdraw()` if amount higher than balance then throw the exception `NoManyEnoughException`.

This exception you will create in package [com.softserveinc.task01](/src/main/java/com/softserveinc/task01).

**Note: pay attention at comments marked as TODO:**

## Task 02

The second task dedicated [Stream API](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html).

In the class [Task02](src/main/java/com/softserveinc/task02/Task02.java) you can find static
final field `EMPLOYEE`. It is list of object [Employee](src/main/java/com/softserveinc/task02/Employee.java) type.

You have 6 exercise (see the methods `ex01()-ex06()`) in the class [Task02](src/main/java/com/softserveinc/task02/Task02.java).

Use the [Stream API](https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html) to resolve all of them:

1. Find and return list of all male employee with aged 18 to 27 (inclusive)
2. Compute the average age of all male
3. Count how many employees are male aged 18 to 60 and women aged 18 to 55
4. Return the list of employees was sort employee by name in descending order
5. Find and return the oldest employee
6. Find and return the youngest employee

**Note: pay attention at comments marked as TODO:**

## Useful links

1. [Exceptions](https://dev.java/learn/exceptions/)
2. [Lambda Expressions](https://dev.java/learn/lambda-expressions/)
3. [Stream API](https://dev.java/learn/the-stream-api/)
4. [Шпаргалка Java программиста 4. Java Stream API](https://habr.com/ru/company/luxoft/blog/270383/)

