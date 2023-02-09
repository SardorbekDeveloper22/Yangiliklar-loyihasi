# django-darslari-1
Bu Loyiha ma'lumotlar bazasiga asoslangan oddiy yangiliklar loyihasi.

## Dasturlar va Frameworklar
Python 3.10 va Django 4.0

## Djangoni o'rnatish 
`pip install Django`


## Foydalanish

Avvalo ma'lumotlar bazasini yangilab olish kerak
```
python manage.py migrate
python manage.py makemigrations
python manage.py migrate
```

Keyin esa Admin sahifaga kirish uchun ro'yxatdan o'tamiz yani super user yaratamiz
```
python manage.py createsuperuser
```
Ro'yxatdan o'tib bo'lgach esa serverni ishga tushiramiz

```
python manage.py runserver
```
