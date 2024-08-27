# Test Cases for Microscopy Image Processing

## Test Case 1: Validate Image Loading and Processing

- **Title**: Validate Image Loading and Processing
- **Description**: Ensure that the microscopy image loads correctly and the image processing step (thresholding) behaves as expected.
- **Preconditions**: Microscopy images are available in the correct format and size.
- **Test Steps**:
  1. Load the image in grayscale.
  2. Apply a threshold to the image.
  3. Verify the dimensions and format of the processed image.
- **Expected Result**: 
  - The image loads successfully in grayscale.
  - The thresholding operation highlights the cells as expected.
- **Acceptance Criteria**: 
  - The image size remains 512x512 pixels.
  - Cells are clearly visible after thresholding.


## Test Case 2: Validate Image Input and Output
- **Title**: Validate Image Input and Output
- **Description**: Ensure that the software can read a high-resolution .tif image and output some form of structured data e.g csv
- **Preconditions**:
- **Test Steps**:
  1. Load the .tif image.
  2. Simulate data extraction from the image (e.g., extracting basic metadata like image size, resolution, or pixel values).
  3. Create a CSV with the extracted data (for the purpose of simulation).
  4. Verify the structure and accuracy of the generated CSV.
- **Expected Results**:
  - The CSV should be generated with the correct image attributes (e.g.width, height, mode)
- **Acceptance Criteria**: 
