# Personal details:
 1. Name: Dhanushmanth savaturi
 2. University: IIT Bhubaneswar
 3. Department: Computer Science and Engineering (B-Tech)


# wechat---a-messaging-service-prototype
A real time messaging service prototype developed using django framework , channels , web sockets and Rest APIs.

# Project Setup
1. First clone the repository and do the following steps ( I used VScode editor for all the work .)

2. Better to create a virtual environment , to create use `py-m venv <name>`
and activate it using `<name>\scripts\activate.bat`

3. Now install dependencies using `pip install -r requirements.txt`

4. Change directory to "wechat" folder and perform migrations
```
    python manage.py makemigrations
    python manage.py migrate
```
5. Atlast , Start server using `python manage.py runserver`
6. If want to check admin panel , create a superuser  using `python manage.py createsuperuser` and go to  http://127.0.0.1:8000/admin .

   

# how to use 
1. After starting the server go to the localhost given in the terminal ( http://127.0.0.1:8000/ ).
2. Now , first signup with the credentials and then login and enter the home page/groups page .
3. In two different tabs , login with two different accounts and start the conversation . If required can signout.
4. Sample screenshots of the prototype can be found in the wechat/screenshots location.

# system design 
 1. Documentation can be found in the project folder with name : SD_Document a pdf file whichn can be downloaded .
 
