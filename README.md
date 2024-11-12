# HalltapeRoadmapDE
<i>Roadmap для Data Engineer | Актуально на 2024-2025г.</i>

Оглавление
- [HalltapeRoadmapDE](#halltaperoadmapde)
    - [0. Деньги](#0-деньги)
    - [1. Кто такой Дата Инженер?](#1-кто-такой-дата-инженер)
    - [2. Курсы](#2-курсы)
    - [3. Github / Git](#3-github--git)
    - [4. Linux / Terminal](#4-linux--terminal)
    - [4. Data Warehouse](#4-data-warehouse)
    - [5. Нормальные формы](#5-нормальные-формы)
    - [6. Модели данных](#6-модели-данных)
    - [7. Data Vault (Hub - Satellite - Link)](#7-data-vault-hub---satellite---link)
    - [999. Hadoop](#999-hadoop)
    - [999. Greenplum](#999-greenplum)
    - [999. Spark](#999-spark)
    - [999. Pet Project](#999-pet-project)
    - [999. Резюме и Работа](#999-резюме-и-работа)

### 0. Деньги
Размер зарплаты зависит от успешности продажи себя на собесе. Если будешь бояться говорить большие суммы, эти суммы будет называть другой более наглый человек. При этом он будет знать меньше тебя, а зарабатывать больше.
С этого момента забудь про справедливость. Её нет.

Зарплатные вилки собраны лично мной на собесах за 2024 год:
| Уровень      | Зарплата на руки      |
|--------------|--------------------|
| Стажер       | 70k - 90k          |
| Джун         | 100k - 150k        |
| Джун+        | 160k - 190k        |
| Мидл        | 200k - 250k        |
| Мидл+       | 260k - 380k        |
| Сеньор и выше | от 380k        |

Учитывайте, что вилки в некоторых компаниях могут быть сильно ниже. Корреляция между размером зарплаты и знаниями не всегда 100%.

>Важно! Нет смысла заниматься раз в неделю. Таким темпом вы никогда не дойдете до конца. Лучше тогда потратьте это время на отпуск, семью, друзей. Иначе вы просто спускаете свою жизнь в никуда.

***

### 1. Кто такой Дата Инженер?
Чтобы понять, кто такой дата инженер и как им стать, посмотри видео!

➜ [Кто такой Data Engineer?](https://youtu.be/75Vu8NqH_cU?si=zYT6U7deVYEPkbmA)


<p align="center">
    <img src="png/de1.jpg" alt="de" width="600"/>
</p>



***
### 2. Курсы
Дальше тебе нужно научиться писать базовые запросы на SQL и на Python. В тренажерах внизу проходи так, как там просят. Не спрашивай зачем, тебе понадобятся эти инструменты в будущем!

Пройди эти три курса SQL и Python

<table>
  <tr>
    <th align="center">Курс</th>
    <th align="center">Продолжительность</th>
  </tr>
  <tr>
    <td align="center"><a href="https://karpov.courses/simulator-sql">SQL с нуля до оконок</a></td>
    <td align="center">≈ 1-2 месяца</td>
  </tr>
  <tr>
    <td align="center"><a href="https://stepik.org/course/58852/syllabus">Python с нуля до базы</a></td>
    <td align="center">≈ 1-2 месяца</td>
  </tr>
  <tr>
    <td align="center"><a href="https://stepik.org/course/68343/syllabus">Продвинутый уровень Python (вложенность, словари, функции)</a></td>
    <td align="center">≈ 1-2 месяца</td>
  </tr>
</table>

>Если задача не получается и ты сидишь с ней уже больше часа, пропускай и переходи к следующей. Потом вернешься и дорешаешь, если будет желание. Не гонись за 100%. Это никто не оценит.
>
***
### 3. Github / Git

<p align="center">
    <img src="png/git_github.png" alt="git" width="600"/>
</p>

Регистрируешься на Github и подключаешь его к своему ПК

➜ [Работа с github / git](Git/README.md)

***
### 4. Linux / Terminal
<p align="center">
    <img src="png/BASH_logo.png" alt="linux" width="600"/>
</p>

Пробуешь привыкнуть и запомнить работу с этими командами в терминале

➜ [Работа с Linux / Terminal](Linux/README.md)

***
### 4. Data Warehouse

<p align="center">
    <img src="png/data_warehouse.png" alt="dwh" width="600"/>
</p>


Нужно понимать, что такое хранилище данных, какие они бывают, чем отличаются и, как в целом можно грузить данные. Обязательно читай теорию!

➜ [Теория по Data Warehouse](DWH/README.md)


***
### 5. Нормальные формы

<p align="center">
    <img src="png/normal_table.jpg" alt="nf" width="600"/>
</p>


Важная тема про нормализацию таблиц. Всегда спрашивают на собесах. За это надо шарить.

➜ [Нормальные формы](NF/README.md)


***
### 6. Модели данных

<p align="center">
    <img src="png/models_data.jpg" alt="nf" width="600"/>
</p>

Для собесов и в будущем на работе вам надо шарить за модели данных. Читаем и обязательно изучаем SCD по ссылке ниже!

➜ [Модели данных](DM/README.md)


***
### 7. Data Vault (Hub - Satellite - Link)

<p align="center">
    <img src="png/dv.png" alt="nf" width="600"/>
</p>

Не факт, что на первой работе вы будете сразу строить Data Vault. Это вообще настолько не факт, что может остаться у вас в теории еще на год вперед. Но на собесах спросить могут. Более того, вам могут дать тестовое на то, чтобы построить простенькую модельку на базе Data Vault. Грубо говоря – это все про то, как связать таблицы между собой...

Читаем конспект ➜ [Data Vault](files/data_vault.pdf)


***
### 999. Hadoop

<p align="center">
    <img src="png/hadoop_logo.png" alt="hdfs" width="600"/>
</p>


На некоторых проектах в качестве хранилища будет HDFS (Hadoop). Инфы из видоса снизу будет достаточно, чтобы успешно ответить на вопросы на собеседовании.

Смотри видео здесь ➜ [HDFS | Что это такое и как оно работает? [Hadoop HDFS]](https://youtu.be/ySDGh_1d87g)

Презентация из видео ➜ [HDFS](files/deep_dive_hdfs_pdf.pdf)

***
### 999. Greenplum

<p align="center">
    <img src="./png/gp_logo.png" width="640" height="320"/>
</p>

Greenplum будет в 50% вакансиях на DE. Остальные будут сидеть на Hadoop + Spark. На первых порах рекомендую **базово освоить** все три, но окунуться поглубже лишь в один на выбор (Spark | Greenplum). Если хватит сил на освоение обоих, флаг вам в руки!

➜ [Теория по Greenplum](GREENPLUM/README.md)

➜ [Простое видео о Greenplum](https://www.youtube.com/watch?v=rLG9Z_HcKPY)

Презентация из видео ➜ [Greenplum](files/greenplum.pdf)

***
### 999. Spark

<p align="center">
    <img src="png/spark_logo.png" alt="spark" width="600"/>
</p>


Spark изучайте только **после** **того**, как научились базово кодить на **python** и **SQL**. Без них будет очень **сложно** и **непонятно**.

Смотри видео здесь ➜ [Что такое Spark и как им пользоваться?](h)


***
### 999. Pet Project

<p align="center">
    <img src="png/pet_project.png" alt="pet_project" width="600"/>
</p>

Все пет проекты – это на самом деле маленькие копии реальных задач. Поэтому чем глубже вы разберетесь в инструментах, тем легче и свободнее вам будет на собесе и на работе. О пет проекте вы можете рассказывать, что он был развернут у вас на предыдущем месте работы. По факту, может вы этого и не делали, но крайне рекомендую именно адаптировать хотя бы часть каких-то задач. Вам точно должно повезти! Ниже ссылка на примеры проектов:

 ➜ [Pet Projects](PET_PROJECT/README.md)

> Будет круто, если ты напишешь свой собственный проект и запушишь его к себе на github. Это сильно поможет уложить в голове многие концепции при работы с данными


***
### 999. Резюме и Работа

<p align="center">
    <img src="png/resume.jpg" width="500"/>
</p>

Все врут. Все приукрашивают. Это сделка двух сторон. Ваша задача продать себя подороже. Задача компании купить вас подешевле, да и выбрать по способнее. По ссылке ниже читаем **ЧИТ КОДЫ** по поиску работы, зарплатным ожиданиям и оформлению резюме.

➜ [Как составить резюме?](h)

➜ [Как найти работу?](JOB/README.md)