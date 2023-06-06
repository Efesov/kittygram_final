# Социальная сеть,  для любителей кисок и котиков - Kittygram
### URL

Проект развернут на сайте:  https://kisimisi.sytes.net/

### Описание проекта:

Интерактивный сайт с личным кабинетом и возможностями публикации фотографий кисок и котов, а также присваивания пушистым достижений .

### Технологии, которые использовались:

Python 3.9, Django 3.2.3, Django REST framework, React

### Запуск проекта в dev-режиме:

-   Клонируйте репозиторий и перейдите в него в командной строке:

```
git clone https://github.com/efesov/kittygram_final.git

```

```
cd kittygram_final

```

-   Запустите проект с помощью команды:

```
docker compose up

```

-   Соберите статику Django с помощью команды:

```
docker compose exec backend python manage.py collectstatic

```

-   Скопируйте статику командой:

```
docker compose exec backend cp -r /app/collected_static/. /static/static/