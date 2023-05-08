# 23Spring-CS598-Final-Project

# Application of deep and machine learning techniques for multi-label classification performance on psychotic disorder diseases

This repository is the official implementation of [Application of deep and machine learning techniques for multi-label classification performance on psychotic disorder diseases](https://www.sciencedirect.com/science/article/pii/S2352914821000356#cebib0010). 

## Requirements

To get the dataset:
>📋  Go to the [paper](https://www.sciencedirect.com/science/article/pii/S2352914821000356#cebib0010) and download csv file from Appendix A.

To mount the dataset to Google Colab:
```setup
drive.mount('/content/drive/')
file = "/content/drive/$path/data.csv"
df = pd.read_csv(file)
```

To upload dataset from local:
```
from google.colab import files
uploaded = files.upload()
```
>📋  Click on "Open in Colab". Run this cell and click 'Choose Files'

## Environment
```
Python 3.10.11

keras==2.12.0
numpy==1.22.4
pandas==1.5.3
pandas-datareader==0.10.0
pandas-gbq==0.17.9
sklearn-pandas==2.2.0
```

## Training


## Evaluation



>📋  Describe how to evaluate the trained models on benchmarks reported in the paper, give commands that produce the results (section below).

## Pre-trained Models



## Results

Our model achieves the following performance on :

### Single-label Classification on deep learning

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| My awesome model   |     85%         |      95%       |

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

>📋  Pick a licence and describe how to contribute to your code repository. 
