# Boston House Pricing Prediction


This project demonstrates a complete workflow from developing a machine learning model to deploying it as a Dockerized web app on Heroku.


### Software And Tools Requirements

1. [Github Account](https://github.com)
2. [HerokuAccount](https://heroku.com)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)


### Steps

- Create a new environment

```
conda create -p venv python==3.7 -y
```
- pip install -r requirements.txt
- Preprocess the data.
- Traina model to predict House Prices.
- After training, save the model and scaler using pickle for later use in web app.
- Dockerize the app by creating a Dockerfile.
- Create a Heroku app.
- Using GitHub Actions, the workflow will automatically build, push, and release the container.