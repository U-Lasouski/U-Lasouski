## О себе
- 👋 Привет, меня зовут Ласовский Владимир.
- 👀 Я интересуюсь backend разработкой на Python.
- 🌱 В данный момент изучаю алгоритмы и структуры данных.

## Ищу сотрудничество

💞️ Я ищу сотрудничество над проектами, связанными с:

- **Django**: Разработка веб-приложений, работа с ORM, создание пользовательских админ-панелей и внедрение лучших практик безопасности.
- **Django REST Framework (DRF)**: Разработка и оптимизация RESTful API, интеграция с внешними сервисами и оптимизация производительности.
- **Docker**: Контейнеризация приложений, создание Docker-образов, настройка Docker Compose, CI/CD интеграция и оптимизация работы контейнеров.

## Как со мной связаться

📫 Вы можете связаться со мной по:
- **email**: lasowskiwlodzimierz@gmail.com
- **telegram**: https://t.me/DziedJanus

## Описание проектов в репозитории

- **[foodgram-project-react](https://github.com/herrShneider/foodgram-project-react)**:
  API сервис с рецептами. Сайт, на котором можно публиковать собственные рецепты, добавлять чужие рецепты в избранное, подписываться на других авторов и создавать список покупок для заданных блюд. В ходе работы над проектом создан собственный API-сервис на Django с использованием PostgreSQL, развернуто и запущено на сервере мультиконтейнерное приложение из образов с DockerHub, настроен CI/CD.
В проекте используется регистрация и авторизация с помощью токенов (Djoser Base Token), пагинация и фильтрация, настроена админ-панель.
Стек: Python, Django, DRF, Djoser, PostgreSQL, Git, Docker, CI/CD.

- **[kittygram_final](https://github.com/herrShneider/kittygram_final)**:
  Cоциальная сеть для обмена фотографиями любимых питомцев. Целью являлся запуск проекта в контейнерах, настройка автоматического тестирования и деплоя этого проекта на удалённый сервер. Автоматизация настроена с помощью сервиса GitHub Actions. При пуше в ветку main: проект тестируется и деплоится на удалённый сервер, при пуше в любую другую ветку проект только тестируется. В случае успешного прохождения тестов образы обновляются на Docker Hub. На сервере запускаются контейнеры из обновлённых образов.
Стек: Python, Django, Docker, Docker Hub, GitHub Actions.

- **[api_yamdb_group](https://github.com/herrShneider/api_yamdb_group)**:
  API сервис, в котором пользователи могут оставлять отзывы на произведения. В проекте реализованы пользовательские роли. Пользователи оставляют к произведениям текстовые отзывы и ставят произведению оценку. Из пользовательских оценок формируется рейтинг. Пользователи могут оставлять комментарии к отзывам. Используется авторизация пользователей с помощью кода, высланного по email.
Стек: Python, Django, DRF, GitHub. Групповой проекты, в котором мной были написаны система регистрации и аутентификации, права доступа, работа с токеном, система подтверждения через e-mail, импорт данных из csv файлов.

<!---
herrShneider/herrShneider is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
