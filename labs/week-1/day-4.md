# Objective:

In this lab, students will explore the differences between classes, structs, and enums in Swift and understand when to use each in app design. They will learn about reference types vs. value types in memory management, and how to handle errors using do-try-catch blocks. Additionally, students will work with optionals and understand how to safely use optional binding, force unwrapping, and optional chaining.

# Instructions:

1. Create a Swift playground or Xcode project to complete the tasks.
2. Follow the step-by-step instructions for each task below.
3. Write your code in a clear and organized manner, following best practices.
4. Your code must be logically correct.

# Requirements:

1. Xcode v13 or higher installed
2. Swift compiler v5.7 or higher installed

# Tasks:

## Task 1: Understanding Data Types

- Declare an enum `Gender` with cases for male, female, and other.
- Create a struct `Car` with properties for make, model, and year.
- Define a class `Person` with properties for name, age, and gender, and car.
- Create at least two instance of each type and print them.

## Task 2: Memory Management

- Create a class `BankAccount` with a balance property.
- Implement a method to deposit money and another to withdraw money, handling negative balances.
- Test the class using different instances, considering reference types and memory management.

## Task 3: Error Handling

- Define a custom error type `LoginError` with cases for invalidUsername and invalidPassword.
- Create a function `login` that takes username and password as arguments and throws a `LoginError` if invalid.
- Use do-try-catch blocks to handle errors when calling the `login` function.

## Task 4: Optional Handling

- Create a struct `Book` with optional properties for title, author, and publication year.
- Implement a function to safely print book information, handling nil values.
- Use optional binding and force unwrapping as needed.

## Task 5: Optional Chaining

- Define a class `Address` with an optional property for street address.
- Create a class `Employee` with a property for the address instance.
- Implement a function to print the person's street address using optional chaining.

# Submission Guidelines:

- Create new repository name it as "iOS-Developemnt-Bootcamp-July-2023-Week-1-Day-4-Lab".
- Upload your project files to the repo you just created.
- Submit your project repo link as comment to [here](https://github.com/learning-bootcamps/iOS-Development-Bootcamp-July-2023/issues/5).

# Grading Criteria:

Your lab assignment will be graded based on the following criteria:

- Correctness and completion of tasks (50%)
- Code quality, readability, and adherence to best practices (50%)

# Additional Notes:

- You may ask the lab instructor for assistance during lab hours.
- Avoid plagiarism; write the code yourself.
- Late submissions will not be accepted without prior approval.

# Deadline:

Submit your completed lab assignment prior start of next session.
