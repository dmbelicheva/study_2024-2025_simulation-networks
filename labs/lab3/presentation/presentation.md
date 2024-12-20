---
## Front matter
lang: ru-RU
title: Лабораторная работа № 3
subtitle: Измерение и тестирование пропускной способности сети. Воспроизводимый эксперимент
author:
  - Беличева Д. М.
institute:
  - Российский университет дружбы народов, Москва, Россия

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Беличева Дарья Михайловна
  * студентка
  * Российский университет дружбы народов
  * [1032216453@pfur.ru](mailto:1032216453@pfur.ru)
  * <https://dmbelicheva.github.io/ru/>

:::
::: {.column width="25%"}

![](./image/belicheva.jpg)

:::
::::::::::::::

## Цель работы

Основной целью работы является знакомство с инструментом для измерения
пропускной способности сети в режиме реального времени — iPerf3, а также
получение навыков проведения воспроизводимого эксперимента по измерению
пропускной способности моделируемой сети в среде Mininet.

## Задание

1. Воспроизвести посредством API Mininet эксперименты по измерению пропускной способности с помощью iPerf3.
2. Построить графики по проведённому эксперименту.

## Выполнение лабораторной работы

![Копирование файла emptynet.py](image/1.png){#fig:001 width=70%}

## Выполнение лабораторной работы

![Содержание файла lab_iperf3_topo.py](image/2.png){#fig:002 width=40%}

## Выполнение лабораторной работы

![Создание топологии и ее основные параметры](image/3.png){#fig:003 width=50%}

## Выполнение лабораторной работы

![Изменение скрипта lab_iperf3_topo.py](image/4.png){#fig:004 width=65%}

## Выполнение лабораторной работы

![Проверка работы внесенных изменений](image/5.png){#fig:005 width=70%}

## Выполнение лабораторной работы

![Настройка параметров производительности](image/6.png){#fig:006 width=50%}

## Выполнение лабораторной работы

![Запуск скрипта с настройкой параметров производительности и без нее](image/7.png){#fig:007 width=50%}

## Выполнение лабораторной работы

![Создание копии скрипта lab_iperf3_topo2.py](image/8.png){#fig:008 width=70%}

## Выполнение лабораторной работы

![Изменен ия кода в скрипте lab_iperf3.py](image/9.png){#fig:009 width=50%}

## Выполнение лабораторной работы

![Запуск скрипта lab_iperf3.py](image/10.png){#fig:010 width=70%}

## Выполнение лабораторной работы

![Создание Makefile](image/11.png){#fig:011 width=70%}

## Выполнение лабораторной работы

![Проверка работы Makefile](image/12.png){#fig:012 width=45%}

## Выводы

В результате выполнения данной лабораторной работы я познакомилась с инструментом для измерения
пропускной способности сети в режиме реального времени — iPerf3, а также
получила навыки проведения воспроизводимого эксперимента по измерению
пропускной способности моделируемой сети в среде Mininet.

## Список литературы

1. Mininet [Электронный ресурс]. Mininet Project Contributors. URL: http://mininet.org/ (дата обращения: 17.11.2024).
2. IPerff [Электронный ресурс]. URL: https://iperf.fr/.