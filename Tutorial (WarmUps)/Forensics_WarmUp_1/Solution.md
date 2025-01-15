# Forensics Warm Up 1

## Challenge Description
> ![image](https://github.com/user-attachments/assets/afeb1f7b-6012-4386-bb0c-8c8a078f55ce)


## Approach
First, I unzipped the provided archive using the 7z command:

`7z x flag.7z`

After extraction, the file flag.jpg appeared. Opening this file visually revealed an image containing the flag.

![image](https://github.com/user-attachments/assets/d91cc985-318b-4b1f-8150-846854964aef)

Since typing out the flag manually seemed tedious, I decided to extract the text using Optical Character Recognition (OCR). I ran the following command to convert the image to text:

`tesseract flag.jpg output`

After running the OCR, I checked the contents of output.txt:

`cat output.txt`

The file revealed the flag.

## Flag: 
SKR{W3LCOM3_TO_FOR3N51C5}



   
