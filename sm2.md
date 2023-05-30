# Туториал по основам системы контроля версий GIT


## *Инициализация проекта*
**Чтобы добавить возможность использовать разные версии файлов необходимо использовать следующую команду:**

~~~fix
git init
~~~


## *Как добавить файл в отслеживание*
**Чтобы добавить файл на отслеживание используйте следующую команду:**

~~~fix
git add
~~~


## *Состояние файла*
**Чтобы узнать какие файлы изменены, но не добавлены в индекс используется команда:**

~~~fix
git status
~~~

## *Создание коммита*
**Чтобы создать коммит используется команда:**

~~~fix
git commit -m ""
git commit -am ""
~~~

## *Просмотреть историю коммитов*
**Чтобы просмотреть историю коммитов с их хеш-кодами используются команды:**

~~~fix
git log 
git reflog
~~~


# Инструкция-туториал по разметке Markdown


## Ссылки





## Исходный код





## Таблицы





## Изображения

Картинка без `alt` текста

![](https://img.freepik.com/free-photo/selective-focus-shot-of-a-white-goose-in-a-snowy-field_181624-56511.jpg?size=626&ext=jpg)

Картинка с альтом и тайтлом:

![Alt text](https://img.freepik.com/free-photo/selective-focus-shot-of-a-white-goose-in-a-snowy-field_181624-56511.jpg?size=626&ext=jpg "Можно задать title")

Запомнить просто: синтаксис как у ссылок, только перед
открывающей квадратной скобкой ставится восклицательный
знак.
Картинки «сноски»:

![Картинка](https://img.freepik.com/free-photo/vertical-shot-of-a-goose-standing-on-the-ground_181624-13136.jpg?size=626&ext=jpg)

Картинки-ссылки:

[![Alt text](https://img.freepik.com/free-photo/shallow-focus-of-a-white-goose-standing-on-the-park-road_181624-51208.jpg?size=626&ext=jpg)](http://example.com/)