---
# Front matter
lang: ru-RU
title: 'Отчёт'
subtitle: 'по лабораторной работе 4'
author: 'Агеева Анастасия Борисовна'

# Formatting
toc-title: 'Содержание'
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
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

Получение практических навыков работы в консоли с расширенными атрибутами файлов.

# Задание

Лабораторная работа подразумевает получение практических навыков работы в консоли с расширенными атрибутами файлов.

# Выполнение лабораторной работы

1. От имени пользователя guest определите расширенные атрибуты файла /home/guest/dir1/file1 (рис.1).

2. Установите на файл file1 права, разрешающие чтение и запись для владельца файла. (рис.1).

   ![рис.1. Определение расширенных атрибутов, установление прев на file1.](images/1.jpg){ #fig:001 width=60% }

3. Попробуйте установить на файл /home/guest/dir1/file1 расширенный атрибут a от имени пользователя guest (рис.2).

4. Зайдите на третью консоль с правами администратора либо повысьте свои права с помощью команды su. Попробуйте установить расширен- ный атрибут a на файл /home/guest/dir1/file1 от имени суперполь- зователя (рис.2).

   ![рис.2. Установление расширенного атрибута.](images/2.jpg){ #fig:002 width=60% }

5. От пользователя guest проверьте правильность установления атрибута (рис.3).

   ![рис.3. Проверка атрибутов.](images/3.jpg){ #fig:003 width=60% }

6. Выполните дозапись в файл file1 слова «test» (рис.4).

   ![рис.4. Запись в файл слова test и его чтение.](images/4.jpg){ #fig:004 width=60% }

7. Попробуйте удалить файл file1 либо стереть имеющуюся в нём информацию (рис.5).

   ![рис.5. Удаление, переименование файла.](images/5.jpg){ #fig:005 width=60% }

8. Попробуйте установить на файл file1 права, например, запрещающие чтение и за- пись для владельца файла (рис.6).

9. Снимите расширенный атрибут a с файла /home/guest/dirl/file1 от имени суперпользователя (рис.6-7).

   ![рис.6. Установление на file1 прав.](images/6.jpg){ #fig:006 width=60% }

   ![рис.7. Снятие расширенного атрибута и повтор команд.](images/7.jpg){ #fig:007 width=60% }

10. Повторите ваши действия по шагам, заменив атрибут «a» атрибутом «i» (рис.8).

   ![рис.8](images/8.jpg){ #fig:008 width=60% }




# Выводы

В результате выполнения работы я повысила свои навыки использования интерфейса командой строки (CLI), познакомилась на примерах с тем, как используются основные и расширенные атрибуты при разграничении доступа. Имела возможность связать теорию дискреционного разделения доступа (дискреционная политика безопасности) с её реализацией на практике в ОС Linux.
