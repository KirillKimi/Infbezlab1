---
# Front matter
title: "Отчёт по лабораторной работе №1"
subtitle: "Установка ОС на виртуальную машину"
author: "Сидоракин Кирилл Вячеславович"

# Generic otions
lang: ru-RU
toc-title: "Содержание"

# Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

# Pdf output format
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
### Fonts
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
## Misc options
indent: true
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, размещение файлов на сервисе Git и подготовка отчета в формате Markdown.

# Выполнение лабораторной работы

1.Перед началом выполнения лабораторной работы я скачал виртуальную машину VirtualBox
![VirtualBox](image/1.jpg){ #fig:001 width=70% }

2.Мы задаем имя,тип и версию виртуальной машины. А так же папку машины.

Нам необходимо выбрать тип “Linux” версии Red Hat(64 bit или 32 bit)- в зависимости от вашего типа системы.
![Имя и Тип](image/2.jpg){ #fig:001 width=70% }

3.Указываем объем памяти, выделенный для виртуальной машины
![Объем памяти](image/3.jpg){ #fig:001 width=70% }

4.Задаем конфигурацию жесткого диска
![Жесткий диск](image/4.jpg){ #fig:001 width=70% }

5.Указываем тип файла
![Тип файла](image/5.jpg){ #fig:001 width=70% }

6.Указываем формат хранения
![Формат хранения](image/6.jpg){ #fig:001 width=70% }

7.Указываем размер файла(40 гб)
![Размер файла](image/7.jpg){ #fig:001 width=70% }

8.Виртуальная машина создана
![VirtualBox](image/8.jpg){ #fig:001 width=70% }

9.Переходим в пункт с настройками и выбираем “Носители”
![Настройки](image/9.jpg){ #fig:001 width=70% }

10.Выбираем образ
![Образ](image/10.jpg){ #fig:001 width=70% }
![](image/11.jpg){ #fig:001 width=70% }

11.Сохраняем образ
![Сохранение](image/12.jpg){ #fig:001 width=70% }

12.После включения появляется окно, где необходимо выбрать язык
![Язык](image/13.jpg){ #fig:001 width=70% }

13.Переходим к настройкам
![Настройки](image/14.jpg){ #fig:001 width=70% }

14.Выбираем время(в зависимости от вашего региона)
![Время](image/15.jpg){ #fig:001 width=70% }

15.Выбираем установки (Server with GUI -> Development Tools)
![Время](image/16.jpg){ #fig:001 width=70% }

16.Отключаем KDUMP
![KDUMP](image/17.jpg){ #fig:001 width=70% }

17.Включаем сеть
В разделе “Host name” меняем localhost на имя пользователя.
![Сеть](image/18.jpg){ #fig:001 width=70% }

18.Необходимо придумать пароль и создать учетную запись
![Пароль и учетная запись](image/18.jpg){ #fig:001 width=70% }
![Пароль](image/19.jpg){ #fig:001 width=70% }
![Учетная запись](image/20.jpg){ #fig:001 width=70% }

19.Все запустилось и работает стабильно
![Сеть](image/21.jpg){ #fig:001 width=70% }

# Выводы

Мы приобрели практические навыки установки операционной системы на виртуальную машину, Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину.
