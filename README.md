# Отчёт о пошаговом создании и публикации статического сайта на MkDocs + GitHub Pages

> Репозиторий: https://github.com/vladik7063/python-static-site-ya-v  
> Опубликованный сайт: https://vladik7063.github.io/python-static-site-ya-v

---

## Шаг 1. Создание репозитория на GitHub
1. Авторизовался в аккаунте GitHub.
2. Нажал кнопку «New repository».
3. Заполнил имя: `python-static-site-ya-v`.
4. Оставил репозиторий публичным, без README и лицензии.
5. Нажал «Create repository».

---

## Шаг 2. Клонирование репозитория локально
1. Открыл терминал PowerShell в рабочей папке.
2. Выполнил команду:
   ```bash
   git clone https://github.com/vladik7063/python-static-site-ya-v.git
3. Перешёл в папку проекта: cd python-static-site-ya-v

---

## Шаг 3. Создание виртуального окружения
1. Внутри папки проекта выполнил:python -m venv venv
2. Убедился, что появилась папка venv.

---

## Шаг 4. Активация окружения
1. Для Windows в PowerShell: .\venv\Scripts\activate
2. В командной строке появился префикс (venv), что подтвердило активацию.

---

## Шаг 5. Установка MkDocs
1. В активированном окружении выполнил: pip install mkdocs
2. Проверил версию: mkdocs --version
3. Выполнил: mkdocs new
   В результате появились:
  ⋅⋅*mkdocs.yml — конфигурационный файл
  ⋅⋅*docs/index.md — стартовая страница

---

## Шаг 6. Локальный просмотр
1. Запустил сервер: mkdocs serve
2. Открыл браузер по адресу http://127.0.0.1:8000 и убедился, что страница отображается корректно.
