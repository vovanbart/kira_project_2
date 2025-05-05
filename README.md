# Проект
## Инструкция по запуску
### Создаешь папку и переходишь в нее в терминале как в прошлом проекте, также создаешь и запускаешь виртуальное окружение и устанавливаешь Django
- `django-admin startproject learning_log`
- `python manage.py startapp learning_logs`
- `python manage.py startapp users`
Копируешь содержимое файлов learning_log/settings.py и learning_logs/models.py
- `python manage.py makemigrations`
- `python manage.py migrate`
- `python manage.py createsuperuser` данные любые
Далее копируешь содержимое файлов из git себе в проект, если файла нет, создаешь его
- learning_log/urls.py
- learning_logs/templates/learning_logs все файлы
- learning_logs/admin.py
- learning_logs/forms.py
- learning_logs/urls.py
- learning_logs/views.py
- users/templates/registration все файлы
- users/urls.py
- users/views.py
После этого в терминале пишешь `python manage.py runserver`, проверяешь, что все работает по ссылке http://127.0.0.1:8000
