# Beginner Reverse 1

## Challenge Description
> ![image](https://github.com/user-attachments/assets/6e098040-8ab8-4b97-ab13-a2da107a94e1)


## Approach
Open the provided file beginner.c to inspect its contents. Use the cat command to display the code: `cat beginner.c`

Here's the content of the file:
```c
#include <stdio.h>

int main () {
        char password[16];
        printf("Enter password: ");
        scanf("%15s",password);
        if (strcmp(password, "P@ssw0rd1337") == 0)
        {
                printf("Welcome admin!\nFlag: SKR{%s}",password);
        }else{
                printf("Login failed!");
        }
}
```

Analyze the Code:
- The program prompts the user to input a password.
- It compares the input with a hardcoded string: P@ssw0rd1337.
- If the input matches, the program prints the flag using the format: SKR{<password>}.
  
From the code, it's clear that the password is the flag. Without even running the program, we can determine the flag as: `SKR{P@ssw0rd1337}`

![image](https://github.com/user-attachments/assets/d0d2cf85-3b4a-43eb-a2d4-bd5ebb40e45c)

## Flag: 
SKR{P@ssw0rd1337}


   



