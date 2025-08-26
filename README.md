# Steganography
Short lab to familiarize with steganography via both Windows &amp; Linux. 8/25/25

This short lab followed both a tutorial on youtube and an article via dev.to. In this excercise, I learn to embed and decrpyt messages in images using steganography for both Windows 11 and Ubuntu Linux.

## Windows
1. First, I opened a file titled 'stegan' and copied over and image and text file.
    - The text file contained the following information: Username: Vanisher, Password: ImaginalDisk758
    
2. Next, I used 7-zip to zip the text file. After I opened up a command prompt and embedded the text file into the image.

-----------------
![photo1](https://github.com/MichaelJbyte/Steganography/blob/7033a93f78a667c865861356841d6c7f81667de2/win-steg01.png)
-----------------

3. Once done, the image now has text embedded into it. I opened the new image created through a text editor to prove the steganography worked.
    - I learned this is a common method to check for steganography on Windows systems.

-----------------
  ![photo2](https://github.com/MichaelJbyte/Steganography/blob/7033a93f78a667c865861356841d6c7f81667de2/win-steg02.png)
-----------------

## Linux
1. Mimicking the first step for Windows, I create a text file and copy an image, using the same data for the text file.

2. Next I install the software, Steghide.
   - This will assist in my learning with steganography software which utilizes encryption, unlike the Windows exercise.

3. Following, I use a Steghide command to embed the text file into the image via the Linux terminal.

---------------
![photo3](https://github.com/MichaelJbyte/Steganography/blob/7033a93f78a667c865861356841d6c7f81667de2/lin-steg01.png)
---------------

4. After, I pivot to using Steghide to decrpyt the process and retrieve the text file from the newly embedded file.
    - I first delete the original text file from the folder I made to prove the process works
  
--------------
![photo4](https://github.com/MichaelJbyte/Steganography/blob/7033a93f78a667c865861356841d6c7f81667de2/lin-steg02.png)
--------------

  - I then use another Steghide command to extract the embedded file, seperating the text and the image back into the folder.

--------------
![photo5](https://github.com/MichaelJbyte/Steganography/blob/7033a93f78a667c865861356841d6c7f81667de2/lin-steg03.png)
--------------

# Afterthoughts

This lab was short, but educated me a lot about steganography. First, i learned steganography can utilize both software and built in command-line tools to embed files into images. I learned about their respective ways to reverse the process and about the various methods one can use to hide data, such as embedding into metadata. I also feel more familiar with using the command line after this excercise. 
