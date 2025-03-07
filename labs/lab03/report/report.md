---
## Front matter
title: "Отчёт"
subtitle: "Лабораторная работа №3"
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

Научится работать с языком разметки Markdown.

# Задание

Оформить отчет второй лабораторной работы в языке разметки Markdown.

# Выполнение лабораторной работы

Создаем титульный лист (рис. [-@fig:001]).

![Создание титульного листа](image/1.PNG){#fig:001 width=70%}

Заполняем цель работы и задание (рис. [-@fig:002]).

![Заполнение цели работы и задания](image/2.PNG){#fig:002 width=70%}

Дальше копируем текст и выбираем правильные картинки (рис. [-@fig:003]).

![Оформление выполнения лабораторной работы](image/3.PNG){#fig:003 width=70%}

Заполняем вывод (рис. [-@fig:004]).

![Оформление вывода](image/4.PNG){#fig:004 width=70%}

# Выводы

В ходе данной лабораторной работы были получены знания для работы с языком разметки Markdown.
