# Обработка и анализ данных физического эксперимента 2020/2021

## [Текущая успеваемость](https://docs.google.com/spreadsheets/d/1lRdvAbSuWK2wrL-w-jgJe3SrstLy-w7MEAeW7-BXRak/edit?usp=sharing)

## Онлайн-составляющая: [Version Control with Git](https://www.coursera.org/learn/version-control-with-git)

## На время дистанционных занятий мы занимаемся в Teams:

- [Лекции](https://teams.microsoft.com/l/channel/19%3a2ea58a1ff9c64f0b906ec028b6286e93%40thread.tacv2/%25D0%259B%25D0%25B5%25D0%25BA%25D1%2586%25D0%25B8%25D0%25B8?groupId=0ee2471c-9602-441d-aead-187ce02a6d97&tenantId=21f26c24-0793-4b07-a73d-563cd2ec235f)
- [Семинары БФ3191](https://teams.microsoft.com/l/channel/19%3a210d2afdd81044a5ac677a271f4c6618%40thread.tacv2/%25D0%25A1%25D0%25B5%25D0%25BC%25D0%25B8%25D0%25BD%25D0%25B0%25D1%2580%25D1%258B%2520%25D0%2591%25D0%25A43191%2520%28%25D1%2584%25D0%25B8%25D0%25B7_%25D0%25BF%25D0%25B31%29?groupId=0ee2471c-9602-441d-aead-187ce02a6d97&tenantId=21f26c24-0793-4b07-a73d-563cd2ec235f)
- [Семинары БФ3192](https://teams.microsoft.com/l/channel/19%3a6a7ed19435c14464960e7fc3b6b71517%40thread.tacv2/%25D0%25A1%25D0%25B5%25D0%25BC%25D0%25B8%25D0%25BD%25D0%25B0%25D1%2580%25D1%258B%2520%25D0%2591%25D0%25A43192%2520%28%25D1%2584%25D0%25B8%25D0%25B7_%25D0%25BF%25D0%25B32%29?groupId=0ee2471c-9602-441d-aead-187ce02a6d97&tenantId=21f26c24-0793-4b07-a73d-563cd2ec235f)
- [Семинары БФ3193](https://teams.microsoft.com/l/channel/19%3a3713b4a9938e418a970a617208cf6968%40thread.tacv2/%25D0%25A1%25D0%25B5%25D0%25BC%25D0%25B8%25D0%25BD%25D0%25B0%25D1%2580%25D1%258B%2520%25D0%2591%25D0%25A43193%2520%28%25D1%2584%25D0%25B8%25D0%25B7_%25D0%25BF%25D0%25B33%29?groupId=0ee2471c-9602-441d-aead-187ce02a6d97&tenantId=21f26c24-0793-4b07-a73d-563cd2ec235f)
- [Семинары БФ3194](https://teams.microsoft.com/l/channel/19%3a52ba928565ab44d28f64c38614be3ee8%40thread.tacv2/%25D0%25A1%25D0%25B5%25D0%25BC%25D0%25B8%25D0%25BD%25D0%25B0%25D1%2580%25D1%258B%2520%25D0%2591%25D0%25A43194%2520%28%25D1%2584%25D0%25B8%25D0%25B7_%25D0%25BF%25D0%25B34%29?groupId=0ee2471c-9602-441d-aead-187ce02a6d97&tenantId=21f26c24-0793-4b07-a73d-563cd2ec235f)

## Практические задания

- [Тест по питону](https://classroom.github.com/a/PkM1Xa1a)
- [Домашнее задание 1](https://classroom.github.com/a/MwpFi6NW)
- [Домашнее задание 2](https://classroom.github.com/a/vW9SxmhR)
- [Самостоятельная работа 1](https://classroom.github.com/a/dLJ2NrTX)

## Лекции

### 15.01 "Анализ алгоритмов"

Выяснили, что алгоритм - это математический объект, который подвержен формальному анализу. Среди всего остального нас интересует алгоритмическая сложность: зависимость времени исполнения (количества шагов, количества операций) от характерного размера входных данных. Обнаружилось, что разные алгоритмы могут решать одну и ту же задачу, но при этом иметь разную сложность. Обнаружилось, что иногда можно даже доказать теорему о существовании/несуществовании алгоритмов для той или иной задачи. Например, все (существующие и еще не придуманные) алгоритмы сортировки использующие сравнения обладают асимптотиками O(N logN) или хуже; или NP-полные задачи не разрешимы за O(N^p) (если P!=NP).
Узнали, что лучшая асимптотика не всегда значит быстрее на практике, например алгоритм умножения матриц Коперсмита-Винограда).

### 22.01 "Структуры данных"

Обнаружили, что наивный алгоритм кросс-идентификации двух астрономических каталогов по координатам работает порядка сотен лет для каталогов из миллиарда записей.
Опечалившись, мы решили изучить структуры данных (вектора, списки, деревья, хеш-таблицы) и алгоритмическую сложность типовых операций с ними (поиск, вставка, удаление, ...). Познакомились с АВЛ деревьями: сбалансированными бинарными деревьями поиска.

### 29.01 "Структуры данных - II"

Разобрались с АВЛ деревьями. Посмотрели как можно обобщить бинарное дерево поиска для индексации многомерного пространства на примере Kd-деревьев. 
Узнали, что если для какого-то типа данных можно предложить хеш-функцию, то эти данные можно сложить в хеш-таблицу и искать из в среднем за константное время.

Немного поговорили про разные форматы данных, про устройство хранения данных в СУБД. Познакомились с понятием о реляционной алгебре.

### 5.02 "Анализ главных компонент"

Разобрались с анализом главных компонент. Выяснилось, что анализ главных компонент позволяет уменьшить размерность данных с помощью линейного преобразования,
потеряв наименьшее количество информации.

Немного поговорили про статетстические свойста линейной оценки наименьших квадратов.

### 12.02 "Методы оптимизации - I"

Вспомнили определения глобального и локального минимумов функции, определение выпуклой функции.
Сформулировали разные варианты задачи оптимизации: безусловной, условной, выпуклой, и т.п.
Сформулировали разные варианты классификации алгоритмов оптимизации: по количеству требуемых данных (без производной, с производной, со второй производной),
по сходимости (к стационарной точке 1 порядка, или 2 порядка), по скорости работы (линейная сходимость, квадратичная).
Разобрали два простейших алгоритма: градиентный спуск и метод Ньютона.

### 19.02 "Методы оптимизации - II"
Познакомились с задачей оптимизации с ограничениями (задача математического программирования). Сформулировали критерии и признаки её решения.
Изучили методы построения алгоритмов решения таких задач: штрафных (барьерных) функций и проекции градиента (на примере алгоритма поиска неотрицательного решения линейной задачи наименьших квадратов (NNLS)).

### 26.02 "Методы оптимизации - III"
Познакомились с методом Метрополиса, который позволяет генерировать выборку случайных векторов с известным распределением.
Познакомились с методом имитации отжига, который получается если в методе Метрополиса постепенно снижать параметр "температура".

Упомянули некорректные задачи, плохо обусловленные задачи, регуляризацию.

### 05.03 "Методы оптимизации - IV"
Познакомились с методом сопряженных градиентов, методами доверительных областей (trust region method), методом стохастического градиентого спуска.

## Семинары

### 15.01

Приветливый тест.

### 22.01

Разбирали приветливый тест и вспоминали `numpy`.

### 29.01

Считали число различных слов в текстовом файле. Читали и писали CSV и netCDF файлики.

- [Конспект двух семинаров](https://github.com/pyoadfe/seminars/blob/master/1_tables.ipynb)
- [Конспект задачки про число слов](https://github.com/pyoadfe/seminars/blob/master/1_list_vs_dict.ipynb)

### 5.02

Применяли анализ главных компонент к различным наборам данных. Синтетическим, табличке про стекло и к набору смайликов.

### 12.02

Разбирали метод градиентного спуска и метод Гаусса-Ньютона.

- [Конспект по методам оптимизации к домашнему заданию](https://raw.githubusercontent.com/pyoadfe/seminars/master/3/nonlinear_ls.pdf)

### 19.02

Разбирали алгоритм NNLS.
Коррелировали содержание озона в атмосфере с активностью Солнца.

- [Конспект по алгоритму NNLS](https://github.com/pyoadfe/seminars/blob/master/nnls.ipynb)

### 26.02
Попробовали метод "Truncated SVD" для взаимодействия с плохо обусловленными задачами линейных наименьших квадратов.

Писали самостоятельную по методу имитации отжига.

### 05.03

Разбирали домашнее задание с использованием готовых функций оптимизации из пакета scipy.




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
