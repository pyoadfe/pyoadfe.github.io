# Обработка физических данных

## [Текущая успеваемость](https://docs.google.com/spreadsheets/d/1vDz97gQo4BwihAs9YOOjwkPfIMiGrU0guuuDAC9_Sa8/edit?usp=sharing)

## Онлайн-составляющая: [Version Control with Git](https://www.coursera.org/learn/version-control-with-git)

## Практические задания

### Приветливый тест по питону: [classroom assignment](https://classroom.github.com/a/-qPj90qJ)

[Авторское решение](https://github.com/pyoadfe/seminars/blob/master/2_welcome_test_solution.ipynb) приветливого теста по питону в формате блокнота jupyter.

### ДЗ №1 «Озон»: [classroom assignment](https://classroom.github.com/a/v-sEvvWK)

### ДЗ №2 «Тьма имеет значение»: [classroom assignment](https://classroom.github.com/a/HtogelgG) (**дедлайн 21.10.2019 23:55**)

### ДЗ №3 «Двойное скопление»: [classroom assignment](https://classroom.github.com/a/iYDasG3A) (**дедлайн 7.11.2019 23:55**)

## Лекции

### 06.09
Введение: задача и структура курса.

Формула итоговой оценки: 0.3 экзамен + 0.6 практические задания + 0.1 самостоятельные работы. Для получения итоговой оценки выше 7 требуется выролнить онлайн-составялющую курса не менее чем на 80%.

Различные представления данных: табличные и структуированные, текстовые и бинарные. Примеры форматов данных: [HDF](https://support.hdfgroup.org/HDF5/doc/H5.intro.html), [FITS](https://fits.gsfc.nasa.gov/fits_documentation.html), [json](https://json.org), \*SV (CSV, TSV, и т.д.).

О- и Θ- нотация, её использование для оценки времени работы алгоритмов. Лучший алгоритм для решаемой задачи не всегда тот, у которого «лучшее» О.

Методы сортировки: пузырьком, слияниями. *Непрактичные методы сортировки (bogosort), специальные методы сортировки (поразрядная, параллельная).*

*P и NP сложные задачи*

### 13.09
Деревья как структура данных. Бинарные деревья, деревья поиска. Названия узлов, глубина дерева. Среднее время работы операций поиска, вставки и удаления в сбалансированном бинарном дереве поиска. K-мерное дерево. *Балансировка бинарного дерева поиска. B-дерево.*

Хэш-таблица и хэш-фукнция. Коллизии и парадокс дней рождения. Способы разрешения коллизий: цепочка, *открытая адресация*. Среднее время работы операций поиска, вставки и удаления.

## Семинары
### 06.09
[Приветливый тест по питону](https://github.com/pyoadfe/welcome_test)

### 13.09
 [Тетрадка Jupyter к задаче поиска самого частого элемента списка.](https://github.com/pyoadfe/seminars/blob/master/1_list_vs_dict.ipynb)
 [Тетрадка Jupyter про `numpy`.](https://github.com/pyoadfe/seminars/blob/master/1_tables.ipynb)

### 20.09
[Тетрадка Jupyter про `numpy`, чтение и запись файлов, `matplotlib`.](https://github.com/pyoadfe/seminars/blob/master/1_tables.ipynb)
[Домашнее задание №1 «Озон»](https://github.com/pyoadfe/hw1-o3)

### 27.09
NNLS: [Википедия](https://en.wikipedia.org/wiki/Non-negative_least_squares), [Тетрадка Jupyter](https://github.com/pyoadfe/seminars/blob/master/nnls.ipynb).

### 04.10 / 08.10
[Домашнее задание №2 «Тьма имеет значение»](https://github.com/pyoadfe/hw2-darkmatter), [консппект по оптимизации](https://github.com/pyoadfe/seminars/blob/master/3/nonlinear_ls.pdf).

### 11.10
Метод главных компонент (PCA). Наборы данных: [озон](https://github.com/pyoadfe/seminars/raw/master/ozon.npy), [эмодзи](https://github.com/pyoadfe/seminars/raw/master/emoji.zip). [Скрипт](https://github.com/pyoadfe/seminars/blob/master/pca.py), написанный на семинаре. См. Википедию про [PCA](https://ru.wikipedia.org/wiki/Метод_главных_компонент) и [собственное лицо](https://en.wikipedia.org/wiki/Eigenface).

### 18.10
[Домашнее задание №3 «Двойное скопление»](https://github.com/pyoadfe/hw3-double-cluster). [Тетрадка Jupyter](https://github.com/pyoadfe/seminars/blob/master/em-basics.ipynb). См. Википедию про [EM](https://en.wikipedia.org/wiki/Expectation–maximization_algorithm). [Лекция про EM на Курсере](https://www.coursera.org/lecture/unsupervised-learning/expectation-maximization-em-alghoritm-2jhbI)

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
