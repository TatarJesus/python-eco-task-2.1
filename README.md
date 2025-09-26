# Статический сайт на MkDocs

## 📌 Описание

Учебный проект по созданию и развертыванию статического сайта с помощью генератора \*\*MkDocs\*\* и автоматической публикацией на \*\*GitHub Pages\*\* через GitHub Actions.

Сайт доступен по адресу:  

👉 [https://TatarJesus.github.io/mysite/](https://TatarJesus.github.io/mysite/)

---

## 🚀 Пошаговое выполнение
### 1. Подготовка окружения (Windows)

Создание папки и окружения

```powershell
mkdir mysite
cd mysite
python -m venv venv
```

Активация окружения

```powershell
venv\\Scripts\\activate
```

Установка MkDocs
```powershell
pip install mkdocs mkdocs-material
```
Создание проекта
```powershell
mkdocs new .
```

### 2. Проверка работы локально:
```powershell
mkdocs serve
```
