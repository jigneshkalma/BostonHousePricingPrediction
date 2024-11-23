# Boston House Pricing Prediction

### Software and Tools Requiremnents

1. [Github Account](https://github.com)
2. [Heroku Account](https://heroku.com)
3. [VS Code IDE](https://code.visualstudio.com/)
4. [Git CLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

### Create a new environment
```
conda create -p venv python=3.7 -y
```

### Activate a environment
```
conda activate venv/ 
```

### Install required libraries
```
pip install -r requirements.txt
```

### Created Model 
```
Created a model of standard scalar and linear regression
```

### Created API
```
Created a POSTMAN API to test the Flask App
```

### Created App
```
Created a Flask web app for doing prediction using web portal
```
## For Heroku Manual Deployment

### Created Procfile
```
Created Procfile to deploy the web app to Heroku cloud.
```

### Deploy Web App
```
Deploy the web app on Heroku using manual deploy from github repo.
```

### Link of Web App
-> [Boston House Price Prediction Web App](https://bostonhousingprice1.herokuapp.com/predict)

## For Heroku Deployment using Docker and Github Action

### Created Docker File
```
Created 'Dockerfile' to use it to do deployment on Heroku platform via docker container
```

### Created github and workflows folder
```
Created 'Github and workflows' folders and create the main.yaml file
```

### How to add github secrets
```
1. go to github and open your repo.
2. go to your repo setting and where you find security part on left side of setting menu.
3. in that you find "Secrets and variable" and in that you have to click on actions.
4. After click on action you have to click on New repository secret.
5. After that you have to give your secret name and its value and create it.
```


### Changes in main.yaml file using Github repo secrets
```
1. email: ${{ secrets.HEROKU_EMAIL }} add your heroku emial in github secret
2. heroku_api_key: ${{ secrets.HEROKU_API_KEY }} add your heroku secret api key in github secret
3. heroku_app_name: ${{ secrets.HEROKU_APP_NAME }} add your heroku app name in github secret
```