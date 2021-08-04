# AI-ML-Based-Disease-Prediction
Disease Predict through Symptoms

To Run the Project
Install Python 3.7.4   
Initially First Create an DJango Environment  
Go to Command Prompt of your Project Folder, the execute the following commands One-by-One  
      1.	python --version  
      2.	pip --version  
      3.	pip install virtualenvwrapper-win  
      4.	mkvirtualenv test or mkvirtualenv brain  
After Successfully Creating the Virtual Environment  
Activate Virtual Environment in Local Command Prompt or VS Code, and Execute by installing all dependencies  
First make sure PostgreSQL and pgadmin is install in your system. then you have to manually create a DB instance on PostgreSQL named "predico", better use PgAdmin for that. make a new environment(recommended) and run...    
      1. Run pip install -r requirements.txt to install dependencies  
      2. Run python manage.py makemigrations    
      3. Run python manage.py migrate  
      4. Run python manage.py runserver  
Navigate to http://127.0.0.1:8000/ in your browser  
Regards....  
