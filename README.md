# Neural Style Transfer with TensorFlow 2.x

This repository provides a TensorFlow 2.x implementation of Neural Style Transfer, a fascinating deep learning technique that merges the content of one image with the style of another. The model is built upon the VGG19 architecture and leverages transfer learning for efficient style and content extraction.

## Features:

- **TensorFlow 2.x Integration:**
  - Harness the capabilities of TensorFlow 2.x for seamless and efficient deep learning computations.

- **VGG19 Architecture:**
  - Employ the pre-trained VGG19 neural network to perform style and content extraction.

- **Style and Content Separation:**
  - Explore the separation of style and content features from input images, allowing for creative combinations.

- **Training Loop:**
  - Experience a comprehensive training loop that utilizes the Adam optimizer to optimize the generation of stylized images.

## Usage:

1. **Specify Image Paths:**
   - Set the paths for both the content and style images to initiate the neural style transfer.

2. **Image Loading and Preprocessing:**
   - Load and preprocess images using TensorFlow functions, ensuring compatibility with the VGG19 architecture.

3. **Style and Content Layer Definition:**
   - Define the style and content layers for precise feature extraction from the images.

4. **Gram Matrix Calculation:**
   - Implement the Gram matrix calculation to capture intricate style features from the chosen style image.

5. **Training the Model:**
   - Train the model to generate a stylized image that beautifully combines the content and style elements.

## Getting Started:

1. **Clone the Repository:**
   - Clone this repository to your local machine using `git clone`.

2. **Install Dependencies:**
   - Ensure all required dependencies are installed by following the instructions in the notebook.

3. **Run the Notebook:**
   - Open and run the provided Google Colab notebook, experimenting with different content and style image combinations.

## Note:

- **Dependency Requirements:**
  - Make sure to have the necessary dependencies installed before running the notebook. Refer to the notebook for a detailed list.

Feel free to explore and experiment with various images to create captivating stylized outputs!
