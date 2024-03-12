---
## Front matter
title: "Индивидуальный проект. Этап 1"
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Выполнение первого этапа индвидуального проекта, начальное понимание hugo

# Задание

1. Установка Hugo

# Выполнение лабораторной работы

Скачиваю hugo c github (рис. [-@fig:001]).

![Установка hugo](image/1.jpg){#fig:001 width=70%}

Перехожу в Downloads и распаковываю установленный зип-файл (рис. [-@fig:002]).

![Распаковка](image/2.jpg){#fig:002 width=70%}

Создаю файл bin (рис. [-@fig:003]).

![Создание файла](image/3.jpg){#fig:003 width=70%}

Перенос файлов (рис. [-@fig:003]).

![Перенос файлов](image/4.jpg){#fig:004 width=70%}

Перенос файлов (рис. [-@fig:005]).

![Перенос файлов](image/5.jpg){#fig:005 width=70%}

Проверка (рис. [-@fig:006]).

![Проверка](image/6.jpg){#fig:006 width=70%}

Создаю новый репозиторий (рис. [-@fig:007]).

![Создание нового репозитория](image/7.jpg){#fig:007 width=70%}

Задаю имя нового репозитория (рис. [-@fig:008]).

![Имя репозитория](image/8.jpg){#fig:008 width=70%}

Копирую ссылку для клонирования (рис. [-@fig:009]).

![Копирование ссылки](image/9.jpg){#fig:009 width=70%}

Клонирую репозиторий (рис. [-@fig:010]).

![Клонирование репозитория](image/10.jpg){#fig:010 width=70%}

Далее использую след.команду. (рис. [-@fig:011]).

![След команда](image/11.jpg){#fig:011 width=70%}

Создаю еще один новый репозиторий (рис. [-@fig:012]).

![Создание нового репозитория](image/12.jpg){#fig:012 width=70%}

Копирую ссылку для клонирования (рис. [-@fig:013]).

![Копирование ссылки](image/13.jpg){#fig:013 width=70%}

Клонирование репозитория + создание файла + пуш на гитхаб (рис. [-@fig:014]).

![Выполнение след.команд](image/14.jpg){#fig:014 width=70%}

Клонирование (рис. [-@fig:015]).

![Клонирование](image/15.jpg){#fig:015 width=70%}

Проверка (рис. [-@fig:016]).

![Проверка](image/16.jpg){#fig:016 width=70%}

Запушиваю (рис. [-@fig:017]).

![Запушивание файлов](image/17.jpg){#fig:017 width=70%}

![Запушивание файлов](image/18.jpg){#fig:018 width=70%}

Проверяю

![Проверка](image/19.jpg){#fig:019 width=70%}


# Выводы

В ходе лаб.работы освоила начальную работу с hugo и файлами

# Список литературы{.unnumbered}

1. Архитектура ЭВМ

