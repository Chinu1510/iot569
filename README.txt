1) Install PyCharm Community Edition 2019.3.1
2) Unzip the folder ECE569A_IoT_project and keep the folder ECE569A_IoT_project under the PycharmProjects folder
3) After opening ECE569A_IoT_project in PyCharm IDE, add an interpreter in Settings -> Project Interpreter for this project
4) Install django, requests, storages in terminal after opeining the project in PyCharm using pip command:
     i) pip install django
     ii) pip install django-storages
     iii) pip install requests
5) Move to the ECE569 folder using following command in terminal:
   cd ECE569
6) Run the manage.py runserver by the following command in terminal:
   python manage.py runserver
7) After running the above command, a URL http://127.0.0.1:8000/ will appear, on clicking the URL, the web application page in browser will appear.
8) Now, browse any files from computer and upload it.
9) If you click "submit to local", a folder with city name will appear in Documents folder and will contain the file that has been uploaded.
10) If you click "submit to cloud", the folder with city name should get created in AWS S3 bucket. But for this cloud part to work, you need AWS credentials. It worked perfectly while testing because we created a temporary AWS account to test it and screenshots are provided in the result section. After testing we disabled that AWS account.




