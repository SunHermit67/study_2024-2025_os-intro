---
## Front matter
title: "Лабораторная работа № 5"
subtitle: "Отчёт"
author: "Приходько Иван Иванович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научится пользоваться pass и chezmoi.

# Задание

Настроить ОС, синхронизировать её с данной. Научится использовать программу для управления паролями.


# Выполнение лабораторной работы

Установим pass (рис. [-@fig:001]).

![Установка pass](image/1.PNG){#fig:001 width=70%}

Установим gopass (рис. [-@fig:002]).

![Установка gopass](image/2.PNG){#fig:002 width=70%}

Выведем pgp ключи (рис. [-@fig:003]).

![Вывод pgp ключей](image/3.PNG){#fig:003 width=70%}

У меня его не оказалось, поэтому я создал новый, проиннициализируем pass (рис. [-@fig:004]).

![Инициализация pass](image/4.PNG){#fig:004 width=70%}

Проинициализируем репозиторий git для pass (рис. [-@fig:005]).

![Инициализация репозитория](image/5.PNG){#fig:005 width=70%}

Создадим новый репозиторий (рис. [-@fig:006]).

![Создание репозитория](image/6.PNG){#fig:006 width=70%}

Настраиваем репозиторий (рис. [-@fig:007]).

![Настройка репозитория](image/7.PNG){#fig:007 width=70%}

Сделаем пустой коммит (рис. [-@fig:008]).

![Пустой коммит](image/8.PNG){#fig:008 width=70%}

Запушим (рис. [-@fig:009]).

![Пуш](image/9.PNG){#fig:009 width=70%}

Установим browserpass для firefox (рис. [-@fig:010]).

![Установка browserpass](image/10.PNG){#fig:010 width=70%}

Установим browserpass для системы (рис. [-@fig:011]).

![Установка browserpass](image/11.PNG){#fig:011 width=70%}

![Установка browserpass](image/12.PNG){#fig:012 width=70%}

Создадим пустой текстовый файл и дадим ему пароль (рис. [-@fig:013]).

![Добавление пароля](image/13.PNG){#fig:013 width=70%}

Установим необходимое обеспечение (рис. [-@fig:014]).

![](image/14.PNG){#fig:014 width=70%}

Установм необходимые шрифты (рис. [-@fig:015]).

![Установка шрифтов](image/15.PNG){#fig:015 width=70%}

Установим chezmoi (рис. [-@fig:016]).

![Установка chezmoi](image/16.PNG){#fig:016 width=70%}

Создадим репозиторий из шаблона (рис. [-@fig:017]).

![Создание репозитория](image/17.PNG){#fig:017 width=70%}

Проинициализируем его с chezmoi (рис. [-@fig:018]).

![Инициализация репозитория](image/18.PNG){#fig:018 width=70%}

Настроим репозиторий (рис. [-@fig:019]).

![Настройка репозитория](image/19.PNG){#fig:019 width=70%}

Проверим обновления (рис. [-@fig:020]).

![Проверка обновлений](image/20.PNG){#fig:020 width=70%}

Подключим авто обновления (рис. [-@fig:021]).

![Подключение авто обновлений](image/21.PNG){#fig:021 width=70%}

Примим изменения (рис. [-@fig:022]).

![Применение изменений](image/22.PNG){#fig:022 width=70%}

Изменим конфигурационный файл, чтобы включить автообновления (рис. [-@fig:023]).

![Изменение конфигурационного файла](image/23.PNG){#fig:023 width=70%}

# Выводы

В результате выполнения лабораторной работы были получены знания, для работы с программой для управление паролей, и навык синхронзации ОС.
