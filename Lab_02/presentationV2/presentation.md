---
title: "Управление пользователями и группами"
author: "Эйвази Мани"
date: "13 марта 2026"
geometry: landscape
toc: true
fontsize: 12pt
header-includes:
  - \usepackage{graphicx}
  - \usepackage{float}
  - \usepackage{caption}
  - \captionsetup{justification=centering}
---

# Цели и задачи работы

## Цель лабораторной работы

Получение практических навыков управления учётными записями пользователей и групп в операционной системе Linux.

\newpage

# Процесс выполнения лабораторной работы

## Определение текущего пользователя

-

![](image/1.png){ width=85% }

*Рис. 1 — Команды whoami и id*

\newpage

## Переключение на root

-

![](image/1.png){ width=85% }

*Рис. 1 — Переход к пользователю root*

\newpage

## Файл /etc/sudoers

-

![](image/2.png){ width=85% }

*Рис. 2 — Открытие /etc/sudoers через visudo*

\newpage

## Создание пользователя alice
-.

![](image/3.png){ width=70% }

*Рис. 3 — Создание пользователя alice*

\newpage

## Создание пользователя bob

-.

![](image/3.png){ width=85% }

*Рис. 3 — Создание пользователя bob*

\newpage

## Настройка параметров useradd

-.

![](image/4.png){ width=60% }

*Рис. 4 — Файл /etc/login.defs*

\newpage

## Каталог /etc/skel

-.

![](image/5.png){ width=80% }

*Рис. 5 — Каталог /etc/skel*

\newpage

## Создание пользователя carol

-.

![](image/6.png){ width=85% }

*Рис. 6 — Создание пользователя carol*

\newpage

## Домашний каталог carol

Проверка работы системы.

![](image/7.png){ width=85% }

*Рис. 7 — Домашний каталог carol*

\newpage

## Файл /etc/shadow

-

![](image/8.png){ width=85% }

*Рис. 8 — Запись carol в /etc/shadow*

\newpage

## Создание групп

-

![](image/9.png){ width=85% }

*Рис. 9 — Работа с группами*

\newpage

# Выводы по проделанной работе

## Вывод

В ходе лабораторной работы были изучены основные механизмы управления пользователями и группами в Linux.  
Получены практические навыки создания учётных записей, настройки прав доступа, управления паролями и группами, а также работы с ключевыми системными конфигурационными файлами.