---
title: Лабораторная работа №11
subtitle: Настройка NAT. Планирование

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

Провести подготовительные мероприятия по подключению локальной сети
организации к Интернету.

# Задание

1. Построить схему подсоединения локальной сети к Интернету;
2. Построить модельные сети провайдера и сети Интернет;
3. Построить схемы сетей L1, L2, L3;
4. При выполнении работы необходимо учитывать соглашение об именовании.

# Выполнение лабораторной работы

: Распределение ip-адресов модельного Интернета {#tbl:ip}

| IP-адреса     | Примечание            |
|---------------|-----------------------|
| 192.0.2.1     | provider-gw-1         |
| 192.0.2.11    | www.yandex.ru         |
| 192.0.2.12    | stud.rudn.university  |
| 192.0.2.13    | esystem.pfur.ru       |
| 192.0.2.14    | www.rudn.ru           |

# Выполнение лабораторной работы

![Схема сети с NAT](image/1.png){#fig:001 width=50%}

# Выполнение лабораторной работы

![Схема L1 сети с выходом в Интернет](image/2.png){#fig:002 width=40%}

# Выполнение лабораторной работы

![Схема L2 сети с выходом в Интернет](image/3.png){#fig:003 width=40%}

# Выполнение лабораторной работы

![Схема L3 сети с выходом в Интернет](image/4.png){#fig:004 width=45%}

# Выполнение лабораторной работы

![Размещение новых устройств](image/5.png){#fig:005 width=70%}

# Выполнение лабораторной работы

![Схема сети в физической рабочей области Packet Tracer](image/6.png){#fig:006 width=70%}

# Выполнение лабораторной работы

![Медиаконвертер с модулями PT-REPEATER-NM-1FFE и PT-REPEATER-NM-1CFE](image/7.png){#fig:007 width=50%}

# Выполнение лабораторной работы

![Оборудование в здании сети провайдера](image/8.png){#fig:008 width=50%}

# Выполнение лабораторной работы

![Оборудование в здании сети модельного Интернета](image/9.png){#fig:009 width=50%}

# Выполнение лабораторной работы

![Схема сети с выходом в Интернет](image/10.png){#fig:010 width=50%}

# Выполнение лабораторной работы

![Задание адреса шлюза](image/11.png){#fig:011 width=65%}

# Выполнение лабораторной работы

![Задание ip-адреса](image/12.png){#fig:012 width=65%}

# Выполнение лабораторной работы

![Добавление DNS-записей](image/13.png){#fig:013 width=50%}

# Выводы

В процессе выполнения данной лабораторной работы я провела подготовительные мероприятия по подключению локальной сети организации к Интернету.

# {.standout}

Спасибо за внимание!
