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

```
pip install numpy
pip install pandas
pip install keras
```

## Training

Run the whole notebook.

## Evaluation

Run the whole notebook.

## Results

Our model achieves the following performance on :

### Multi-label Classification (machine learning)

| Model name         | Imbalanced Acc. | Balanced Acc. |
| ------------------ | --------------- | ------------- |
| MLP                |     40.21%      |     35.05%    |
| SVM                |     21.65%      |     28.87%    |
| RF                 |     30.93%      |     40.21%    |
| DT                 |     39.18%      |     37.11%    |

### Classification on imbalanced data (deep learning)

|                | Train Acc.      | Validation Acc.|
| -------------- | --------------- | -------------- |
| Multi label    |     0.6082      |     0.6837     |
| Insomnia       |     0.6999      |     0.7583     |
| Schizophrenia  |     0.8500      |     0.8917     |
| VD             |     0.6999      |     0.7083     |
| MBD            |     0.6700      |     0.6833     |
| Bipolar        |     0.7200      |     0.7583     |

### Classification on balanced data (deep learning)

|                | Train Acc.      | Validation Acc.|
| -------------- | --------------- | -------------- |
| Multi label    |     0.3992      |     0.4192     |
| Insomnia       |     0.7732      |     0.7891     |
| Schizophrenia  |     0.9072      |     0.9314     |
| VD             |     0.3814      |     0.5000     |
| MBD            |     0.5464      |     0.5878     |
| Bipolar        |     0.7526      |     0.7338     |

>📋  Accuracy of Multi-layered Perceptron (MLP), Support Vector Machine (SVM), Random Forest (RF), Decision Tree (DT), and Deep Learning Neural Network.
