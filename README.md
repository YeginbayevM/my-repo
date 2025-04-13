# Практикум по Git/GitHub и техническому английскому

# ★ ПРАКТИКУМ ПО GIT, GITHUB И ТЕХНИЧЕСКОМУ АНГЛИЙСКОМУ ★

---

## ≡ ЦЕЛЬ ПРОЕКТА

Научиться:

- Работать с Git через командную строку (CLI)
- Создавать репозитории на GitHub
- Анализировать и описывать баги на английском языке
- Правильно оформлять Issues и Pull Requests

---

## ≡ ИНСТРУКЦИЯ ДЛЯ СТУДЕНТОВ

### 1. Клонирование репозитория

Откройте Git Bash и выполните:

```bash
git clone https://github.com/[ваш-логин]/[название-репозитория].git
```

### 2. Поиск ошибок

Изучите файлы в папке broken_code

Запустите код на выполнение

Зафиксируйте ошибки (скриншоты, логи ошибок)

### 3. Создание Issue

Перейдите на GitHub → вкладка Issues → New Issue

Выберите шаблон Bug Report

Заполните все поля на английском языке

### ТРЕБОВАНИЯ К ISSUE

Title: [Язык] Краткое описание

Пример: [Python] Division by zero in calculate_average()

Description: Детальное описание проблемы

Steps to Reproduce:

Откройте файл X

Запустите команду Y

Смотрите ошибку в строке Z

Expected/Actual Behavior:

Ожидалось: программа выводит среднее значение

Фактически: ошибка ZeroDivisionError

Environment (окружение):

OS: Windows 10

Python 3.11.4

        VS Code 1.82.1

%%≡ ПОЛЕЗНЫЕ КОМАНДЫ GIT

```
Действие	Команда
Проверка статуса	git status
Добавление изменений	git add имя_файла
Фиксация изменений	git commit -m "описание правок"
Отправка на GitHub	git push origin main
Просмотр истории	git log --oneline
```


# Содержание репозитория

1. **broken_code/** - Примеры кода с ошибками
    ```
    /broken_code
    ├── /python
    │   ├── syntax_error.txt    # Код с синтаксическими ошибками
    │   └── logical_bug.txt     # Пример логической ошибки
    ├── /javascript
    │   └── async_bug.txt       # Ошибки работы с асинхронностью
    └── /cpp
        └── memory_leak.txt     # Пример утечки памяти
    ```

2. **docs/** - Учебные материалы
    ```
    /docs
    ├── git_guide_ru.txt        # Полное руководство по Git (на русском)
    ├── english_terms.txt       # Глоссарий технических терминов
    └── issue_examples.txt      # Примеры оформления issues
    ```

3. **Служебные файлы**
    ```
    /
    ├── README.txt              # Главная инструкция
    ├── .gitignore              # Исключаемые из Git файлы
    └── /github
        └── /ISSUE_TEMPLATE
            └── bug_report.txt  # Шаблон для создания issue
    ```

---

### Настройка Git:

```bash
git config --global user.name "Ваше Имя"
git config --global user.email "ваш@email.com"
```
