# Stegnography 1

## Challenge Description
> ![image](https://github.com/user-attachments/assets/19f5a287-4462-47a6-a477-1c5984d936af)


## Approach
First, I used the file command to confirm the format and details of the file:

```bash
┌──(kali㉿kali)-[~/Downloads/skr]
└─$ file flag.png
flag.png: PNG image data, 1111 x 540, 8-bit/color RGB, non-interlaced
```
The file is a standard PNG image with dimensions of 1111x540 pixels.

Next, I used exiftool to inspect the metadata for any clues: 

`exiftool flag.png`

The output revealed no unusual metadata, but it confirmed the file's specifications:
- File type: PNG
- Color type: RGB
- Compression: Deflate/Inflate
- No hidden metadata or suspicious entries were found.

Using Stegsolve, I analyzed the image by applying various color maps and filters to uncover hidden information.
1. Loaded the image in Stegsolve.
2. Applied different color planes using the "Random Color Map" feature.
3. After cycling through the maps, the hidden flag appeared embedded within the image.
   
![image](https://github.com/user-attachments/assets/39a2d185-4f84-4662-afe5-ebbdc282a2c2)

## Flag: 
SKR{Th1is_1s so H@rd_TO S33}


   
