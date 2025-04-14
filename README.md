# Face Classification Using CLIP

A facial recognition system leveraging OpenAI's CLIP model and ChromaDB for efficient face classification and retrieval.

## Overview

This project utilizes the visual encoder of OpenAI's CLIP model to generate embeddings for facial images. 
These embeddings are stored in ChromaDB, a vector database, facilitating efficient similarity searches and classification tasks.

## Features

- **Face Embedding Generation**: Processes facial images to generate embeddings using CLIP.​
- **Vector Database Integration**: Stores embeddings in ChromaDB for efficient retrieval.​
- **Similarity Search**: Performs nearest-neighbor searches to classify and retrieve similar faces.​
- **Dataset Filtering**: Includes tools to filter datasets based on specific criteria.

## Usage

Use the **query.py** script to perform similarity searches based on a query image.

## Directory structure

```plaintext
├── Faces/                  # Directory containing facial images
├── Original Images/        # Original dataset images
├── chromadb_init.py        # Script to initialize and populate ChromaDB
├── query.py                # Script to perform similarity searches
├── utils.py                # Utility functions
├── Face Recognition.ipynb  # Jupyter notebook demonstrating the workflow
├── filtered_dataset.csv    # CSV file with filtered dataset information
├── requirements.txt        # Python dependencies
```

## Dependencies

Ensure the following Python packages are installed:​

- torch​
- Pillow​
- chromadb​
- clip-by-openai​
- pandas​
- numpy​

## Notes

- Ensure that the Faces/ and Original Images/ directories are populated with the appropriate images before running the scripts.​

- The filtered_dataset.csv file should contain the necessary metadata for the images.

