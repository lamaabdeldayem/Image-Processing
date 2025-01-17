
# Image Processing Project with OpenCV

This project demonstrates basic image processing techniques using Python and OpenCV. The program loads an image, applies edge detection, thresholding, and contour detection, and visualizes the results. It also draws contours and bounding boxes on the image.

## Requirements

To run the project, you need to install the required dependencies. You can do this by using `pip`.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/lamaabdeldayem/Object-Detection.git
   cd Object-Detection
   ```

### Dependencies

- `opencv-python`
- `numpy`

2. Manually install the required dependencies :
```bash
pip install opencv-python numpy
```

## Usage

Ensure that you have the required image files (`red_birds.png` and `white_templet.PNG`) in the same directory as the script.

Run the script:

```bash
python script_name.py
```

### Description of the code

- The script loads an image (`red_birds.png`) and converts it to grayscale.
- It applies edge detection using the Canny algorithm.
- Thresholding is applied to generate a binary image, and contours are detected.
- Bounding boxes are drawn around each contour in the image.
- The contours are also drawn on a blank white image (`white_templet.PNG`).

The results are displayed in separate windows showing the following:
- The original image (`img`)
- The grayscale image (`img_gray`)
- The edge-detected image (`edge_detection`)
- The thresholded image (`thresh`)
- The image with contours drawn on it (`white_image`)
- The final image with bounding boxes around the contours (`img_after`)

### Example

1. Original Image:
   ![original](./red_birds.png)

2. Edge Detection:
   ![edge_detection](./edge_detection.png)

3. Contours with Bounding Boxes:
   ![img_after](./img_after.png)
