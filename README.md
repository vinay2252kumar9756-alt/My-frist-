I'll provide detailed answers to each question.

*1. Arrays*

An array is a collection of elements of the same data type stored in contiguous memory locations.

Example: `int scores[5] = {90, 80, 70, 60, 50};`

Declaration: `data_type array_name[array_size];`

*2. Functions*

A function is a block of code that performs a specific task. It can take arguments, return values, and be reused.

Types of functions:

1. *No argument, no return value*: `void printHello() { printf("Hello"); }`
2. *Argument, no return value*: `void printName(char name[]) { printf("%s", name); }`
3. *No argument, return value*: `int getAge() { return 25; }`
4. *Argument, return value*: `int add(int a, int b) { return a + b; }`

Examples:
#include <stdio.h>

// No argument, no return value
void printHello() {
    printf("Hello\n");
}

// Argument, no return value
void printName(char name[]) {
    printf("%s\n", name);
}

// No argument, return value
int getAge() {
    return 25;
}

// Argument, return value
int add(int a, int b) {
    return a + b;
}

int main() {
    printHello();
    printName("John");
    printf("%d\n", getAge());
    printf("%d\n", add(5, 7));
    return 0;
}
*3. Pointers*

A pointer is a variable that stores the memory address of another variable.

Example:
#include <stdio.h>

int main() {
    int x = 10;
    int *ptr = &x; // Initialize pointer
    printf("%d\n", *ptr); // Dereference pointer
    return 0;
}
*4. Types of Arrays*

1. *1D Array*: `int scores[5] = {90, 80, 70, 60, 50};`
2. *2D Array*: `int matrix[3][4] = {{1, 2, 3, 4}, {5, 6, 7, 8}, {9, 10, 11, 12}};`

Example code:
#include <stdio.h>

int main() {
    // 1D Array
    int scores[5] = {90, 80, 70, 60, 50};
    for (int i = 0; i < 5; i++) {
        printf("%d ", scores[i]);
    }
    printf("\n");

    // 2D Array
    int matrix[3][4] = {{1, 2, 3, 4}, {5, 6, 7, 8}, {9, 10, 11, 12}};
    for (int i = 0; i < 3; i++) {
        for (int j = 0; j < 4; j++) {
            printf("%d ", matrix[i][j]);
        }
        printf("\n");
    }
    return 0;
}
*5. Operators*

1. *Arithmetic Operators*: `+`, `-`, `*`, `/`, `%`, etc.
2. *Comparison Operators*: `==`, `!=`, `>`, `<`, `>=` , `<=`
3. *Logical Operators*: `&&`, `||`, `!`
4. *Assignment Operators*: `=`, `+=`, `-=`, `*=`, `/=`, etc.
5. *Bitwise Operators*: `&`, `|`, `^`, `~`, etc.

Example code:
#include <stdio.h>

int main() {
    int a = 5;
    int b = 3;

    // Arithmetic Operators
    printf("%d + %d = %d\n", a, b, a + b);
    printf("%d - %d = %d\n", a, b, a - b);

    // Comparison Operators
    printf("%d == %d = %d\n", a, b, a == b);
    printf("%d > %d = %d\n", a, b, a > b);

    // Logical Operators
    printf("%d && %d = %d\n", a, b, a && b);
    printf("%d || %d = %d\n", a, b, a || b);

    // Assignment Operators
    a += b;
    printf("a += b = %d\n", a);

    return 0;
}
Let me know if you need further clarification or details!
