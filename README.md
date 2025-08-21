<div align="center">
<h1>Анализатор страниц / Page analyzer</h1>
</div>

## Ссылка на проект: https://python-project-83-40k2.onrender.com/

### Hexlet tests and linter status:
[![Actions Status](https://github.com/maxgrin04/python-project-83/actions/workflows/hexlet-check.yml/badge.svg)](https://github.com/maxgrin04/python-project-83/actions)

### Python CI Badge
[![Python CI](https://github.com/maxgrin04/python-project-83/actions/workflows/pyci.yml/badge.svg)](https://github.com/maxgrin04/python-project-83/actions/workflows/pyci.yml)

### CodeClimate Badges
[![Maintainability](https://qlty.sh/gh/maxgrin04/projects/python-project-83/maintainability.svg)](https://qlty.sh/gh/maxgrin04/projects/python-project-83)


## Описание проекта
Анализатор страниц - это сайт, который анализирует указанные страницы на SEO-пригодность по аналогии с PageSpeed Insights.

## Требования

- Python ^3.12.8
- uv ^0.5.21
- PostgreSQL

## Инструкция по установке

> Чтобы использовать пакет, вам нужно скопировать репозиторий на свой компьютер. Это делается с помощью команды ``git clone``:

```bash
git clone https://github.com/maxgrin04/python-project-83
```

> Создайте файл .env в корневой директории проекта. Добавьте в него две переменные: DATABASE_URL и SECRET_KEY.

- SECRET_KEY может быть сгенерирован или введён вручную.
- DATABASE_URL должен иметь следующий формат: {provider}://{user}:{password}@{host}:{port}/{db}

> Сделайте скрипт build.sh исполняемым:

- Перейдите в директорию проекта
```bash
cd page-analyzer
```

- Далее сделайте скрипт исполняемым
```bash
chmod +x ./build.sh
```

> Выполните установку пакета и настройте базу данных:

```bash
make build
```
