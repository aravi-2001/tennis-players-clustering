# tennis-players-clustering

# Automated Image Classification using Feature Extraction and KMeans Clustering

This project implements automated image classification for players in a tennis court using computer vision techniques and KMeans clustering. The solution is designed for real-time processing.


## Requirements

Before running the project, ensure you have the following installed:

- Python 3.x
- OpenCV
- scikit-learn
- NumPy
- Matplotlib

You can install the required libraries using pip:

```bash
pip install opencv-python scikit-learn numpy matplotlib '''



'''lua

├── two_players_top/
└── two_players_bot/
├── execute.sh
└── script.py
Place your images in the data/two_players_top and data/two_players_bot directories.

Usage
To run the code, execute the execute.sh script:

'''bash
chmod +x execute.sh  # Make the script executable (if not already)
./execute.sh

This script will process the images, perform feature extraction, and apply KMeans clustering to classify the players, saving the output images in the output directory.
