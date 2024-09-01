# Image Search Engine with FAISS and InceptionV3

## Overview
This project is an image search engine that allows users to upload an image and retrieve visually similar images from a dataset. The application leverages the InceptionV3 model for feature extraction and FAISS (Facebook AI Similarity Search) for fast similarity search. This solution can be integrated into e-commerce platforms to enhance user experience by enabling customers to find products that are visually similar to an uploaded image.

## Features
- **Image Upload:** Users can upload an image to the search engine.
- **Feature Extraction:** The InceptionV3 model, pre-trained on ImageNet, is fine-tuned and used to extract feature embeddings from images.
- **Similarity Search:** FAISS is used to index and search for similar images quickly.
- **Display Results:** The top N similar images are displayed to the user.
