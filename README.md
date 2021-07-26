## Курс по книге Python разработка на основе тестирования

### Используемые команды
### Запуск тестового сервера

python manage.py runserver

### Создание базы данных и регистрация суперпользователя

python manage.py migrate
python manage.py createsuperuser

### Запуск тестов

python manage.py test - модульные тесты  
python tests\functional_tests.py - функциональные тесты