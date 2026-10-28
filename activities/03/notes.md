# Lecture 03 Activity: Notes
Name: Kim Gabriel A. Nasayao · Student ID: 2023-0002

## My photos (Parts 0 to 6)
How many photos, and what each shows (one line each):
4 photos:
- *Rubik's Cube*
- *Pineapple*
- *Cat*
- *3D Maze*

## My dataset (Part 7)
Categories: *Electricity Meter* vs. *3D Carton Maze*
Photos per category: Electricity Meter: 35 and 3D Carton Maze: 20

How I took them (places, backgrounds, lighting, angles):
*Electricity Meter*
- Photographed at the same location in my boarding house
- clear background
- different lighting each time (along with phone flash sometimes)
- different angle each time

*3D Carton Maze*
- Photographed at the same table
- clean background, sometimes includes room at the back
- slightly different lighting
- different angles

Final validation accuracy: transfer *1.0* · from scratch *0.77*
The dataset contained 55 images, split into 42 training images and 13 validation images.

## My kernel (Part 2c)
The numbers, and what it detects:
```
[[0,1,2],
[-1,0,1],
[-2,-1,0]]
```
- The kernel compares the upper-right and lower-left regions of each patch.
It is sensitive to diagonal edges running from top-left to bottom-right.
Positive and negative responses indicate opposite brightness-change directions.
Its weights sum to zero, so uniform regions produce zero response away from padded boundaries.

## AI and outside help
List any AI tools, websites or classmates you used, and for what. Write "None" if none.

- *ChatGPT*: used for assisting me with the `#TODO:` sections in code and for learning about the different Deep Learning libraries and functions.