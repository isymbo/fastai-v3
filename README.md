# Starter for deploying [fast.ai](https://www.fast.ai) models on your own cloud server(linux for example).

This repo can be used as a starting point to deploy
[fast.ai](https://github.com/fastai/fastai) models on your own server.

Make sure you have installed docker and docker-compose before following steps
blow.

* cd into the directory of the repo
* put your trained model file (*.pth) under ./app/models
* run ```docker build -t fastai:lesson2 .```
* run ```docker-compose up -d```

Then you should be able to access the application on http://**yourhostip**:5042
