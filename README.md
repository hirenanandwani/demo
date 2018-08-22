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
    Testing Framework : Python unittest
    
    
  Flow of the Application :
  
      
  ![alt text](http://52.74.168.111/wp-content/uploads/2016/06/devops.png)
  
   
    
  File Description - 
  
  Directories -
  
    FeatureRequestApp - Contains Whole Application Code
    static - Contains sub directories (1)css (2)js
    templates - HTMTL Templates
    scripts - Contains .sh file that should be run on the tim eof deployment on AWS EC2.
    
  Files -
  
    featuresapp.py - Flask app which will start Flask Server
    feature-test.py - Python file which contains test case to be tested on Jenkins Server
    views.py - Contains routes for the Flask Application
    models.py - ORM - Sqlalchmey Model for Flask Application
    appsec.yml  - Configuration file which is read by AWS Code Deploy Agent to do before installation, installation and after
                  installation steps and other configuration steps to be followed at EC2 instances.
    
    
    
    
