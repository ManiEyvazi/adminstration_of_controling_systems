---
title: "Управление логическими томами (LVM)"
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

Получить навыки создания, управления и модификации логических томов LVM.

\newpage

# Процесс выполнения лабораторной работы

## Создание физического тома

-

![](image/1.png){ width=85% }

*Рис. 1 — Очистка и разметка диска /dev/sdb*

\newpage

## Проверка VG

-.

![](image/2.png){ width=85% }

*Рис. 2 — Вывод vgs*

\newpage

## Создание файловой системы

-

![](image/3.png){ width=85% }

*Рис. 3 — Создание файловой системы*

\newpage

## Редактирование fstab
-.

![](image/4.png){ width=70% }

*Рис. 4 — Редактирование fstab*

\newpage

## Проверка монтирования	

-.

![](image/5.png){ width=85% }

*Рис. 5 — Монтирование LV*

\newpage

## Добавление нового раздела

-.

![](image/6.png){ width=55% }

*Рис. 6 — Создание /dev/sdb2*

\newpage

## Увеличение VG

-.

![](image/7.png){ width=55% }

*Рис. 7 — Увеличение VG*

\newpage

## Увеличение размера LV

-.

![](image/8.png){ width=85% }

*Рис. 8 — Увеличение LV*

\newpage

## Уменьшение размера LV

Проверка работы системы.

![](image/9.png){ width=60% }

*Рис. 9 — Уменьшение LV*

\newpage

## Создание PV/VG/LV

-

![](image/11.png){ width=85% }

*Рис. 11 — Создание PV, VG и LV*

\newpage

## Настройка fstab

-

![](image/12.png){ width=85% }

*Рис. 12 — Настройка fstab*

\newpage

## Создание нового PV для расширения

-

![](image/14.png){ width=50% }

*Рис. 14 — Создание /dev/sdc2*

\newpage

# Выводы по проделанной работе

## Вывод

Были освоены процедуры работы с LVM:
создание PV, VG, LV, монтирование, расширение и уменьшение томов.
Отработаны навыки управления файловыми системами ext4 и XFS.