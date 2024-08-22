# My Blog - Личный Блог на Python и Django

## Описание проекта

**My Blog** - это современный и удобный личный блог, разработанный с использованием Python и Django. Проект предназначен для публикации и распространения информации, а также для поддержания активного диалога с аудиторией через систему комментариев и рекомендации.

## Назначение

Проект создан для создания интерактивного и интуитивно понятного пространства для публикации статей, управления контентом и взаимодействия с читателями. Он предоставляет широкие возможности для авторов и читателей, включая управление контентом, системы рекомендаций, комментариев и тегирования.

## Реализованный функционал

- **Админ-панель**: Управление контентом блога, пользователями и настройками сайта.
- **Канонические URL**: SEO-оптимизация структуры сайта.
- **Пагинация**: Разделение контента на страницы для лучшей навигации.
- **Система рекомендаций по электронной почте**: Автоматическая рассылка новостей подписчикам.
- **Система комментариев**: Взаимодействие между авторами и читателями.
- **Система тегирования**: Классификация статей по категориям и ключевым словам.
- **Рекомендуемые посты по комментариям**: Предложение других статей на основе комментариев.
- **Кастомные теги**: Расширение возможностей классификации статей.
- **Карта сайта**: Структурированный список всех страниц сайта.
- **RSS-лента**: Получение обновлений блога в реальном времени.
- **Поисковый механизм**: Поиск информации на сайте.

## Цель выполнения проекта

Целью проекта является создание удобного и функционального блога, который будет привлекать внимание аудитории, обеспечивая простой доступ к информации и стимулирование активного общения между участниками сообщества.

## Технический стек

- **Backend**: Python (Django)
- **Frontend**: HTML, CSS
- **База данных**: PostgreSQL
- **Система контроля версий**: Git

## Инструкция по развёртыванию проекта

1. **Скачать репозиторий**

   [Используйте команду `git clone` для клонирования репозитория на ваш локальный компьютер.](https://github.com/antsakharov/my_blog/tree/main)

2. **Создать виртуальное окружение**

   Перейдите в директорию проекта и выполните команду `python -m venv venv`, где `venv` — имя вашего виртуального окружения.

3. **Активировать виртуальное окружение**

   Для активации виртуального окружения используйте следующие команды:
   - На Linux/Mac: `source venv/bin/activate`
   - На Windows: `venv\Scripts\activate`

4. **Установить зависимости из requirements.txt**

   Запустите команду `pip install -r requirements.txt` для установки всех необходимых библиотек.

5. **Установить PostgreSQL**

   Убедитесь, что у вас установлен PostgreSQL. Если нет, скачайте и установите его с официального сайта.

6. **Создать базу данных**

   Создайте базу данных для вашего проекта, используя PostgreSQL. Это можно сделать через pgAdmin или командную строку.

7. **Создать .env файл**

   Скопируйте `.env.example` в новый файл `.env` и заполните его значениями, соответствующими вашей среде и конфигурации базы данных.

8. **Выполнить миграцию базы данных**

   Запустите команду `python manage.py migrate` для применения миграций к вашей базе данных.

9. **Запустить сервер разработки**

   Запустите сервер разработки командой `python manage.py runserver`. Теперь вы можете открыть браузер и перейти по адресу `http://127.0.0.1:8000/` для просмотра проекта.
