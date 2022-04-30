---
## Front matter
title: "Первый этап индивидуального проекта"
subtitle: "Размещение на Github pages заготовки для персонального сайта"
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

 Разместить заготовку сайта на Github pages.

# Ход работы

1. Установим "hugo_extended_0.98.0_Windows-64bit.zip"

2. Создадим репезиторий с любым именем. (Ниже риснуок)

![](image/1.png){ width=100% }

3. Создадим репозиторий дял нашего сайта. (Ниже риснуок)

![](image/2.png){ width=100% }

4. Клонируем наш репозиторий в нашем случае "qwerty" . (Ниже риснуок)

![](image/3.png){ width=100% }

5. Далее заходим и в него и запускаем hugo.exe. (Ниже рисунок)

![](image/4.png){ width=100% }

6. В нашем репозитории создалась папка public, после этого мы копируем все её файлы и вставляем в репозиторий для сайта. (Ниже рисунок) 

![](image/5.png){ width=100% }

7. Далее опубликуем данный сайт и проверим грузится он или же нет.

![](image/6.png){ width=100% }

8. Давайте попробуем изменить что-нибудь на сайте.

![](image/7.png){ width=100% }



# Вывод

 Разместили заготовку сайта на Github pages.