# Experiment 1
This repository is a collection of basic programming examples aimed at beginners. It includes simple implementations of the classic "Hello, World!" program and calculator.

## Progam 1: Simple ‘Hello World’ program

### Aim
To print "Hello, World!" in C++.

### Software Used
- Dev C++

### Theory
C++ is a high-level, general-purpose programming language designed for system and application programming. It was developed by Bjarne Stroustrup at Bell Labs in 1983 as an extension of the C programming language. C++ is an object-oriented, multi-paradigm language that supports procedural, functional, and generic programming styles.
<br>
In the "Hello, World!" program, the cout function from the iostream library is used to print output to the console. The iostream library is part of the C++ Standard Library, providing essential functionalities for handling input and output operations. By including using namespace std;, the program avoids the necessity of prefixing standard library names with std::, thereby simplifying the code and enhancing readability.
<br>
### Algorithm: 
<br>
Step 1: Start
<br>
Step 2: Display Hello World
<br>
Step 3: Stop
<br>

### Program Code
```cpp
// Premish Ninawe
// ENTC B1
// 23070123092
#include <iostream>
using namespace std;

int main() 
{
    cout << "Hello, World!" << endl; 
    return 0;
}
```

### Output

### Conclusion:
Hence, we learned how to print text in C++ using the cout function.
<br>

## Program 2: Simple Calculator 

### Aim
To make a basic calculator in C++.

### Software Used
- Dev C++

### Theory
The Calculator Program is a basic C++ application that performs four essential arithmetic operations: addition, subtraction, multiplication, and division. This program helps you understand how to use user input, perform calculations, and display results.
<br>
<strong align="left">Arithmetic Operations</strong>
Arithmetic Operators in C++ are used to perform arithmetic or mathematical operations on the operands. For example, ‘+’ is used for addition, ‘–‘ is used for subtraction,  ‘*’ is used for multiplication, etc. In simple terms, arithmetic operators are used to perform arithmetic operations on variables and data; they follow the same relationship between an operator and an operand.
<br>
<br>
### Algorithm
Step 1: Start
<br>
Step 2: Declare two variables: num1 and num2
<br>
Step 3: Read the first number (num1) from the user
<br>
Step 4: Read the second number (num2) from the user
<br>
Step 5: Display the value of the num1+num2
<br>
Step 6: Display the value of the num1-num2
<br>
Step 7: Display the value of the num1/num2
<br>
Step 8: Display the value of the num1*num2
<br>
Step 9: End
<br>
<br>
### Program Code
```cpp
// Name - Premish Ninawe
// PRN - 23070123092
#include <iostream>
using namespace std;
int main() {
    float num1, num2;
    cout << "Please enter the first number: ";
    cin >> num1;
    cout << "Please enter the second number: ";
    cin >> num2;
    cout << "The sum of " << num1 << " and " << num2 << " is: " << num1 + num2 << "\n";
    cout << "The difference when subtracting " << num2 << " from " << num1 << " is: " << num1 - num2 << "\n";
    cout << "The result of dividing " << num1 << " by " << num2 << " is: " << num1 / num2 << "\n";
    cout << "The product of " << num1 << " and " << num2 << " is: " << num1 * num2 << "\n";
    return 0;
}
```

### Output
![image](https://github.com/user-attachments/assets/d672f627-fbbf-47eb-9a8b-8890a0a4d9a2)
<br>
## Conclusion
Hence, we learned how to perform basic arithmetic operations in C++ using user input and output functions.
