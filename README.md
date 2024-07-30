# ImageCompression



# Image Compression using K-means Clustering

This Streamlit app allows users to compress images by reducing the number of colors using the K-means clustering algorithm. Users can upload an image, choose the number of colors, and download the compressed image.

## Features

- Upload an image in JPG, JPEG, or PNG format.
- Select the number of colors (clusters) for compression.
- View the original and compressed images.
- Display the original and compressed image sizes.
- Download the compressed image.

## Installation

To run this app locally, you need to have Python installed on your system. Follow the steps below to set up the project:

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/image-compression-kmeans.git
    cd image-compression-kmeans
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To start the Streamlit app, run the following command:
```bash
streamlit run app.py


How It Works
The app uses the K-means clustering algorithm to reduce the number of colors in an image. Here's a brief overview of the process:

Image Upload: The user uploads an image.
Color Clustering: The image pixels are clustered into the specified number of colors using the K-means algorithm.
Image Compression: The original image is compressed by replacing each pixel with the nearest cluster center.
Display Results: The original and compressed images are displayed along with their sizes.
Download Option: The compressed image can be downloaded.


Code Overview
The main code for the app is in app.py. The key sections of the code are:

Custom CSS: Enhances the UI of the app.
compress_image Function: Performs the K-means clustering and compresses the image.
Streamlit Interface: Handles the user interface and interactions.
