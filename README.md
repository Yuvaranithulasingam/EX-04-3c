# EX-4(C)  LENGTH OF THE STRING

## AIM:
To write a C program to find the length of the string .

## ALGORITHM:
  1: Start the program.
  
  2: Read a string input from the user and store it in a character array str with a maximum
capacity of 100 characters.

  3: Initialize a variable c to 0 to count the length of the string.
  
  4: Iterate through each character ch in the str array, Increment c by 1.
  
  5: Print the value of c as the length of the string.
  
  6: Stop the program.

## program:
```
#include <stdio.h>
#include <string.h>
int main()
{
    int i;
    char str[10];
    scanf("%s",str);
    for(i=0;str[i]!='\0';i++);
    printf("Length of Str is %d\n", i);
return 0;
}
```

## OUTPUT:
![image](https://github.com/Yuvaranithulasingam/EX-04-3c/assets/121418522/d880f841-ae37-4e72-a93a-30553f9067fc)

## RESULT:
Thus, the program is successfully verified.
