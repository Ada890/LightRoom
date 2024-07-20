# Light Room Image Editor

**Light Room** is a simple Python-based image editor built using the Tkinter library. It offers basic image manipulation features, allowing users to import images, apply transformations and filters, adjust brightness and vibrance, and export the edited images.

## Features

### Image Import
- Import images from the local file system using the "Import" button.

### Image Editing
- **Rotate**: Adjust the image rotation by specifying an angle.
- **Zoom**: Crop the image to a specific size.
- **Flip**: Flip the image horizontally, vertically, or both.
- **Brightness**: Adjust the image brightness.
- **Vibrance**: Enhance the image's color vibrance.
- **Grayscale**: Convert the image to grayscale (commented out).
- **Invert Colors**: Invert the colors of the image (commented out).
- **Blur**: Apply Gaussian blur to the image.
- **Contrast**: Adjust the image contrast.
- **Special Effects**: Apply special effects like emboss, find edges, contour, and edge enhance.

### Image Display
- The edited image is displayed in a canvas, and its size adapts to the canvas size while maintaining the aspect ratio.

### Export Image
- Users can export the edited image with a chosen name, file format, and directory.

## Usage

1. Run the application.
2. Click the "Import" button to select an image for editing.
3. Use the sliders and options to manipulate the image as desired.
4. The edited image will be displayed in the canvas.
5. Click the "Export" button to save the edited image.

## Dependencies

- Python 3.x
- CustomTkinter (customtkinter module)
- Pillow (PIL module)
- menu module (Assumed to provide UI for adjusting parameters, not provided in the code snippet)
- image_widget module (Assumed to provide image display and import functionality, not provided in the code snippet)

## Note

- Some image manipulation features like grayscale and color inversion are commented out in the code but can be uncommented for use.
- The "menu" module is assumed to provide a user interface for adjusting parameters but is not provided in the code snippet. Ensure it's available or implement it as needed.

This image editor provides a basic set of editing tools and can serve as a foundation for building a more advanced image editing application.
