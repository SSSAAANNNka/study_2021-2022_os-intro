---
## Front matter
title: "Лабораторная работа № 4"
subtitle: "Основы интерфейса взаимодействия пользователя с системой Unix на уровне командной строки"
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

Приобретение практических навыков взаимодействия пользователя с системой по-
средством командной строки.



# Ход работы

1. Определяем полное имя нашего домашнего каталога, для этого вводим команду.(Рис. 1)

![](image/1.png){ width=100% }

 *Рис. 1 Определение домашнего каталога*

2. Перейдём в каталог /tmp .(Рис. 2)


3. Выведем на экран содержимое каталога /tmp.(Рис. 2)

![](image/2.png){ width=100% }
 
 *Рис 2. Переход  в каталог /tmp и вывод его содержимого* 


4. Определим, есть ли в каталоге /var/spool подкаталог с именем cron, как можно заметить нет такого подкаталога.(Рис. 3)

![](image/4.png){ width=100% }
 
 *Рис. 3 вывод spool*


 5. Определим, кто является владельцем файлов и подкаталогов.(Рис. 4)

![](image/5.png){ width=100% }

*Рис. 4 Видно кто владелец*

6. В домашнем каталоге создаём новый каталог с именем newdir, далее В каталоге ~/newdir создаём новый каталог с именем morefun. (Рис. 5)

7. В домашнем каталоге создаём одной командой три новых каталога с именами
letters, memos, misk. Затем удалите эти каталоги одной командой. (Рис. 5) 

![](image/6.png){ width=100% }

 *Рис. 5 выполнение пункта 3-3.4*

 8. Попробуем удалить ранее созданный каталог ~/newdir командой rm. Проверим,
был ли каталог удалён.

![](image/7.png){ width=100% }


9. С помощью команды man определим, какую опцию команды ls нужно использо-
вать для просмотра содержимое не только указанного каталога, но и подкаталогов,
входящих в него. (Ниже рисунок)

![](image/9.png){ width=100% }


10. С помощью команды man определим набор опций команды ls, позволяющий отсорти-
ровать по времени последнего изменения выводимый список содержимого каталога
с развёрнутым описанием файлов. (Ниже рисунок)

![](image/10.png){ width=100% }


11. Используя информацию, полученную при помощи команды history, выполним мо-
дификацию и исполнение нескольких команд из буфера команд. (Ниже рисунок)

![](image/8.png){ width=100% }

# Вывод


Приобрели практические навыки взаимодействия пользователя с системой по-
средством командной строки.


# Контрольные вопросы

1. Командная строка (консоль или Терминал) – это специальная программа, которая позволяет управлять компьютером путем ввода текстовых команд с клавиатуры.

2. pwd dir

3. ls

4. ls -a

5. rm dir

   rm -f -r dir

6. history

7. !CommandNumber from history

8. cd home; ls

9. Экранирование символов — замена в тексте управляющих символов на соответствующие текстовые подстановки. Один из видов управляющих последовательностей.

