# demo

# FeatureRequestFlask

This is a Feature Request APP for a product in insurance industry. It is a web application to add and manage a new features requested by the client.


Techstack for this application:


    OS: Ubuntu 16
    Server Side Scripting: Python 2.7
    Server Framework: Flask
    ORM: Sql-Alchemy
    JavaScript: KnockoutJS
    Continious Integration Tool : Jenkins
    Automated Deployment Platform : AWS Code Deploy with EC2
    
    
  Flow of the Application :
  
      
  ![alt text](http://52.74.168.111/wp-content/uploads/2016/06/devops.png)
  
  ![alt text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR3jm_BcnJO5kC3o0DXhiot3jLYAg6tRX5KipgP3I8TklVcgz-Z7g)
  
  
            

  
    
    
  File Description - 
  
  Directories -
  
    FeatureRequestApp - Contains Whole Application Code
    static - Contains sub directories (1)css (2)js
    templates - HTMTL Templates
    
  Files -
  
    featuresapp.py - Flask app which will start Flask Server
    feature-test.py - Python file which contains test case to be tested on Jenkins Server
    views.py - Contains routes for the Flask Application
    models.py - ORM - Sqlalchmey Model for Flask Application
    
