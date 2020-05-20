# Курсовая работа Spy Game

## Нетология, модуль "Основы языка программирования Python", декабрь 2019 г.

### Установка

`$ git clone https://github.com/Klavionik/python_coursework_1.git`  
`$ cd python_coursework_1`  
`$ pip install -r requirements.txt`  
`$ python spygame.py`

### И что она делает?

Находит те сообщества ВКонтакте, в которых состоит пользователь, но не состоит ни один его друг. Сохраняет результат работы в JSON-файл.

### Использование

Справка по доступным опциям:

```
$ python spygame.py --help
```

При первом запуске программе потребуется получить ключ доступа к API с правами **friends** и **groups**. По умолчанию ключ доступа будет сохранен в файл `token.dat`.

После авторизации программа попросит ввести id пользователя или его screen name, выполнит поиск уникальных групп для пользователя, выведет результат в консоль и сохранит его в файл `groups.json`.
