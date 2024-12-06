# Ex02 Django ORM Web Application
# Date:06/12/2024
# AIM
To develop a Django application to store and retrieve data from a bank loan database using Object Relational Mapping(ORM).

# ENTITY RELATIONSHIP DIAGRAM
## DESIGN STEPS
## STEP 1:
Clone the problem from GitHub

## STEP 2:
Create a new app in Django project

## STEP 3:
Enter the code for admin.py and models.py

## STEP 4:
Execute Django admin and create details for 10 books

# PROGRAM
```
admin.py

from django.contrib import admin 
from .models import Employee, EmployeeAdmin 
admin.site.register (Employee, EmployeeAdmin)

models.py

from django.db import models 
from django.contrib import admin
class Employee (models.Model):
    eid=models.CharField(max_length=20,help_text="Employee ID")         
    name=models.CharField(max_length=100)
    salary=models.IntegerField()
    age=models.IntegerField()
    email=models. EmailField()

class EmployeeAdmin (admin. ModelAdmin):
    list_display=('eid', 'name', 'salary', 'age', 'email')

```

# OUTPUT
![Screenshot 2024-12-06 233314](https://github.com/user-attachments/assets/94b98a73-c2b6-4c8b-949d-87021d5ec283)
![Screenshot 2024-12-06 234722](https://github.com/user-attachments/assets/7943d4a5-772d-46c4-ad9d-3cefc1f8f1d1)
![Screenshot 2024-12-06 234747](https://github.com/user-attachments/assets/3a8a3b5c-2dc6-4ddc-bf9d-7db243feb7b5)
![Screenshot 2024-12-06 235807](https://github.com/user-attachments/assets/2a8c2c54-f244-40b9-983a-77d1134911cb)
![Screenshot 2024-12-06 235824](https://github.com/user-attachments/assets/ceebdac5-a5ea-4033-aabf-eb77450ecce1)


# RESULT
Thus the program for creating a database using ORM hass been executed successfully
