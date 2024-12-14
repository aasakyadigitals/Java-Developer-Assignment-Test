# Instructions {#instructions .unnumbered}

-   Time allowed: 2 hours

-   The test consists of multiple-choice questions, short answer
    questions, and coding exercises.

-   Coding exercises should be implemented in Java. Write clean and
    optimized code.

-   Use appropriate comments to explain your code where necessary.

# Core Java (20 points)

## Multiple Choice Questions (10 points) {#multiple-choice-questions-10-points .unnumbered}

1.  What is the difference between `StringBuilder` and `StringBuffer` in
    Java? (2 points)

    1.  `StringBuilder` is thread-safe, and `StringBuffer` is not.

    2.  `StringBuffer` is thread-safe, and `StringBuilder` is not.

    3.  Both are immutable.

    4.  Both are thread-safe.

2.  What does the `volatile` keyword do in Java? (2 points)

    1.  Prevents a variable from being overridden.

    2.  Ensures a variable's value is visible to all threads.

    3.  Synchronizes a block of code.

    4.  Declares a variable as constant.

3.  What will the following code print? (2 points)

    ``` {.java language="Java"}
    int x = 10;
        int y = ++x;
        System.out.println(x + " " + y);
    ```

    1.  10 11

    2.  11 10

    3.  11 11

    4.  10 10

4.  Which collection allows null keys and values in Java? (2 points)

    1.  `Hashtable`

    2.  `HashMap`

    3.  `TreeMap`

    4.  `LinkedHashMap`

5.  Which of the following is not a feature of Java 8? (2 points)

    1.  Lambda Expressions

    2.  Streams

    3.  Modules

    4.  Functional Interfaces

# Java API Development (30 points)

## Short Answer Questions (10 points) {#short-answer-questions-10-points .unnumbered}

1.  Explain the purpose of the `@RestController` annotation in Spring
    Boot. (5 points)

2.  What is the use of the `ResponseEntity` class in Spring? (5 points)

## Coding Challenge (20 points) {#coding-challenge-20-points .unnumbered}

**Problem:**

-   Create a REST API endpoint to manage a list of books. Implement the
    following:

    1.  **GET /books**: Retrieve all books.

    2.  **POST /books**: Add a new book. Each book should have a unique
        ID, title, author, and price.

    3.  **DELETE /books/{id}**: Delete a book by ID.

-   Write the Java code using Spring Boot.

# Database Integration (20 points)

## SQL Query (10 points) {#sql-query-10-points .unnumbered}

Write an SQL query to fetch the titles of books that have a price
greater than \$20 from a table named `books`.

## Coding Challenge (10 points) {#coding-challenge-10-points .unnumbered}

**Problem:**

-   Connect to a MySQL database in Java using JDBC and retrieve all rows
    from the `books` table. Display the results in the console.

# Debugging and Problem Solving (30 points)

## Debugging Task (15 points) {#debugging-task-15-points .unnumbered}

**Problem:** The following code throws a `NullPointerException`. Fix the
issue.

``` {.java language="Java"}
public class NullPointerExample {
    public static void main(String[] args) {
        String str = null;
        System.out.println(str.length());
    }
}
```

## Problem-Solving Task (15 points) {#problem-solving-task-15-points .unnumbered}

**Problem:** Write a Java program to find the first non-repeating
character in a string.

# Scoring Criteria {#scoring-criteria .unnumbered}

-   Core Java: 20 points

-   API Development: 30 points

-   Database Integration: 20 points

-   Debugging and Problem Solving: 30 points

**Total: 100 points**


## Please update your code by creating a branch of your name and upload the test file there. The structure of assignment files is totally optional. 
