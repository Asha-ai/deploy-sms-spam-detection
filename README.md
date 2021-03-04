# NLP-Model-Deployment
deploy sms spam model using Flask and HEROKU
Deployed link - https://deploy-sms-spam.herokuapp.com/
### Steps to fallow
folder consists of app.py, html templates,nlp_model.pkl, transform.pkl, requirements.text
download the folder into your local path
open command line in the same folder - then tun the command
-- python app.py
then you can see local falsk URL as shown in the below command prompt:

![cmd](https://user-images.githubusercontent.com/66937023/109926235-bd975300-7ce8-11eb-8200-93f2d2fba541.PNG)

-- copy and paset the link in the browser - http://127.0.0.1:5000/
-- here we can see html file, but this is running local flask, it need to deploy in heroku next step
![image](https://user-images.githubusercontent.com/66937023/109926809-62199500-7ce9-11eb-8f48-fe006758c20d.png)

configure github and select manual deployment, then Deploy will will get weblink
![image](https://user-images.githubusercontent.com/66937023/109927954-ee788780-7cea-11eb-95a1-395cc312ef15.png)

-- Final weblink after deploying at HEROKU
![image](https://user-images.githubusercontent.com/66937023/109928493-84141700-7ceb-11eb-850a-3b815c098814.png)

*Note - configuring github repo in HEROKU is pretty easy
-- Go a head and deploy all your ML projects 
-- All the best
--Thanks Krish

