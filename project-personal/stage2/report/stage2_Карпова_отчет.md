---
## Front matter
title: "Отчет по второму этапу инд.проекта"
subtitle: "Операционные системы"
author: "Карпова Анастасия Александровна"

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
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
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

Дополнить сайт информацией о себе

# Задание

1. Разместить фотографию владельца сайта.
2. Разместить краткое описание владельца сайта (Biography).
3. Добавить информацию об интересах (Interests).
4. Добавить информацию от образовании (Education).
5. Сделать пост по прошедшей неделе.
6. Добавить пост на тему по выбору:
   Управление версиями. Git.
   Непрерывная интеграция и непрерывное развертывание (CI/CD).

# Выполнение лабораторной работы

## Размещение фотографии владельца сайта

Изменяю фотографию на сайте (рис. [-@fig:001]).

![Фото](image/1.jpg){#fig:001 width=70%}

## Размещение краткого описания владельца сайта 

Размещаю краткое описание о себе (рис. [-@fig:002])

![Описание](image/2.jpg){#fig:002 width=70%}

## Размещение информации об интересах

Размещаю на сайте информацию о своих интересах (рис. [-fig@:003])

![Интересы](image/3.jpg){#fig:003 width=70%}

## Размещение информации об образовании

Размещаю на сайте инфу о своем образовании (рис. [-fig@:004])

![Образование](image/4.jpg){#fig:004 width=70%}

![Образование](image/5.jpg){#fig:005 width=70%}

![Инфа](image/6.jpg){#fig:006 width=70%}


## Размещение поста по прошедшей неделе

Делаю пост по прошедшей неделе (рис. [-fig@:007])
 
![Процесс создания поста](image/7.jpg){#fig:007 width=70%}

## Пост по теме: Управление версиями Git

Делаю пост по этой теме

Здесь кратко описываются итоги проделанной работы.

## Вывод

В ходе выполнения работы я добавила информацию о себе.

# Список литературы{.unnumbered}

1. Архитектура ЭВМ


