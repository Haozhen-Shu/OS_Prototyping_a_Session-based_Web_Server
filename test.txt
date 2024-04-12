#include <stdio.h>

int main() {
    int x = 6;  // Declare an integer variable
    int *p = &x;  // Assign the address of x to the pointer p

    // Dereference the pointer p and assign a value to the memory location it points to
    *p = 6;

    // Print the value of x
    printf("The value of x is: %d\n", x);

    return 0;
}
