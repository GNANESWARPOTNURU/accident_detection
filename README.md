
# Accident Detection and Assistance System

This project aims to detect accidents in images using a pre-trained MobileNetV2 model and provide assistance by identifying nearby hospitals and marking the accident location on a map.

## Features

- **Accident Detection**: Utilizes a deep learning model to predict whether an accident is present in an input image.
- **Nearby Hospitals**: Identifies nearby hospitals based on the location where the image was captured.
- **Map Visualization**: Marks the accident location on a map image for better visualization.
- **Data Augmentation**: Utilizes image data augmentation techniques to enhance model performance.
- **Easy Integration**: Provides a simple interface for users to input images for accident detection and assistance.

## Usage

1. **Setup Environment**:
   - Ensure Python and required dependencies are installed (`tensorflow`, `numpy`, `matplotlib`, `Pillow`, `pandas`).
   - Install required packages using `pip install -r requirements.txt`.

2. **Extract Images**:
   - Provide a ZIP file containing images to be processed.
   - Update the `zip_path` variable in the script to point to your ZIP file.
   - Run the script to extract and classify images into train, test, and validation sets.

3. **Train the Model**:
   - The pre-trained MobileNetV2 model is used for accident detection.
   - Train the model using the extracted image data.

4. **Predict Accidents**:
   - Provide an image file to the system for accident prediction.
   - The system will detect accidents, identify nearby hospitals, and mark the accident location on a map.

## Example

```python
# Predict accidents in the provided image
given_image_path = 'path_to_image.jpg'  # Update with your image path
# Run prediction
# Display results
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

