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

Существует два варианта оформления ссылок. Первый — обычная вставка в текст:

<code>[Текст ссылки](адрес "Описание")
</code>

Текст ссылки

и второй вариант — оформление ссылки в виде сноски. Когда в текст вставляется конструкция вида:

<code>[Текст ссылки][Тег1]
</code>

… Указывающая, что именно в этом место будет располагаться ссылка, а где-нибудь ниже её описание:

<code>[Тег1][Адрес ссылки]
</code>

Результат выполнение будет аналогичен первому варианту, но такое оформление удобнее с точки зрения дальнейшей поддержки и редактирования.

<code>I get 10 times more traffic from [Google][1] than from
[Yahoo][2] or [MSN][3].

[1]: http://google.com/        "Google"
[2]: http://search.yahoo.com/  "Yahoo Search"
[3]: http://search.msn.com/    "MSN Search"
</code>

## Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в
начале каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть
более удобный способ: ставим по три апострофа (на букве
Ё) до и после кода. Также можно указать язык исходного
кода.
```html
<nav class="nav nav-primary">
 <ul>
 <li class="tab-conversation active">
 <a href="#" data-role="post-count"
class="publisher-nav-color" data-nav="conversation">
 <span class="comment-count">0
комментариев</span>
 <span class="comment-countplaceholder">Комментарии</span>
 </a>
 </li>
 <li class="dropdown user-menu" data-role="logout">
 <a href="#" class="dropdown-toggle" datatoggle="dropdown">
<span class="dropdown-toggle-wrapper">
 <span>
 Войти
 </span>
 </span>
 <span class="caret"></span>
 </a>
 </li>
 </ul>
</nav>
```
Самое приятное, что в коде не нужно заменять угловые
скобки `< >` и амперсанд `&` на их html-сущности.



## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.

First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

Можно управлять выравниванием столбцов при помощи
двоеточия.

| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.



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

тест