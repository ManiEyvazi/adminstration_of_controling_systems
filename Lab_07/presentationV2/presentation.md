---
title: "Управление процессами и заданиями"
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

Получить навыки работы с журналами мониторинга различных событий в системе Linux, используя службы rsyslog и systemd-journald.

\newpage

# Процесс выполнения лабораторной работы

## Мониторинг системных событий

-

![](image/1.png){ width=50% }

*Рис. 1 — Мониторинг /var/log/messages в реальном времени*

\newpage

## Ошибки аутентификации su

-.

![](image/2.png){ width=50% }

*Рис. 2 — Сообщения об ошибках su в журнале*

\newpage

## Использование команды logger

-

![](image/3.png){ width=50% }

*Рис. 3 — Добавление пользовательского сообщения в журнал*

\newpage

## Журнал безопасности /var/log/secure
-.

![](image/4.png){ width=50% }

*Рис. 4 — Просмотр последних записей журнала secure*

\newpage

## Изменение правил rsyslog.conf

-.

![](image/5.png){ width=50% }

*Рис. 5 — Запуск службы httpd и её журнал*

\newpage

## Настройка веб-сервера Apache

-.

![](image/6.png){ width=50% }

*Рис. 6 — Изменение конфигурации httpd.conf*

\newpage

## Настройка ErrorLog syslog:local1

-.

![](image/7.png){ width=50% }

*Рис. 7 — Файл /etc/rsyslog.d/httpd.conf*

\newpage

## Создание файла правил httpd.conf

-.

![](image/8.png){ width=50% }

*Рис. 8 — Файл /etc/rsyslog.d/debug.conf*

\newpage

## Создание файла debug.conf



![](image/9.png){ width=50% }

*Рис. 9 — Сообщение от logger в messages-debug*

\newpage

## Проверка записи отладочных сообщений

-

![](image/10.png){ width=50% }

*Рис. 10 — Просмотр системного журнала*

\newpage

# Выводы по проделанной работе

## Вывод

В ходе лабораторной работы были изучены принципы системного журналирования в Linux.
Были рассмотрены возможности служб rsyslog и systemd-journald, настройка пользовательских правил, регистрация ошибок и отладочной информации.
Освоены команды фильтрации и анализа логов с помощью journalctl, а также способы организации постоянного хранения журналов для долгосрочного мониторинга системы.