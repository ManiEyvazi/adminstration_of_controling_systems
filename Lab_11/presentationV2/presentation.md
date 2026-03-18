---
title: " Управление загрузкой системы (GRUB2)"
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

Получить навыки работы с загрузчиком системы GRUB2 в Linux.

\newpage

# Процесс выполнения лабораторной работы

## Изменение параметров GRUB2

-

![](image/1.png){ width=70% }

*Рис. 1 — Редактирование файла /etc/default/grub*

\newpage

## Генерация конфигурации GRUB2

-.

![](image/2.png){ width=85% }

*Рис. 2 — Создание новой конфигурации GRUB2*

\newpage

## Меню загрузки системы

-

![](image/3.png){ width=85% }

*Рис. 3 — Меню загрузки GRUB*

\newpage

## Вход в режим восстановления
-.

![](image/4.png){ width=70% }

*Рис. 4 — Редактирование строки загрузки (rescue mode)*

\newpage

## Активные юниты в rescue mode

-.

![](image/5.png){ width=85% }

*Рис. 5 — Список активных юнитов в rescue mode*

\newpage

## Вход в emergency mode

-.

![](image/6.png){ width=85% }

*Рис. 6 — Редактирование строки загрузки (emergency mode)*

\newpage

## Активные службы в emergency mode

-.

![](image/7.png){ width=80% }

*Рис. 7 — Список юнитов в emergency mode*

\newpage

## Загрузка с параметром rd.break

-.

![](image/8.png){ width=85% }

*Рис. 8 — Редактирование строки загрузки с параметром rd.break*

\newpage

## Попытка сброса пароля root

Проверка работы системы.

![](image/9.png){ width=85% }

*Рис. 9 — Попытка сброса пароля root*

\newpage


# Выводы по проделанной работе

## Вывод

В ходе работы были изучены основные приёмы настройки и модификации загрузчика GRUB2 в операционной системе Linux.
Были рассмотрены процессы изменения параметров конфигурационного файла /etc/default/grub, генерации нового файла /boot/grub2/grub.cfg и проверка результатов при загрузке системы.
Дополнительно были исследованы режимы rescue и emergency, а также порядок действий при сбросе пароля суперпользователя root.