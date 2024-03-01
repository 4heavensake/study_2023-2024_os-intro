---
## Front matter
title: "Отчёт по лабораторной работе"
subtitle: "Первоначальна настройка git"
author: "Югай Александр Витальевич"

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

Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.

# Выполнение лабораторной работы

Для начала устанавливаем пакеты git 
<p align="center">![Устанавливаем git](image/1.png)
<p>Начинаем настройку git
<p>Задаем имя и email владельца репозитория
<p align="center">![Начало настройки](image/2.png)
<p>Настраиваем utf-8
<p align="center">![Настройка utf-8](image/3.png)
<p>Задаем имя для начальной ветки, параметр autocrlf и safecrlf
<p align="center">![Настройка начальной ветки и параметров](image/4.png)
<p>Создаем ключи ssh по алгоритмам rsa и ed25519
<p align="center">![rsa](image/5.png)
<p align="center">![ed25519](image/6.png)
<p>Генерируем ключ pgp
<p align="center">![pgp ключ](image/7.png)
<p>Выводим список созданных нами ключей и копируем отпечаток приватного ключа
<p align="center">![Вывод ключей](image/8.png)
<p>Копируем pgp ключ в буфер обмена
<p align="center">![Копируем ключ](image/9.png)
<p>Вставляем ключ в настройках GitHub
<p align="center">![Вставляем ключ](image/10.png)
Используя введёный email, указываем Git применять его при подписи коммитов
<p align="center">![Продолжаем настройку](image/11.png)
<p>Авторизовываемся через gh
<p align="center">![Авторизация через консоль](image/12.png)
<p>Создаем репозиторий по шаблону
<p align="center">![Создание репозитория](image/13.png)
<p>Настраиваем каталог курса, удаляем и создаем необходимые файлы и каталоги
<p align="center">![Настройка каталога курса](image/14.png)
<p>Отправляем файлы на сервер
<p align="center">![Отправка файлов через git push](image/15.png)

# Выводы

Я изучил идеологию и применение средств контроля версий и освоил умения по работе с git.

