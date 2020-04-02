# student_ms
Система управління студентами
[![Python Version](https://img.shields.io/badge/Python-3.7.6-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/Django-2.1.2-green.svg)](https://djangoproject.com)

Веб-сайт ,,Система управління студентами” потужний проект, який дозволить коледжу керувати діяльністю студентів через Інтернет, у будь-який час з будь-якої точки світу. Це допоможе найефективніше налагоджувати зв’язки між навчальним закладом, викладачами та студентами.
За основу проекта взято веб-фрейморк Python – Django.
При створенні сайту були пройдені такі етапи:
-	моделювання головного функціоналу, що реалізовано за допомогою UML-діаграм в середовищі draw.io;
-	проектування front-end та back-end функціоналу;
-	написання пояснювальної записки.
	Тому, даний сайт спростить роботу навчального закладу, маючи необхідний функціонал, що містить введення даних як про студентів, викладачів, так і про наявні кафедри, предмети, групи студентів їх оцінювання та відвідування занять.
 Робоча версія проекту http://dmitry2442.pythonanywhere.com/ 


## Запуск проекту локально

Спочатку клонуйте сховище до вашої локальної машини:

```bash
git clone https://github.com/snowbhub/student_ms.git
```

Встановіть вимоги:

```bash
pip install -r requirements.txt
```

Застосуйте міграції::

```bash
python manage.py migrate
```

Після цього слід створити власного адміністратора:
```bash
python manage.py createsuperuser
```

Нарешті, запустіть сервер розробки:

```bash
python manage.py runserver
```

Проект буде доступний за адресою **127.0.0.1:8000**.

## Ліцензія

Відкрита