---
## Front matter
lang: ru-RU
title: Лабораторная работа №2
subtitle: Первоначальна настройка git
author:
  - Югай.А.В.
institute:
  - Российский университет дружбы народов, Москва, Россия

## i18n babel
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

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Югай Александр Витальевич
  * Студент
  * Российский университет дружбы народов
  * [1132230302@pfur.ru]

:::
::: {.column width="30%"}


:::
::::::::::::::

## Цель работы

Изучить идеологию и применение средств контроля версий.
Освоить умения по работе с git.

# Выполнение лабораторной работы

## Для начала устанавливаем пакеты git 

Для начала устанавливаем пакеты git 
<p align="center">![Устанавливаем git](image/1.png)

## Начинаем настройку git

<p>Задаем имя и email владельца репозитория
<p align="center">![Начало настройки](image/2.png)

## Настраиваем utf-8

<p>Настраиваем utf-8
<p align="center">![Настройка utf-8](image/3.png)

## Задаем имя для начальной ветки, параметр autocrlf и safecrlf

<p>Задаем имя для начальной ветки, параметр autocrlf и safecrlf
<p align="center">![Настройка начальной ветки и параметров](image/4.png)

## Создаем ключи ssh по алгоритмам rsa и ed25519

<p>Создаем ключи ssh по алгоритмам rsa и ed25519
<p align="center">![rsa](image/5.png)
<p align="center">![ed25519](image/6.png)

## Генерируем ключ pgp

<p>Генерируем ключ pgp
<p align="center">![pgp ключ](image/7.png)

## Выводим список созданных нами ключей и копируем отпечаток приватного ключа

<p>Выводим список созданных нами ключей и копируем отпечаток приватного ключа
<p align="center">![Вывод ключей](image/8.png)

## Копируем pgp ключ в буфер обмена

<p>Копируем pgp ключ в буфер обмена
<p align="center">![Копируем ключ](image/9.png)

## Вставляем ключ в настройках GitHub

<p>Вставляем ключ в настройках GitHub
<p align="center">![Вставляем ключ](image/10.png)

## Используя введёный email, указываем Git применять его при подписи коммитов

Используя введёный email, указываем Git применять его при подписи коммитов
<p align="center">![Продолжаем настройку](image/11.png)

## Авторизовываемся через gh

<p>Авторизовываемся через gh
<p align="center">![Авторизация через консоль](image/12.png)

## Создаем репозиторий по шаблону

<p>Создаем репозиторий по шаблону
<p align="center">![Создание репозитория](image/13.png)

## Настраиваем каталог курса, удаляем и создаем необходимые файлы и каталоги

<p>Настраиваем каталог курса, удаляем и создаем необходимые файлы и каталоги
<p align="center">![Настройка каталога курса](image/14.png)

## Отправляем файлы на сервер

<p>Отправляем файлы на сервер
<p align="center">![Отправка файлов через git push](image/15.png)

## Выводы

Я изучил идеологию и применение средств контроля версий и освоил умения по работе с git.
