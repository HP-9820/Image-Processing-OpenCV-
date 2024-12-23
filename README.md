# Image Processing with OpenCV

## Overview
This repository contains a collection of experiments and implementations using OpenCV to explore various image processing techniques. The goal is to enhance understanding of image variations and their impact on computer vision tasks.

## Features

### Image Enhancements
- **Filters**: Applying filters to improve image quality.
- **Blurring**: Techniques to reduce noise and smooth images.
- **Sharpening**: Enhancing edges for better clarity.
- **Color Transformations**: Transforming images to LAB color space for improved feature extraction.

### Noise Simulation
- Adding noise (Gaussian, Salt & Pepper) to images to simulate real-world scenarios for robust model training.

### Image Variations
1. **Occlusion**
   - Handling cases where parts of an object are hidden.
   - Example: Overlapping objects in a scene.

2. **Illumination/Exposure**
   - **Illumination**: Effects of light on image clarity.
     - Natural (sunlight, moonlight) and artificial sources.
   - **Exposure**: Controlling light with shutter speed, aperture, and ISO settings.
     - Switching to grayscale using infrared mode in low light.

3. **Scale Variation**
   - Changes in object size due to camera distance.
   - Example: Distant objects appear smaller, closer ones larger.

4. **Background Variation**
   - Managing diverse and dynamic backgrounds that affect detection algorithms.

5. **Pose Variation**
   - Adapting to changes in object orientation and positioning within images.

6. **Noise**
   - Addressing pixel value distortions caused by sensor or environmental factors.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
- Run the individual scripts in the `src` directory for specific image processing tasks.
- Example:
  ```bash
  python src/image_enhancement.py
  ```

## Examples
- Filters and sharpening: `examples/filter_demo.py`
- Noise simulation: `examples/noise_simulation.py`
- Scale variation: `examples/scale_variation.py`

## Contributions
Contributions are welcome! Please feel free to submit a pull request or open an issue for feedback and suggestions.

## License
This project is licensed under the MIT License.

---

Explore the fascinating world of image processing and share your thoughts!

