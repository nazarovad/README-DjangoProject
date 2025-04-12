## Веб-приложение на образовательную тематику - тренажер по английскому языку с проверкой ответов

Для запуска приложение введите команды

```python
pip install -r requirements.txt
python manage.py makemigrations   
python manage.py migrate
python manage.py runserver     
```
Для добавления нового теста открой ссылку `http://127.0.0.1:8000/admin` далее в сущности `Слова` добавь новый тест.

![img.png](progect_images/img.png)

Логин и пароль: `admin` `admin`

Для создания своего суперпользователя нужно прописать

```python
python manage.py createsuperuser
```

В итоге получаем - выбор ответа. Ответы также меняются в рандомном порядке

![img_3.png](progect_images/img_3.png)

Результат:

![img_1.png](progect_images/img_1.png)

Если бд пустая

![img_2.png](progect_images/img_2.png)


## Использование Django Rest Framework для создания Api

Для просмотра Api мы будем использовать 3 маршрута `http://127.0.0.1:8000/api/words/` и `http://127.0.0.1:8000/api/words/` для просмотра всей бд и конкретного элемента по id

![img_4.png](progect_images/img_4.png)

Также можно просмотреть по этой ссылке `http://127.0.0.1:8000/api/random-test/` рандомный тест


# README-DjangoProject
