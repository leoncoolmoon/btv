# Zigzag Line Image Converter

This webpage allows you to convert an image into a zigzag line representation. It provides an interactive platform to upload an image and adjust various parameters to fine-tune the conversion process. Here's a brief overview of what this HTML file can do:

## Features

- **Image Upload:** You can upload an image file. The image is then rendered on a canvas.

- **Parameter Adjustment:** The conversion process can be customized using various parameters such as:
    - Color Diff (64-200)
    - Epsilon for DouglasPeucker (0.2-2)
    - Max Dist (1-30)
    - Num Colors (2-255)
    - Sigma for Gaussian Smooth (0.5-5)

- **Conversion:** Once the parameters are set, you can click on the "Convert" button to start the conversion process. The conversion process includes steps like reducing the color number, finding the edges, grouping and simplifying edges, curve fitting, smoothing the curve, and finally converting the image into a zigzag line representation.

- **Output:** The result of the conversion is displayed in multiple stages:
    - Reduced Colour Image
    - Edge Detection Image
    - SVG-PNG Image
    - SVG Image
    - Gcode: This is the GCode representation of the image which can be used for CNC machines or 3D printers.

- **Downloadable SVG:** The final SVG image can be downloaded and used elsewhere.

This webpage is great for artists, designers, or anyone keen on exploring image manipulation and transformation. The usage is pretty straightforward, and you can have fun playing around with different parameters and observing their effects on the final output.
