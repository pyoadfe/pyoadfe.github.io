# Обработка и анализ данных физического эксперимента 2021/2022

## [Текущая успеваемость](https://docs.google.com/spreadsheets/d/1eL_OH9g9g9pMIpt96tsPLxfCAzL3OiBRtp3R6uoKqB4/edit?usp=sharing)

## [«Упрощённая» программа курса](https://drive.google.com/file/d/1O1OIo2LqlTYdqpBWnXI1It-zoP8qkLwE/view?usp=sharing)

## Онлайн-составляющая: [Version Control with Git](https://www.coursera.org/learn/version-control-with-git)

## Практические задания
- [Тест по питону](https://classroom.github.com/a/e1FPT_xl)
- [Домашнее задание «Озон»](https://classroom.github.com/a/nAHhA_mo)

## Лекции

### 14.01
Цели и задачи курса.
Алогритм как математический объект.
Понятие эффективного алогритма.
O-нотация.
Лучшая асимптотика не всегда быстрее.
Теоремы об эффективных алгоритмах.

### 21.01
NP-задачи, «задача о рюкзаке», проблема P≠NP.
Пример про кросс-корреляцию астрономических каталогов. Структуры данных.
Вектор (массив), односвязный и двусвязный списки. Сложность операций поиска, вставки и удаления.
Сбалансированные бинарные деревья поиска.

### 28.01
Сбалансированные бинарные деревья поиска. Многомерные kd-деревья. Ассоциативный массив (словарь).
Хеш-таблицы. Хеш-функции. Коллизии и методы их устранения.

### 04.02
Распространённые форматы хранения данных. Сервера управления базами данных и реляционная алгебра.

## Семинары

### 28.01
Дополнительные материалы:
 * [Блокнот с numpy и чтением данных](https://github.com/pyoadfe/seminars/blob/master/1_tables.ipynb)
 * [Задачка про подсчёт слов](https://github.com/pyoadfe/seminars/blob/master/1_list_vs_dict.ipynb)

### 04.02
Дополнительные материалы:
 * [Блокнот с ООП](https://github.com/pyoadfe/seminars/blob/master/oop.ipynb)
 * [Блокнот с pandas](https://github.com/pyoadfe/seminars/blob/master/pandas.ipynb)

## Дополнительные материалы к курсу

### Python

- `ru` [Интерактивный учебник по Python](https://snakify.org/ru/)
- `ru` [Интерактивный задачник по Python](http://pythontutor.ru) — не все примеры решения хороши, но много хороших задач
- `ru` [Игра, в которой герой управляется вашей программой](http://codecombat.com), выберите Python при создании персонажа
- `ru` [Курс Вышки на Coursera](https://www.coursera.org/learn/python-osnovy-programmirovaniya)
- `ru` [Курс на Stepik](https://stepik.org/course/67/)
- [Курс на Codeacademy](https://www.codecademy.com/learn/learn-python-3)
- [Официальный туториал по языку](https://docs.python.org/3/tutorial/index.html) — очень хороший материал для последовательного изучения языка
- `ru` [Изучите Python за Y минут](https://learnxinyminutes.com/docs/ru-ru/python3-ru/) — хороший туториал для быстрого погружения в язык, требуется уверенное владение другим языком программирования
- [Игра для тех, кто уже освоил азы Python](https://py.checkio.org)
- [10 minutes to pandas](https://pandas.pydata.org/pandas-docs/stable/user_guide/10min.html) — короткий туториал по библиотеке pandas от разработчиков

### Install Python

Remember to use Python 3, 3.5 and later is good enough in 2019. You can check python version typing in console `python3 --version` or `import sys; print(sys.version)` in Python itself

#### All platforms
- [Anaconda Python distribution](https://www.anaconda.com/download/) is a good choice for scientific Python programming on every platform. It includes a lot of pre-compiled numerical and scientific packages and `conda` package manager where you can find even more packages, like `astropy` or `scikit-learn`
- [Official Python distribution](https://www.python.org/downloads/): good on Windows or macOS, when you like to build your environment from scratch.

#### macOS
Instead of official Python distribution I recommend to use [Homebrew](http://brew.sh) package manager, type `brew install python`

#### Linux
Probably you already have Python 3, check its version before start. If you haven't use your Linus package manager to install

### Source code editors for Python
- [IDLE](https://docs.python.org/3/library/idle.html): a simple Python source code editor. It is a part of Python standard library, so if you have Python, you probably have IDLE
- [Visual Studio Code](https://code.visualstudio.com) (do not be confused with Visual Studio, they are two different products): a powerful source code editor
- [Spyder](https://www.spyder-ide.org): the scientific Python development environment
- [PyCharm](https://www.jetbrains.com/pycharm/): a powerful Python IDE (integrated development environment). PyCharm is closed source product, but Community edition is free to use and every student and professor can ask for a [free professional version](https://www.jetbrains.com/student/)

### Git

- [GitHub Tutorials](https://guides.github.com) — официальные руководства по использованию <https://github.com>
- `ru` [GitHowTo](https://githowto.com/ru) — хороший курс по Git в командной строке
- `ru` [Git Book](https://git-scm.com/book/ru/v2) — официальный учебник по Git, тоже про командную строку
- [Bitbucket tutorials](https://www.atlassian.com/git/tutorials) — руководства по использованию Git на сайте Bitbucket, сервиса-конкрента GitHub
- [A Quick Introduction to Version Control with Git and GitHub](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1004668)
- ["Commits are snapshots, not diffs"](https://github.blog/2020-12-17-commits-are-snapshots-not-diffs) — как Git хранит данные. Заметка, рассказывающая о внутренностях Git с точки зрения структур данных.
