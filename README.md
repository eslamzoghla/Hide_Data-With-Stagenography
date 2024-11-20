# Hide Data With Stagenography
This project focuses on implementing advanced steganography techniques to hide sensitive data (text or images) within a cover image while ensuring the integrity and quality of the cover image. It includes two main components: Text Steganography and Image Steganography, both of which are deployed as user-friendly applications using Streamlit.

# Features
1. Text Steganography
Utilizes the Least Significant Bit (LSB) method to encode text into images.
Allows users to:
Input a cover image and secret text to generate a stego-image.
Extract the hidden text from the stego-image.
Ensures minimal distortion in the cover image.
Designed for simplicity and efficiency.
2. Image Steganography
Based on a Generative Adversarial Network (GAN) model with an Encoder-Decoder structure.
Encoder: Encodes the secret image into a compressed latent space.
Decoder: Decodes and reconstructs the hidden image from the cover image.
Achieves high-quality output with minimal loss of detail in both the secret and cover images.
Steps included:
Training the model to learn effective embedding and extraction.
Encoding the secret image into the cover image to generate a stego-image.
Decoding the stego-image to extract the hidden image.
3. Streamlit Deployment
Both components are deployed as interactive applications using Streamlit, enabling:
Easy uploading of images.
Real-time encoding and decoding.
Visualization of the stego-images and extraction results.

# Acknowledgment
This project is part of the DEPI Graduation Program, specializing in Generative AI.

Feel free to contribute, suggest improvements, or explore the repository to learn more about the exciting world of steganography!

# Video

https://github.com/user-attachments/assets/fa7712ca-e5e9-43cf-a7cf-c47b784d1940

