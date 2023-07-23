#  Проект «Kittygram»

## Описание проекта:

- #### Проект Kittygram создан для демонстрации Ваших котов и их достижений!

---

## У нас вы можете:

- #### Зарегистрироваться.
- #### Добавить, убрать, редактировать кота.
- #### Выбрать цвет и год рождения.
- #### Добавить фото.

---

## Технологии

[Python] - Бэкенд

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

[Django Rest Framework] - Набор инструментов Python для создания веб-API

![DjangoREST](https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=blue)

[JavaScript] - Фронтэнд

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

[React] - Библиотека JavaScript для создания пользовательских интерфейсов

![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)

[Ubuntu] - операционная система с открытым исходным кодом на базе Linux

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
 
[Gunicorn] - HTTP-сервер Python WSGI для UNIX

![Gunicorn](https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white)

[Nginx] - HTTP и обратный прокси-сервер

![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)

## Как запустить проект:

✅ Получить доменное имя

✅ Установить удаленный сервер на [Yandex Cloud](https://cloud.yandex.ru/) и авторизоваться

##### **Выполните следующие действия на вашем удаленном сервере!**

✅ Установить Python

```
sudo apt install python3-pip python3-venv -y
```

✅ Установить npm

```
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash - &&\
sudo apt-get install -y nodejs
npm -v
# 9.5.0 (or newest)
```

✅ Установить Nginx

```
sudo apt install nginx -y
```

✅ Сделать fork репозитория и клонировать его:

```
https://github.com/VladimirIakushev/kittygram_final
```

✅ Установить и активировать виртуальное окружение

```
python -m venv venv
sourse venv/scripts/activate
```

✅ Обновить pip и установить зависимости из requirements.txt

```
python -m pip install --upgrade pip
pip install -r requirements.txt
```

✅ Создать .env файл и заполнить в соответствии с  .env.excample файлом



✅ Перейти в папку бэкенд и применить миграции

```
python manage.py migrate
```

✅ Создать суперпользователя (superuser)

```
python manage.py createsuperuser
```

✅ Сделать push проекта в ветку main

```
git add .
git commit -m 'example'
git push
```


---
## Попробовать демо-версию:
* [Kittygram](https://kittygreat.ddns.net)

### Над проектом работал:
* Владимир Якушев
