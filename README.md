# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    srand(time(0));

    printf("Enter number of random numbers: ");
    scanf("%d", &n);

    printf("Random Numbers:\n");

    for (i = 0; i < n; i++) {
        printf("%d\n", rand() % 100);
    }

    return 0;
}
```
# OUTPUT:
<img width="500" height="318" alt="image" src="https://github.com/user-attachments/assets/594a7f9c-89ab-4525-bb95-eea4dd728e68" />

# RESULT:
The program has successfully executed
