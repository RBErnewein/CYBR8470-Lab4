# CYBR8470: Secure Web Application Development
Professor: Dr. Hale  
Student:   Robert Ernewein

## Lab 4: Django Tutorial  

### VM Setup

Platform: ASUS X555D  
Host OS: Windows 10 Home (Build 1903)  
No AMD-V/RVI support

Host VM: VMWare Workstation Pro (v15.5.0)  
Emulating AMD-V/RVI  
VM OS: Ubuntu 20 LTS


### Part I: Setup/Installation  

python (v3.8.2)  
pip (v20.0.2)  
django (v3.1.2)  

First View  
![](./images/1-2.FirstView.png)

### Part II: Database Setup  

Create/Migratrate Polls   
![](./images/2-2.sqlmigrate.png)

Change Models  
![](./images/2-3.ChangeModels.png)
Note: My first changes to model.py broke syntax/structure and I had to rebuild from scratch.  

Django Admin  
![](./images/2-5.admin.png)


### Part III: Views and Templates  

Render Views  
![](./images/3-2.render.png)

Name Spacing  
![](./images/3-4.NameSpace.png)


### Part IV: Forms and Views  

View Results   
![](./images/4-1.results.png)

Generic Views  
![](./images/4-2.GenericViews.png)


### Part V: Testing  

Create Test Cases  
![](./images/5-1.Test.png)

Adding Test Cases  
![](./images/5-2.Test3.png)
Note: I ran into an issue implementing the create_question shortcut at the end of Step 5. It may have been the question I added to the database. I corrected the datatime error. Django default: PDT 
