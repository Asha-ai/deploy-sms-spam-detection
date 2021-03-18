# NLP-Model-Deployment
deploy sms spam model using Flask and HEROKU
Deployed link - https://deploy-sms-spam.herokuapp.com/
Data - https://www.kaggle.com/uciml/sms-spam-collection-dataset
### Steps to fallow
folder consists of app.py, html templates,nlp_model.pkl, transform.pkl, requirements.text
download the folder into your local path
open command line in the same folder - then tun the command

python app.py

then you can see local falsk URL as shown in the below command prompt:

![cmd](https://user-images.githubusercontent.com/66937023/109926235-bd975300-7ce8-11eb-8200-93f2d2fba541.PNG)

copy and paset the link in the browser - http://127.0.0.1:5000/
gen we can see html file, but this is running local flask, it need to deploy in heroku later

![image](https://user-images.githubusercontent.com/66937023/109927110-bb81c400-7ce9-11eb-80a9-bbb52e3d7f74.png)

-- keep this folder in github master branch and create account at heroku
-- congifure github repository link

![image](https://user-images.githubusercontent.com/66937023/109927575-701be580-7cea-11eb-80b5-75085872c046.png)

-- and deploy manually gen we get weblink -  https://deploy-sms-spam.herokuapp.com/
* Note its easy to configure github repo at HEROKU 




