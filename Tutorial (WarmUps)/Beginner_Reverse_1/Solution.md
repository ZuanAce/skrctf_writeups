# Beginner Reverse 1

## Challenge Description
> ![image](https://github.com/user-attachments/assets/6e098040-8ab8-4b97-ab13-a2da107a94e1)


## Approach
Running `cat beginner.c` to see the file content.

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
Based on the code, it can be seen that the password is the flag: `SKR{P@ssw0rd1337}`
![image](https://github.com/user-attachments/assets/d0d2cf85-3b4a-43eb-a2d4-bd5ebb40e45c)


## Flag: 
SKR{P@ssw0rd1337}


   



