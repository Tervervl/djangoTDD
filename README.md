## Курс по книге Python разработка на основе тестирования

## Установка geckodriver:

Скачать драйвер по ссылке https://github.com/mozilla/geckodriver/releases  
распаковать и скопировать в папку /bin командой sudo copy geckodriver /bin  
geckodriver --version - проверить работоспособность драйвера 

## Используемые команды:

#### Запуск тестового сервера

python manage.py runserver

#### Создание базы данных и регистрация суперпользователя

python manage.py migrate  
python manage.py createsuperuser

#### Пересоздание базы даннх

rm db.sqlite3  
python manage.py migrate --noinput

##### Создаёт миграцию базы данных:  

python manage.py makemigrations 

#### Запуск тестов

python manage.py test - запуск функциональных и модульных тестов  
python tests\functional_tests.py - функциональные тесты  
python ./tests/functional_tests.py - функциональные тесты для Линукс  
python manage.py test functional_tests - запуск функционального теста после рефакторинга  
python manage.py test lists - запуск только модульных тестов

#### Git

Создаём новый репозиторий на GitHub и далее командами:  
git remote add origin https://github.com/Tervervl/djangoTDD.git  
git push -u origin master  
связываем его с локальным git.