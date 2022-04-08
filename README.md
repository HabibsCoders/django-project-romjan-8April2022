# Portfolio Django web application
#### Django full functional portfolio + blog web application.

![Image of homeage of this repository](https://scontent.fdac20-1.fna.fbcdn.net/v/t39.30808-6/277529502_489573759323347_1942150943296809175_n.jpg?_nc_cat=108&ccb=1-5&_nc_sid=09cbfe&_nc_eui2=AeFX-h95Vi4vO7qf2SRQH0McIHQBDXXeoVcgdAENdd6hVz6eN0xJp6w3_VLAxvy7bwXhAd55Cl9jFe2FM8hULJzB&_nc_ohc=HXc2KRiIyx0AX8VR8Iu&tn=Kumn5Zs1WbuvrV-W&_nc_ht=scontent.fdac20-1.fna&oh=00_AT_mg8gaUCB9l4em4HmiMxUhBIgFK6HIG0Yu9ogLXDaObg&oe=62551501)

#### Prerequisite:
###### 1: python 3.8

# Deploy at heroku
```
It's 100% ready to deploy at heroku container. Just fork the 'add-migrations' branch of this repository 
or make your own. Login your heroku account and make an app.
In deploy method, select github. connect your repository and start deploy. that's it. 
```

# Local Development:
###### Download or clone the stable branch 'add-migrations'. Goto project root folder.

```
C:\>git clone https://github.com/HabibsCoders/django-project-romjan-8April2022.git

C:\>cd portfolio

C:\portfolio>cd django

C:\portfolio\django>scripts\activate.bat

(django)C:\portfolio\django>cd ..

(django)C:\portfolio>pip freeze > requirements.txt

(django)C:\portfolio>pip install -r requirements.txt

(django)C:\portfolio>python manage.py migrate

(django)C:\portfolio>python manage.py runserver
```

```
### It will start a local server on 'http://localhost:8000'
```

###### create a super user using,
```
(django)C:\portfolio>python manage.py createsuperuser
```


###### then go to http://localhost:8000/admin to accesss your administrations to control your dynamic application.

###### Congrats! everything is setup. Your project ready to deploy in heroku for live your project online.
```
Get any error, send me the scrrenshot at my inbox, i will try to give you the solution.
Facebook: https://www.facebook.com/www.habibullah.us
Email: mdhabibullahkhan7@gmail.com
Phone: 01581127669
```
