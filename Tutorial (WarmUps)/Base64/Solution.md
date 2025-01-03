# Base 64

## Challenge Description
> ![image](https://github.com/user-attachments/assets/492cc930-2e56-4549-9e13-1f2f08fc3efe)


## Approach
As the challenge suggests the use of Base64 encoding, our first step is to decode the given text. You can either:
- Use an online decoder, such as CyberChef.
- Write your own decoding script, using programming languages like Python.
  
In this case, I used CyberChef to decode the Base64 string provided in the challenge. After decoding, the flag was revealed.

![image](https://github.com/user-attachments/assets/72dd594a-1b5d-4494-aaec-17adfb0b4304)

> [!NOTE]
> What is Base 64? 
> - Base64 is an encoding scheme used to represent binary data in a text format. It encodes data by converting it into a set of readable ASCII characters.
>   
> - Base64 is widely used in applications like data transmission, storing binary files as text, and embedding data in HTML or JSON.
>   
> Key Features of Base64:
> - The encoded string often ends with one or two = signs, which act as padding.
> - The character set used in Base64 includes uppercase letters (A-Z), lowercase letters (a-z), digits (0-9), +, and /.
> 
> How to Identify Base64-Encoded Data:
> - The text only contains characters from the Base64 character set.
> - It often has a length that is a multiple of 4.
> - You might see padding characters (=) at the end of the string.

## Flag: 
SKR{b4se64_4r3_s0_s1mp13}



   



