## Курс по книге Python разработка на основе тестирования

### Используемые команды
### Запуск тестового сервера

python manage.py runserver

### Создание базы данных и регистрация суперпользователя

python manage.py migrate  
python manage.py createsuperuser  

##### Создаёт миграцию базы данных:  

python manage.py makemigrations 

### Запуск тестов

python manage.py test - модульные тесты  
python tests\functional_tests.py - функциональные тесты  
python ./tests/functional_tests.py - функциональные тесты для Линукс

### Git

Создаём новый репозиторий на GitHub и далее командами:  
git remote add origin https://github.com/Tervervl/djangoTDD.git  
git push -u origin master  
связываем его с локальным git.