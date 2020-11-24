# Evans-Clinic-Centre
This is a project for Evans Clinic Centre.
About how to use this website, please see the video in this project.
1. cd to the file folder ex:cd C:\Python39\Lib\site-packages\django\HelloWorld>
2. install mysql setup: sudo pip3 install pymysql
3. run sql files to create databse and table
4. python manage.py inspectdb
5. create model.py using our own databse:python manage.py inspectdb > models.py
6. move created model.py to Model folder
7. $ python3 manage.py migrate   # 创建表结构
8. $ python3 manage.py makemigrations TestModel  # 让 Django 知道我们在我们的模型有一些变更
9. $ python3 manage.py migrate TestModel   # 创建表结构
10. python manage.py runserver 0.0.0.0:8000
11. go to local website to check: http://127.0.0.1:8000/biomedical
