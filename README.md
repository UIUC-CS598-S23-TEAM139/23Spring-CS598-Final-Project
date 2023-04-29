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
>📋  Run this cell and click 'Choose Files'

## Training

To train the model(s) in the paper, run this command:

```train
python train.py --input-data <path_to_data> --alpha 10 --beta 20
```

>📋  Describe how to train the models, with example commands on how to train the models in your paper, including the full training procedure and appropriate hyperparameters.

## Evaluation

To evaluate my model on ImageNet, run:

```eval
python eval.py --model-file mymodel.pth --benchmark imagenet
```

>📋  Describe how to evaluate the trained models on benchmarks reported in the paper, give commands that produce the results (section below).

## Pre-trained Models

You can download pretrained models here:

- [My awesome model](https://drive.google.com/mymodel.pth) trained on ImageNet using parameters x,y,z. 

>📋  Give a link to where/how the pretrained models can be downloaded and how they were trained (if applicable).  Alternatively you can have an additional column in your results table with a link to the models.

## Results

Our model achieves the following performance on :

### [Image Classification on ImageNet](https://paperswithcode.com/sota/image-classification-on-imagenet)

| Model name         | Top 1 Accuracy  | Top 5 Accuracy |
| ------------------ |---------------- | -------------- |
| My awesome model   |     85%         |      95%       |

>📋  Include a table of results from your paper, and link back to the leaderboard for clarity and context. If your main result is a figure, include that figure and link to the command or notebook to reproduce it. 


## Contributing

>📋  Pick a licence and describe how to contribute to your code repository. 
