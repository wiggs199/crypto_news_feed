# crypto_news_feed  

***Setting up your environment on Mac OS X or Linux.***

***Install Python 3.6:***

1. ***Open Terminal***

2. ***Install homebrew with the command***

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

3. ***Install Python with Brew:***

```
brew install python
```

4. ***Get the version:***

```
python3 -V
  ``` 
***Now install Django/Virtualenv on Mac OS X or Linux. Django will be the framework , and VirtualEnv(virtualenv) is a tool used to keep projects with different software versions nice and safe :)***

1.***Install Pip.(Python Package Installer):***
```
sudo easy_install pip
```

2.***Install virtualenv:***
```
sudo pip install virtualenv
```

3.***Navigate to where you want to store your code. You can:***
```
(a)Create a new directory(mkdir Name) 
```
```
(b)Change to a previous directory (cd Name)
```

4.***Create a new virtualenv:***
```
virtualenv yourenv -p python3.6 
```
  (yourenv is arbitrary)

5.***Activate virtualenv:***
```
source bin/activate (The result should look alott like -----> (yourenv) Norm-iMac-2:~ nwiggins$
```

6.***Install Django:***
```
pip install django==1.11.2

```

7.***Run Local Server:***
```
$ python3 manage.py runserver
```

When you run the server , it should look like this :
```
Performing system checks...

System check identified no issues (0 silenced).

You have unapplied migrations; your app may not work properly until they are applied.
Run 'python manage.py migrate' to apply them.

June 11, 2019 - 15:50:53
Django version 2.2, using settings 'mysite.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.
```


7. Happy Coding !!!!!!!!!!!



