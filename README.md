# student-management-django

#Prerequisite:
```
  pip install django
  
  pip install mysql-connector-python
  
  create new directory student-mgmt
  or create venv
```
![image](https://user-images.githubusercontent.com/84037413/136268942-2cf2524e-2063-43bc-a8e4-19e877032a33.png)
# For deactivate : deactivate system-mgmt


```
  django-admin startproject student_mgmt_system
  
  Login to my sql-> username root & pwd root 
  
  create database student_mgmt_system
    
  create user 'student_mgmt_system'@'localhost' identified by 'student';
  
  # Grant all Privileges to use(read & write permission)
  grant all  privileges on *.* to 'student_mgmt_system'@'localhost';
 
```
 ![image](https://user-images.githubusercontent.com/84037413/136261426-8c607c1f-b76e-44f0-8565-26e094228789.png)
 ![image](https://user-images.githubusercontent.com/84037413/136262847-c0a6a82a-2409-484d-88b1-0ff9989e7f8f.png)
 
 
 ```
  Change default database sqlite to MYSQL in settings.py
 ```
 # Before Change:
 ![image](https://user-images.githubusercontent.com/84037413/136263899-5e6cd462-1701-41b8-ab69-5dfd6da8d9dc.png)

# AFter Change:
![image](https://user-images.githubusercontent.com/84037413/136264649-09450367-0706-4412-9211-fbb290810038.png)


