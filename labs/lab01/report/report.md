---
## Front matter
title: "Лабораторная работа № 1"
subtitle: "Установка и конфигурация операционной системы на виртуальную машину"
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

Приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Выполнение лабораторной работы

Создаем новую виртуальную машину в virtualbox
<p align="center">![Создание новой виртуальной машины](image/1.png)
<p>Выделяем нужное количество оперативной памяти и ядер процессора
<p align="center">![Выделяем ресурсы](image/2.png)
<p>Выделяем нужное количество памяти для виртуального диска
<p align="center">![Выделяем память](image/3.png)
<p>Запускаем операционную систему
<p align="center">![Запуск sway](image/5.png)
<p>Заходим в программу установки Anaconda
<p align="center">![Anaconda](image/4.png)
<p>Выбираем диск в котором будет установлена ос
<p align="center">![Выбор диска](image/7.png)
<p>Создаем суперпользователя
<p align="center">![Создание суперпользователя](image/8.png)
<p>Создаем учетную запись
<p align="center">![Создание учетной записи](image/9.png)
<p>Ждем завершения установки
<p align="center">![Завершение установки](image/10.png)
<p>Вынимаем загрузочный диск
<p align="center">![Вынимаем диск](image/11.png)
<p>Запускаем терминал
<p align="center">![Терминал](image/12.png)
<p>Переключаемся на роль супер-пользователя
<p align="center">![Используем sudo -i](image/13.png)
<p>Обновляем все пакеты
<p align="center">![Обновление пакетов](image/14.png)
<p>Устанавливаем программы для удобства работы в консоли
<p align="center">![Установка программ](image/15.png)
<p>Устанавливаем программное обеспечение для автоматического обновления
<p align="center">![Установка по](image/16.png)
<p>Запускаем таймер
<p align="center">![Запуск таймера](image/17.png)
<p>Делаем изменения в файле config через nano
<p align="center">![Изменяем значения](image/18.png)
<p>Перезапускаем машину
<p align="center">![Reboot](image/19.png)
<p>Запускаем терминальный мультиплексор
<p align="center">![tmux](image/20.png)
<p>Переключаемся на супер-пользователя
<p align="center">![Sudo -i](image/13.png)
<p>Устанавливаем средства разработки
<p align="center">![Установка средств](image/22.png)
<p>Устанавливаем пакет DKMS
<p align="center">![Установка пакета](image/23.png)
<p>Подключаем образ диска дополнений гостевой ОС
<p align="center">![Подключение образа](image/24.png)
<p>Подмонтируем диск
<p align="center">![Подмонтаж](image/25.png)
<p>Устанавливаем драйвера
<p align="center">![Установка драйверов](image/26.png)
<p>Перезапускаем машину
<p align="center">![Reboot](image/19.png)
<p>Запускаем терминальный мультиплексор
<p align="center">![tmux](image/20.png)
<p>Создаем конфигурационный файл и редактируем его
<p align="center">![Редактируем в nano](image/30.png)
<p>Переключаемся на супер-пользователя
<p align="center">![Sudo -i](image/13.png)
<p>Редактируем конфигурационный файл
<p align="center">![Редактируем в nano](image/32.png)
<p>Перезапускаем машину
<p align="center">![Reboot](image/19.png)
<p>Запускаем терминальный мультиплексор
<p align="center">![tmux](image/20.png)
<p>Переключаемся на супер-пользователя
<p align="center">![Sudo -i](image/13.png)
<p>Устанавливаем имя хоста
<p align="center">![Установка имя хоста](image/34.png)
<p>Добавляем пользователя в группу vboxsf
<p align="center">![Добавление пользователя](image/35.png)
<p>Перезапускаем машину
<p align="center">![Reboot](image/19.png)
<p>Запускаем терминальный мультиплексор
<p align="center">![tmux](image/20.png)
<p>Переключаемся на супер-пользователя
<p align="center">![Sudo -i](image/13.png)
<p>Устанавливаем pandoc
<p align="center">![Установка pandoc](image/36.png)
<p>Разархивируем pandoc и помещаем в каталог /usr/local/bin.
<p align="center">![Разархивировка](image/37.png)
<p align="center">![Перемещение](image/38.png)
<p>Устанавливаем texlive
<p align="center">![Установка texlive](image/39.png)

# Домашнее задание

Выполнение домашнего задания
<p align="center">![Получение нужной информации через dmesg | grep -i](image/40.png)

# Выводы

Я приобрел практические навыки установки операционной системы на виртуальную машину

