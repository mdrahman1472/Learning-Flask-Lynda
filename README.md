# Learning Flask by Lalith Polepeddi on Lynda.com 

## Heroku:
After install heroku software   
//login using :  
--> heroku login  

Installing Heroku for flask:  
--> pip install gunicorn  
--> pip freeze > requirements.txt  
--> touch Procfile   			// tells horoku to run flask file  
	  ==> add following line to Procfile:  
	web: gunicorn routes:app  
	      
   
// create heroku app   
--> heroku create  

  
// deploying app on heroku  
--> git push heroku master  
  
// open new tab with heroku address  
--> heroku open  

   
## install sqlalchemy
--> pip install flask-sqlalchemy   
