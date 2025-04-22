---
title: Лабораторная работа №12
subtitle: Настройка NAT

author:
  - Замбалова Д.В.
institute:
  - Российский университет дружбы народов, Москва, Россия
lang: ru-RU
babel-lang: russian
babel-otherlangs: english
fonttheme: professionalfonts
mainfont: DejaVu Sans
sansfont: DejaVu Sans
monofont: DejaVu Sans Mono
theme: metropolis
aspectratio: 169
section-titles: true
toc: false
slide_level: 2
header-includes:
  - \usepackage{polyglossia}
  - \setdefaultlanguage{russian}
  - \setotherlanguage{english}
  - \usepackage{fontspec}
  - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
  - \makeatletter
  - \beamer@ignorenonframefalse
  - \makeatother
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Замбалова Дина Владимировна
  * студентка
  * Российский университет дружбы народов
  * [1132226536@pfur.ru](mailto:1132226536@pfur.ru)
  * <https://github.com/dvzambalova>

:::
::: {.column width="25%"}

:::
::::::::::::::

# Цель работы

Приобрести практические навыки по настройке доступа локальной сети к внешней сети посредством NAT.

# Задание

1. Сделать первоначальную настройку маршрутизатора provider-gw-1 и коммутатора provider-sw-1 провайдера: задать имя, настроить доступ по
паролю и т.п.
2. Настроить интерфейсы маршрутизатора provider-gw-1 и коммутатора
provider-sw-1 провайдера.
3. Настроить интерфейсы маршрутизатора сети «Донская» для доступа к сети
провайдера.
4. Настроить на маршрутизаторе сети «Донская» NAT с правилами.
5. Настроить доступ из внешней сети в локальную сеть организации.
6. Проверить работоспособность заданных настроек.
7. При выполнении работы необходимо учитывать соглашение об именовании.

# Выполнение лабораторной работы

![Первоначальная настройка маршрутизатора provider-dvzambalova-gw-1](image/1.png){#fig:001 width=70%}

# Выполнение лабораторной работы

![Первоначальная настройка коммутатора provider-dvzambalova-sw-1](image/2.png){#fig:002 width=70%}

# Выполнение лабораторной работы

![Настройка интерфейсов маршрутизатора provider-dvzambalova-gw-1](image/3.png){#fig:003 width=70%}

# Выполнение лабораторной работы

![Настройка интерфейсов коммутатора provider-dvzambalova-sw-1](image/4.png){#fig:004 width=50%}

# Выполнение лабораторной работы

![Настройка интерфейсов маршрутизатора msk-donskaya-dvzambalova-gw-1](image/5.png){#fig:005 width=50%}

# Выполнение лабораторной работы

![Проверка доступности маршрутизатора](image/6.png){#fig:006 width=70%}

# Выполнение лабораторной работы

![Настройка пула адресов для NAT](image/7.png){#fig:007 width=70%}

# Выполнение лабораторной работы

![Настройка списка доступа для NAT](image/8.png){#fig:008 width=70%}

# Выполнение лабораторной работы

![Настройка NAT](image/9.png){#fig:009 width=70%}

# Выполнение лабораторной работы

![Проверка доступности маршрутизаторов](image/10.png){#fig:010 width=45%}

# Выполнение лабораторной работы

![Настройка доступа из Интернета](image/11.png){#fig:011 width=70%}

# Выполнение лабораторной работы

![Добавление ноутбука на территорию Интернет](image/12.png){#fig:012 width=70%}

# Выполнение лабораторной работы

![Задание статического ip-адреса](image/12_2.png){#fig:013 width=70%}

# Выполнение лабораторной работы

![Задание gateway-адреса](image/12_1.png){#fig:014 width=70%}

# Выполнение лабораторной работы

![Проверка доступа из Интернета по ftp](image/13.png){#fig:015 width=40%}

# Выполнение лабораторной работы

![Проверка доступа из Интернета к web-серверу](image/14.png){#fig:016 width=70%}

# Выполнение лабораторной работы

![Доступ dep-donskaya-dvzambalova-1 к 192.0.2.13](image/15.png){#fig:017 width=70%}

# Выполнение лабораторной работы

![Доступ dk-donskaya-dvzambalova-1 к www.yandex.ru](image/16.png){#fig:018 width=70%}

# Выполнение лабораторной работы

![Доступ dk-donskaya-dvzambalova-1 к stud.rudn.university](image/17.png){#fig:019 width=70%}

# Выполнение лабораторной работы

![Доступ adm-donskaya-dvzambalova-1 к www.rudn.ru](image/18.png){#fig:020 width=70%}

# Выводы

В результате выполнения данной лабораторной работы я приобрела практические навыки по настройке доступа локальной сети к внешней сети посредством NAT.

# {.standout}

Спасибо за внимание!
