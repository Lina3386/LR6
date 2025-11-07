# Лабораторная работа №6: Система контроля версий

## Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, 
опыт работы с локальным и удаленным репозиторием. 


## Задачи
1. Создать аккаунт на GitHub
2. Fork репозитория https://github.com/Kurtyanik/LR6/
3. Установить и настроить Git
4. Клонировать репозиторий
5. Работа с ветками и слиянием
6. Откат коммита
7. Оформление отчета


## Выполнение работы

### 1. Создание и настройка аккаунта
- Создан аккаунт на GitHub: Lina3386
- Выполнен форк репозитория: https://github.com/Kurtyanik/LR6/
- Установлен git version 2.47.0.windows.1
- Настроены параметры пользователя:
    - Имя: "4416 Makarova P.D."
    - Почта: "pupulkabut56@gmail.com"


### 2. Работа с репозиторием
Снимки выполненных операций:

#### Скриншот 1: Создание файла через интерфейс GitHub
![screenshot1](screenshots/screenshot1.png)

#### Скриншот 2: Команды Git в консоли
![screenshot2](screenshots/screenshot2.png)

#### Скриншот 3: История коммитов
![screenshot3](screenshots/screenshot3.png)

#### Скриншот 4: Слияние веток
![screenshot4](screenshots/screenshot4.png)

#### Скриншот 5: Откат коммита
![screenshot2](screenshots/screenshot2.png)


## Лог команд

```
git config --global user.name "4416 Makarova P.D."
git config --global user.email
git clone https://github.com/Lina3386/LR6
git status
git pull origin master
git branch -a
git log --oneline
git log
git log --all
git show HEAD
git show origin/branch1~
git checkout -b new_branch
git add notes.txt
git commit -m "Добавлен текст в notes.txt"
git checkout master
git merge new_branch
git branch -d new_branch
git branch
git reset --hard HEAD~1
git checkout -b report
```