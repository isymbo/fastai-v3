# Starter for deploying [fast.ai](https://www.fast.ai) models on your own cloud server(linux for example).

This repo can be used as a starting point to deploy
[fast.ai](https://github.com/fastai/fastai) models on your own server.

Make sure you have installed docker and docker-compose before following steps
blow.

* cd into the directory of the repo
* run ```docker build -t fastai:lesson2 .```
* run ```mkdir models```, and put your trained model file (*.pth) under this dir. ***NOTE:*** not the directory of app/models.
* run ```docker-compose up -d```

Then you should be able to access the application on http://**yourhostip**:5042
