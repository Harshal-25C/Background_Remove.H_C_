# Background_Remove.H_C_

## Getting Started :
>**Note** : Make sure you have completed the [Python - Environment Setup](https://www.python.org/downloads/) instructions till "Creating a new application" step, before proceeding.

## Overview :
This Python script utilizes the `rembg` library to remove backgrounds from images. It provides a simple interface using `easygui` for selecting input and output files.

## Installation :
Ensure you have Python installed on your system. Then, install the required libraries :
```bash
(1) pip install easygui
(2) pip install rembg
```

## Usage :
1. Run the script.
2. Select the image file you want to process.
3. Choose where to save the processed image.

## Example :
Let's say you have an image `input_image.png` with a background you want to remove. After running the script and selecting `input_image.png` as the input file, you'll get a background-removed version saved as `output_image.png`.
- I uploaded `lion.jpg` as input :
![ss1](https://github.com/Harshal-25C/Background_Remove.H_C_/blob/main/lion.jpg)

- So , I got the Output :
![ss2](https://github.com/Harshal-25C/Background_Remove.H_C_/blob/main/lion_rembg.png.bmp)

## Notes :
- This script works best with images containing distinct foreground objects against a solid background.
- For complex images, manual touch-ups may be required.

## Contributing :
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
- [ Harshal Choudhary ] - [ harshalchoudhary340@gmail.com ].
