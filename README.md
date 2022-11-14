<p align="center">
<img width="200" height="200" src="https://media-exp1.licdn.com/dms/image/C4D0BAQFxBa6W6H46_Q/company-logo_200_200/0/1655455167248?e=2147483647&v=beta&t=9APBEwiZiKz4a9CAZ7-QeS7UE3Ill9e7ZwITaAG0e5o">
</p>

# sentiment-analysis
Sentiment-analysis is an intent classification model created by Supernova-PulsarAIGeorgia.

## Usage
The model is divided into two parts: model training and model inference.

In model_training folder you have all necassery files to train a model

In inference, the folder with the name "model" contains neccessary files for model inferenece.

## Installation
to use API you should run docker file

commands:
```sh
sudo docker build -t dockerfile .
```
```sh
sudo docker run -p 8000:8000 dockerfile
```
## Structure

### Intent Classification

[IntentClassification.ipynb](https://github.com/Supernova-PulsarAIGeorgia/sentiment-analysis/blob/main/model_training/IntentClassification.ipynb) contains model training code.

### Model Folder
After training,save all the necessary model files to the "model" folder.

Also you can [download](https://drive.google.com/drive/u/1/folders/1K6ZrM8lqqa2t80TiYk_Kj9-glVGNi-Qf) all the necessary files and add it to the "model" folder. 

### App

Implements actual intent calssification. Currently, this part is implemented as REST API.

[main](https://github.com/Supernova-PulsarAIGeorgia/sentiment-analysis/blob/main/infernce/main.py) implements the server and classification.

[calssifier](https://github.com/Supernova-PulsarAIGeorgia/sentiment-analysis/blob/main/infernce/classifier.py) inferenece of the model.

### Questions

If you have a question, create an issue, and label it as a question.

## Contribution

We welcome your pull requests for bug fixes. To implement something new, please create an issue first so we can discuss it together.
We also welcome to increase data.

When your code is ready to be submitted, submit a pull request to begin the code review process. We have added a pull request template to our project.
## Work with us

You are welcomed to contribute to this repository

## License
This project is licensed under the terms of the MIT open source license. Please refer to [LICENSE](https://github.com/Supernova-PulsarAIGeorgia/sentiment-analysis/blob/main/LICENSE) for the full terms.
