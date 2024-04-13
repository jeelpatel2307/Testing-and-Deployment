```
# Testing and Deployment in Java

This repository contains a simple example of testing and deployment in Java.

## Calculator.java

The `Calculator` class provides basic arithmetic operations such as addition and subtraction.

## CalculatorTest.java

The `CalculatorTest` class contains unit tests for the `Calculator` class using JUnit.

## Instructions

1. **Compile the classes**: Use `javac` to compile the `Calculator.java` and `CalculatorTest.java` files.

2. **Run the tests**: Execute the tests using JUnitCore.

    ```
    java -cp .:junit.jar org.junit.runner.JUnitCore CalculatorTest
    ```

3. **Package the application**: Package the application into a JAR file using the `jar` command.

    ```
    jar cvf Calculator.jar Calculator.class
    ```

4. **Deployment**: Deploy the `Calculator.jar` file to your desired environment.

Feel free to modify the code and tests as needed for your project.

```
