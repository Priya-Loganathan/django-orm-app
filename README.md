# Django ORM Web Application

## AIM
To develop a Django application to store and retrieve data from a database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the repository to Theia IDE.Start a new inside the project folder.

### STEP 2:
Type the appropriate code for your table and provide appropriate datatypes to the columns.

### STEP 3:
Create a report about project in readme.md file and upload the django-orm-app folder to your remote repository.

# PROGRAM
```
from django.db 
import models
from django.contrib 
import admin

#Create your models here

class Student (models.Model):
    name=models.CharField(max_length=100)
    age=models.IntegerField()
    email=models.EmailField()
    referencenumber=models.CharField(max_length=20,help_text="reference number")
    
class StudentAdmin(admin.ModelAdmin):
    list_display=('name','age','email','referencenumber')
 ```
 
# OUTPUT
![clientoutput](https://user-images.githubusercontent.com/121166075/230700634-572d083a-4b45-40c9-a316-e7dbbc22b765.png)

## RESULT
thus,the project is developed to have Student Information Database.
