# Build-API-Django-Rest-Framework


 Build an API with the Django Rest Framework <br><br>
 #### 1. Create virtual env by type ("python -m venv venv")
 #### 2. Activate to venv (.\Scripts\active or source ./bin/activate ) 
 #### 3. pip install django==2.2 (in venv na)
 #### 4. pip install djangorestframework
 #### 5. pip list or pip freeze to see package
 ## Start project:
 #### 1. In project folder (django-admin startproject djangoapi)
 #### 2. Run python manage.py migrate
 #### 3. python manage.py createsuperuser
 #### 4. python manage.py runserver
 #### 5. python manage.py startapp courses
 #### 6. In settings.py (INSTALLED_APPS => 'rest_framework', 'courses')
 #### 7. Edit urls.py of project and make a new one in app
 #### 8. Edit models.py (to create database and determine datatype)
 #### 9. Create serializers.py to help to translate data and send to JSON form.
 #### 10. Edit views.py to make all logic here.
 #### 11. After getting REST-API we can test by Browser or POSTMAN.
 
 ![homepage](https://github.com/atthana/Build-API-Django-Rest-Framework/blob/master/Photo/1_home-page.JPG)<br><br>
 ![homepage](https://github.com/atthana/Build-API-Django-Rest-Framework/blob/master/Photo/2_api-page.JPG)<br><br>
 ![homepage](https://github.com/atthana/Build-API-Django-Rest-Framework/blob/master/Photo/3_api-page-post.JPG)<br><br>
 ![homepage](https://github.com/atthana/Build-API-Django-Rest-Framework/blob/master/Photo/4_api-page-id.JPG)<br><br>
