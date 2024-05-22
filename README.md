## Local Chattogram Lanugage to Standard Bangla Language Conversion

The model is training on encoder decoder with attention mechanism. 

## Installation
```bash
pip install -r requirements.txt
```
## Requirements
```bash
numpy==1.19.5
sentencepiece==0.1.97
tokenizers==0.8.1
torch==1.11.0+cu113
torchsummary==1.5.1
torchtext==0.12.0
torchvision==0.12.0+cu113
transformers==3.0.2
nltk==3.7 
```
## Dataset
Local Chittagong to Standard Bangla Book
## Configuration

```bash
epochs : 300
batch_size : 150
n_layers : 6  
heads : 8
d_model :512
dropout : 0.1
lr : 0.0001
```

## Inference
```bash
input : তুর লাই হথা আছে 
Ground Truth : তুর সাথে কথা আছে 
prediction: কথা আছে তুর সাথে
```