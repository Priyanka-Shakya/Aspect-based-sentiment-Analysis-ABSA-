# A Novel Hybrid Deep Learning Model for Aspect-Based Sentiment Analysis (ABSA)
## Brief Introduction
This project presents a hybrid deep learning approach to perform aspect-based sentiment analysis. A hybrid deep learning model that combines:
LSTM (Long Short-Term Memory) for capturing the overall contextual sentiment of the sentence by modeling sequential dependencies in the text.
GAT (Graph Attention Network) for analyzing aspect-based sentiment polarity, effectively modeling the relationships between words in a sentence through attention mechanisms based on graph structures.
This architecture enables the model to understand both the global sentiment and the fine-grained sentiment toward specific aspects in a review.

## Table of Contents
1. Installation Instructions
2. Usage
3. Features
4. Technologies Used
5. Configuration
6. Contributing
7. License
8. Authors or Acknowledgements
9. Contact Information

   
## Installation Instructions
1. Clone the repository.
2. Ensure Python 3 and pip are installed.
3. Install dependencies: pip install -r requirements.txt
4. Run the Jupyter Notebook: jupyter notebook "A Novel Hybrid Deep Learning Model for Aspect-based sentiment Analysis.ipynb"



## Usage
-> The notebook loads and preprocesses the IMDB dataset and laptop dataset.
-> Sentiment labels are encoded and the data is split into training and testing sets.
-> A hybrid model using LSTM and GAT is trained to classify overall sentence sentiments and corresponding to particular given aspect in sentence respectively.
-> Evaluation metrics and outputs are displayed in the notebook for both the components.


## Features
-  Aspect-based sentiment classification
-  Preprocessing of large review datasets
-  LSTM and GAT based deep learning architecture
-  Hybrid model design for enhanced accuracy


## Technologies Used
> Python
> TensorFlow / Keras
> Pandas
> NumPy
> Scikit-learn
> Jupyter Notebook
> Google Translate

## Configuration
1> Dataset used: IMDB Movie Reviews and Laptop dataset
2> Ensure the dataset is placed in the correct input path (/kaggle/input/imdb-dataset-of-50k-movie-reviews/IMDB Dataset.csv) for LSTM component or (https://www.kaggle.com/datasets/priyankashakya18/laptop-dataset) for GAT component -update the path accordingly in the notebook


## Contributing
1. Fork the repo
2. Create a new branch (git checkout -b feature-branch)
3. Make your changes and commit (git commit -m 'Add feature')
4. Push to the branch (git push origin feature-branch)
5. Create a Pull Request

##  Authors or Acknowledgements
>> Original model implementation and dataset usage by the notebook author.
>> Thanks to Kaggle for hosting the dataset and execution environment.

## Result
source code - *https://github.com/Priyanka-Shakya* 
- Accuracy: 94.22%

## Contact Information
**For any questions, feel free to reach out or open an issue!*https://github.com/Priyanka-Shakya*


