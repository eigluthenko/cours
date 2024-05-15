---
## Front matter
title: "Отчет о прохождении 2 этапа внешних курсов"
subtitle: "Работа на сервере"
author: "Глущенко Евгений Игоревич, НКАбд-02-23"

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

Ознакомиться с функционалом операционной системы Linux.

# Задание

Просмотреть видео и на основе полученной информации пройти тестовые задания.

# Теоретическое введение

Линукс - в части случаев GNU/Linux — семейство Unix-подобных операционных систем на базе ядра Linux, включающих тот или иной набор утилит и программ проекта GNU, и, возможно, другие компоненты. Как и ядро Linux, системы на его основе, как правило, создаются и распространяются в соответствии с моделью разработки свободного и открытого программного обеспечения. Linux-системы распространяются в основном бесплатно в виде различных дистрибутивов — в форме, готовой для установки и удобной для сопровождения и обновлений, — и имеющих свой набор системных и прикладных компонентов, как свободных, так и проприетарных. 

# Выполнение лабораторной работы

2 Этап: (рис. @fig:001, @fig:002, @fig:003, @fig:004, @fig:005, @fig:006, @fig:007, @fig:008, @fig:009, @fig:010, @fig:011, @fig:012, @fig:013, @fig:014, @fig:015, @fig:016, @fig:017, @fig:018, @fig:019, @fig:020, @fig:021, @fig:022, @fig:023, @fig:024).

![Задание 1](image/1.png){#fig:001 width=70%}

Компьютер, размещенный в дата-центре, который можно контролировать извне через интернет-соединение, известен как удаленный сервер. Обычно удаленные серверы используются для хранения веб-сайтов, приложений, баз данных и других служб, которые необходимы для функционирования сайта или рабочих процессов компании. С помощью протоколов удаленного доступа, таких как RDP, VNC или SSH, пользователи могут подключаться к удаленным серверам.

![Задание 2](image/2.png){#fig:002 width=70%}

Только id_rsa.pub, ведь он является открытым.

![Задание 3](image/3.png){#fig:003 width=70%}

-r = Recursively copy entire directories. Note that scp follows symbolic links encountered in the tree traversal.

![Задание 4](image/4.png){#fig:004 width=70%}

Во-первых, надо убедитья, что устройство не может установить соединение с сервером. Во-вторых, проверить, известно ли устройству о существовании программы.

![Задание 5](image/5.png){#fig:005 width=70%}

FileZilla — свободный многоязычный проект, посвящённый приложениям для FTP. Включает в себя отдельное приложение «FileZilla Client» (являющееся FTP-клиентом), и «FileZilla Server». Приложения публикуются с открытым исходным кодом для Windows, macOS и Linux. Клиент поддерживает FTP, SFTP, и FTPS (FTP через SSL/TLS) и имеет настраиваемый интерфейс с поддержкой смены тем оформления.

![Задание 6](image/6.png){#fig:006 width=70%}

1. Настроить сервер, чтобы он поддерживал вывод информации на экран компьютера

2. Проверить, есть ли другая версия этой программы (специально для терминала)


![Задание 7](image/7.png){#fig:007 width=70%}


![Задание 8](image/8.png){#fig:008 width=70%}

FastQC supports files in the following formats

FastQ (all quality encoding variants)
Casava FastQ files*
Colorspace FastQ
GZip compressed FastQ
SAM
BAM
SAM/BAM Mapped only (normally used for colorspace data)


![Задание 9](image/9.png){#fig:009 width=70%}

-align
Do full multiple alignment.


![Задание 10](image/10.png){#fig:010 width=70%}

Ctrl+Z - приостанавливает процесс.
Ctrl+С - завершает процесс.


![Задание 11](image/11.png){#fig:011 width=70%}


![Задание 12](image/12.png){#fig:012 width=70%}

Отсутствие захвата сигнала процессом приводит к уничтожению процесса. Поэтому это используется для завершения работы процесса в корректном режиме. Команда "kill -9" отправляет сигнал уничтожения для немедленного завершения любого процесса по PID или имени процесса. Это насильственный способ завершить набор процессов.


![Задание 13](image/13.png){#fig:013 width=70%}

Команда kill шлёт сигнал о завершении процесса. Но программа обрабатывает сигналы только когда она исполняется, пока она остановлена она не может обработать сигнал и приступит к его обработке только после продолжения работы. 

![Задание 14](image/14.png){#fig:014 width=70%}

Остановленная программа не потребляет CPU.

![Задание 15](image/15.png){#fig:015 width=70%}

Приложение остается в оперативной памяти, поэтому оно будет занимать столько же оперативной памяти, сколько до постановки на паузу.

![Задание 16](image/16.png){#fig:016 width=70%}


![Задание 17](image/17.png){#fig:017 width=70%}


![Задание 18](image/18.png){#fig:018 width=70%}

echo "306174 reads; of these:
  306174 (100.00%) were unpaired; of these:
    11 (0.00%) aligned 0 times
    305580 (99.81%) aligned exactly 1 time
    583 (0.19%) aligned >1 times
100.00% overall alignment rate" > bowtie.log

![Задание 19](image/19.png){#fig:019 width=70%}


![Задание 20](image/20.png){#fig:020 width=70%}

exit завершает работу tmux

![Задание 21](image/21.png){#fig:021 width=70%}

Мы заходили на сервер с терминала, который и потом закрыли, а tmux будет дальше продолжать свою работу на сервере.


![Задание 22](image/22.png){#fig:022 width=70%}

Ещё появится предупреждение о том, что работа завершится. 

![Задание 23](image/23.png){#fig:023 width=70%}


Ctrl+b , - переименовать текущее окно;


![Задание 24](image/24.png){#fig:024 width=70%}


# Выводы

Я просмотрел курс и понял как работать с сложными командами в Линукс.

# Список литературы{.unnumbered}

1. Введение в Linux

::: {#refs}
:::
