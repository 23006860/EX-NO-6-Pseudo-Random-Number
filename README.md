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
~~~
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
 {
    srand(time(0));  
    int random = rand(); 
    printf("Random number: %d\n", random); 
    return 0;
}

~~~
# OUTPUT:
![Screenshot 2025-05-25 143233](https://github.com/user-attachments/assets/03f6ece8-770a-47ef-9e15-c5083cda0874)


## Result:
The program is executed successfully
