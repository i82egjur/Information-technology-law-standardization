
# Class activity PNG 

> Standard chosen for its low complexity and easy browsing
> 
> Goal: learn how to read an standard and find the desired information 
> 
> Find inside the PNG standard the answer to the following questions:
> 

## 1. How can I know if a file is a PNG image?
- We can know this by locking at the first 8 bytes, if it is a png file, the file should begin with 89 5 4E 47 0D 0A 1A 0A
it is shown in the signature.
## 2. How are the images kept for its progressive loading?
    It is when the image is download network and show in a web, if it snot fully load, it can be parcial loaded and give us an impression of the picture.
    pass straction. The image is encoded in such way that you can have four pixel in grey, another 2 in red and so on. wich refer to the reduce image

## 3. What is a chunk?
Block of data
- In chapter 4, we can find certain information about chunk information. It describes two main chunk types which are critical chunks, and ancillary chunks.
- The specification say that "all implementations must undertand and successfully render the standard critical chunks". A valid PNG image must contain an IHDR
  chunk, one or more IDAT chunks, and an IEND chunk.
    - IHDR Image header. It must appear ***FIRST***. It contains

## 4. What is the color palette (or colour indexing)?
Each color is defined by a code.
16 color.
## What has been added to the standard from ISO?
List of changes beet... in the anex.

## Does PNG images allow transparency? Is is required oroptional

supports different levels of transparency. Each pixel can have an opacity between 0 and 255, with 0 as completely transparent.
