---
## Front matter
title: "Лабораторная работа № 3"
subtitle: "Markdown"
author: "Хошхоев Александр Борисович"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
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
Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.


# Теоретическое введение

Markdown (произносится маркдаун) — облегчённый язык разметки, созданный с целью обозначения форматирования в простом тексте, с максимальным сохранением его читаемости человеком, и пригодный для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).


# Ход работы 


1. Делаем отчёт по лабораторной работе№2 в формате Markdown.

![](screenshots/1.png){width=100%}

 *Процесс работы*

2. Конвертируем наш файл в pdf и docx 

![](screenshots/2.png){width=100%}

  *Конвертация нашего файла в pdf формат*

![](screenshots/3.png){width=100%}

 *Конвертация нашего файла в docx формат*

3. Смотрим правильно всё сделано по оформлению. 


![](screenshots/4.png){width=100%}

![](screenshots/5.png){width=100%}
 
 *Отчёт по лабораторным работам*

# Вывод


Научились оформлять отчёты с помощью легковесного языка разметки Markdown.