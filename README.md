# EX-NO-6-Pseudo-Random-Number

# AIM: 

Implementation of Pseudorandom Number Generation Using Standard library

# PROGRAM
```
NAME: NARESH KUMAR V
REG NO: 212223040126

#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int count, min, max;
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &count);
    printf("Enter the minimum value: ");
    
    scanf("%d", &min);
    printf("Enter the maximum value: ");
    scanf("%d", &max);
    srand(time(NULL));
    printf("Pseudorandom numbers:\n");   
    for (int i = 0; i < count; i++) 
    {
        int random_number = (rand() % (max - min + 1)) + min;
        printf("%d ", random_number);
    }
    return 0;
}
```

# OUTPUT

![Screenshot 2024-10-28 125845](https://github.com/user-attachments/assets/cddaceb5-5efb-4180-bfe7-350cf3177ae8)


# RESULT
   Thus the Implementation of Pseudorandom Number Generation Using Standard library was executed successfully.


