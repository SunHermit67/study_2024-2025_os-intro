---
## Front matter
title: "Лабораторная работа № 4"
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

Получение навыков работы с репоззиториями git.

# Задание

Выполнить работы с тестовым репозиторием, преобраазовать его в репозиторий с git-flow.

# Выполнение лабораторной работы

Для начала подключаем репозиторий, из которого скачаем gitflow (рис. [-@fig:001]).

![Подключение репозитория](image/1.PNG){#fig:001 width=70%}

Устанавливаем gitflow (рис. [-@fig:003]).

![Установка gitflow](image/3.PNG){#fig:003 width=70%}

Устанавливаем nodejs (рис. [-@fig:004]).

![Установка nodejs](image/4.PNG){#fig:004 width=70%}

Устанавливаем pnpm (рис. [-@fig:005]).

![Установка pnpm](image/5.PNG){#fig:005 width=70%}

Запускаем pnpm (рис. [-@fig:006]).

![Запуск pnpm](image/6.PNG){#fig:006 width=70%}

Установим с помощью него commitizen и changelog(рис. [-@fig:007]).

![Установка commitizen и changelog](image/7.PNG){#fig:007 width=70%}

Создадим репозиторий git-extended (рис. [-@fig:008]).

![Создание репозитория git-extended](image/8.PNG){#fig:008 width=70%}

Создадим тестовый файл (рис. [-@fig:009]).

![Создание тестового файла](image/9.PNG){#fig:009 width=70%}

Добавим первый коомит и добавим ветку (рис. [-@fig:010]).

![Первый коммит и ветка](image/10.PNG){#fig:010 width=70%}

Проинициализируем pnpm (рис. [-@fig:011]).

![Инициализация pnpm](image/11.PNG){#fig:011 width=70%}

Добавим необходимую информацию в только что созданный файл package.json (рис. [-@fig:012]).

![Изменение package.json](image/12.PNG){#fig:012 width=70%}

Сделаем коммит через cz и запушим (рис. [-@fig:013]).

![Коммит через cz и пуш](image/13.PNG){#fig:013 width=70%}

Проинициализируем gitflow и убедимся ,что мы на ветке develop (рис. [-@fig:014]).

![Инициализация gitflow](image/14.PNG){#fig:014 width=70%}

Запушим (рис. [-@fig:015]).

![Пуш](image/15.PNG){#fig:015 width=70%}

Добавим ветку релиза 1.0.0 (рис. [-@fig:016]).

![Добавление ветки релиза 1.0.0](image/16.PNG){#fig:016 width=70%}

Завершим первый релиз (рис. [-@fig:017]).

![Завершение первого релиза](image/17.PNG){#fig:017 width=70%}

Запушим все файлы с тэгами (рис. [-@fig:018]).

![Пуш](image/18.PNG){#fig:018 width=70%}

Создадим первый changelog (рис. [-@fig:019]).

![Первый changelog](image/19.PNG){#fig:019 width=70%}

Начнем релиз 1.2.3 (рис. [-@fig:020]).

![Релиз 1.2.3](image/20.PNG){#fig:020 width=70%}

Изменим package.json (рис. [-@fig:021]).

![Изменение package.json](image/21.PNG){#fig:021 width=70%}

Добавляем новый changelog и коммит (рис. [-@fig:022]).

![Changelog и коммит новой версии](image/22.PNG){#fig:022 width=70%}

Пушим (рис. [-@fig:023]).

![Финальный пуш](image/23.PNG){#fig:023 width=70%}

# Выводы

В результате выполнение данной работы были получены навыки работы с расширенными возможностями git.
