# Analyzing Roget’s Thesaurus with Machine Learning
This project was assigned by Professor Panos Louridas, during my Applied Machine Learning course.

Utilized Beautiful Soup for web scraping, applied text preprocessing and feature extraction, implemented clustering methods for grouping words, applied machine learning algorithms with Sklearn, and used TensorFlow to build and optimize deep learning models for hierarchical word categorization.

# Installatation

## Data Resources

Because the uploading capacity of MS Teams was limited to 500MB,
the resources such as word embeddings computed and the model's for fasttext and
GloVe are uploaded to this drive:
https://drive.google.com/drive/folders/1J0WV5Xd528_cCVnz1BApbACw6wgn2pwR?usp=sharing

Make sure to add them in the same PATH as the notebook, all the other files.

## Dependencies

The dependencies of the project are managed through Poetry.
During the development process, I encountered some issues when trying to incorporate the TensorFlow dependency when used with the latest Python versions. To address this, it was necessary to adjust the Python version used for the project.
Please ensure that your Python installation is within the version range of >=3.9 and <3.11
