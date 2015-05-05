# jsx-facebook-images
A JSX Photoshop Action to prepare a bunch of images for the use in facebook

## Usage
- Download the .jsx File to your local drive.
- Open Photoshop
- Select "File/Scripts/Select" and select the previously downloaded jsx File
- Follow the instructions

## What the script does
The script performs a bunch of actions in the given order:
- Opens an image file
- Resizes the image to maximum dimensions of 1200x900px
- Draws a white border around the image
- Adds a watermark image top the upper right corner
- Sharpens both image and watermark
- Adds a copyright notice to the lower left corner of the image
- Saves the image using a "facebook-" prefix for the filename (Automatically creates a unique filename, so no file is overwritten)

## Tested in
- Adobe Photoshop CS6
