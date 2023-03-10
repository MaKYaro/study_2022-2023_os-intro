---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
author:
  - Клюкин М. А.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - НКАбд-02-22

## i18n babel
babel-lang: russian
babel-otherlangs: english

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


## Цель

Преобрести практические навыки взаимодействия с системой посредством командной строки   
Выполнить задания лабораторной работы  

## Задача

1. Определить полное имя домашнего каталога.   
2. Выполнить команду ls с различными опциями согласно заданию.   
3. Выполнить команды mkdir и rm с различными опциями согласно заданию  
4. Определить опцию команды ls для просмотра содержимого каталога и его подкаталогов
5. Определить набор опций команды ls для сортировки списка содержимого каталога по времени последнего изменения.
6. Посмотреть описание команд cd, pwd, mkdir, rmdir, rm.
7. Выполнить модификацию команд

## Теоретическое введение

Командная строка -- это программа, которая позволяет управлять компьютером путем ввода текстовых команд с клавиатуры.  
Командная строка является основным интерфейсом взаимодействия пользователя с операционной системой UNIX во всех ее модификациях.  
Команды, введенные пользователем, интерпретируются и испольняются специальной программой -- командной оболочкой.

# Выполнение лабораторной

## Первый шаг

Определили полное имя домашнего каталога с помощью команды pwd

![Имя домашнего каталога](image/Screenshot_from_2023-03-04_11-34-25.png){#fig:001 width=70%}

## Второй шаг

Вывели на экран содержимое каталога /tmp  
Определили, есть ли в каталоге /var/spool подкаталог с именем cron  
Перешли в домашний каталог и вывели на экран его содержимое  

## Второй шаг

![Работа с командой ls](image/Screenshot_from_2023-03-04_11-36-22.png){#fig:002 width=70%}

## Второй шаг

Определили владельца файлов и каталогов в домашнем каталоге

![Владелец файлов и каталогов](image/Screenshot_from_2023-03-04_11-36-49.png){#fig:003 width=70%}


## Третий шаг

В домашенм каталоге создали каталог newdir, а в нем подкаталог morefun  
Там же создали и удалили одной командой три новых каталога letters, memos, misk  
Удалили каталог ~/newdir, проверили, что он был удален  

## Третий шаг

![Создание и удаление катлогов](image/Screenshot_from_2023-03-04_11-38-23.png){#fig:004 width=70%}

## Четвертый шаг

Определили опцию команды ls для просмотра содержимого подкаталогов  

![Определение опции команды ls](image/Screenshot_from_2023-03-04_11-39-17.png){#fig:005 width=70%}

## Пятый шаг

Определили набор опций для сортировки списка по времени последнего изменения и вывода развернутого описания.  

![Определение опции команды ls](image/Screenshot_from_2023-03-04_11-40-36.png){#fig:006 width=70%}

## Шестой шаг

Командой man вывели описание для команд cd, pwd, mkdir, rmdir, rm  

## Шестой шаг

![Описание команды cd](image/Screenshot_from_2023-03-04_11-42-53.png){#fig:007 width=70%}

## Шестой шаг

![Описание команды pwd](image/Screenshot_from_2023-03-04_11-43-24.png){#fig:008 width=70%}

## Шестой шаг

![Описание команды mkdir](image/Screenshot_from_2023-03-04_11-43-51.png){#fig:009 width=70%}

## Шестой шаг

![Описание команды rmdir](image/Screenshot_from_2023-03-04_11-44-26.png){#fig:010 width=70%}

## Шестой шаг

![Описание команды rm](image/Screenshot_from_2023-03-04_11-44-54.png){#fig:011 width=70%}

## Седьмой шаг

Исполнили и модифицировали несколько команд из буфера команд

![Модификация команд](image/Screenshot_from_2023-03-04_11-47-20.png){#fig:012 width=70%}

## Седьмой шаг

![Модификация команд](image/Screenshot_from_2023-03-04_11-48-25.png){#fig:013 width=70%}

## Выводы 

 Приобрели практические навыки взаимодействия с системой посредством командной строки.  
 Выполнили задания лабораторной.  
