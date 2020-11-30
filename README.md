# Evans-Clinic-Centre
environment: Python 3.9.0 django 3.1.3 

This is a project for Evans Clinic Centre.
About how to use this website, please see the video in this project.
1. make the password and username in settings.py is correct, so you can link the project to your database.
2. run sql files in the floder to create tables in the database: diagnosis.sql, labresult.sql, Patientinfo.sql.
3. cd to the file folder ex:$ cd C:\Python39\Lib\site-packages\django\HelloWorld
4. install mysql setup: $ pip install pymysql
5. $ python manage.py inspectdb
6. create model.py using our own databse:$ python manage.py inspectdb > models.py
7. move created model.py to Model folder, in order to replace the model.py in the Model folder.
8. $ python manage.py migrate   # 创建表结构
9. $ python manage.py makemigrations TestModel  # 让 Django 知道我们在我们的模型有一些变更
10. $ python manage.py migrate TestModel   # 创建表结构
11. $ python manage.py runserver 0.0.0.0:8000
12. go to local website to check: http://127.0.0.1:8000/biomedical
