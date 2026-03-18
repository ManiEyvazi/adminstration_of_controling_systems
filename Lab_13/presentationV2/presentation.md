---
title: "Фильтр пакетов"
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

Получить навыки работы с межсетевым экраном в Linux
и научиться управлять правилами фильтрации пакетов через:

- firewall-cmd (CLI)
- firewall-config (GUI)

\newpage

# Процесс выполнения лабораторной работы

## Определение конфигурации

-

![](image/1.png){ width=50% }

*Рис. 1 — Список зон и служб*

\newpage

## Анализ активной зоны

-.

![](image/2.png){ width=85% }

*Рис. 2 — Параметры зоны public*

\newpage

## Добавление сервиса (временное изменение)

-

![](image/3.png){ width=85% }

*Рис. 3 — Добавление VNC и исчезновение после рестарта*

\newpage

## Добавление сервиса(постоянное изменение)
-.

![](image/4.png){ width=70% }

*Рис. 4 — Добавление VNC permanent*

\newpage

## Добавление порта 2022/TCP

-.

![](image/5.png){ width=50% }

*Рис. 5 — Добавление порта 2022/tcp*

\newpage

## Включение служб

-.

![](image/6.png){ width=85% }

*Рис. 6 — GUI firewall-config services*

\newpage

## Добавление порта

-.

![](image/7.png){ width=80% }

*Рис. 7 — GUI firewall-config port*

\newpage

## Проверка результата

-.

![](image/8.png){ width=50% }

*Рис. 8 — Список активных служб и портов*

\newpage

## Добавление служб

Проверка работы системы.

![](image/9.png){ width=50% }

*Рис. 9 — Добавление служб через GUI*

\newpage

## Проверка конфигурации

-

![](image/10.png){ width=85% }

*Рис. 10 — Итоговая конфигурация*

\newpage

# Выводы по проделанной работе

## Вывод

- Изучены инструменты управления брандмауэром: **firewall-cmd** и **firewall-config**
- Освоены:
  - просмотр зон и разрешённых служб
  - добавление портов и сервисов
  - различие между временной и постоянной конфигурацией
- На практике закреплено применение параметра `--permanent`  
  и активация изменений через `firewall-cmd --reload`