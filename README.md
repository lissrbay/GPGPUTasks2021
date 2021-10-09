В этом репозитории предложены задания для [курса по вычислениям на видеокартах в CSC](https://compscicenter.ru/courses/video_cards_computation/2021-autumn/).

[Остальные задания](https://github.com/GPGPUCourse/GPGPUTasks2021/).

# Задание 4. Транспонирование матрицы, умножение матриц.

[![Build Status](https://github.com/GPGPUCourse/GPGPUTasks2021/actions/workflows/cmake.yml/badge.svg?branch=task04&event=push)](https://github.com/GPGPUCourse/GPGPUTasks2021/actions/workflows/cmake.yml)

0. Сделать fork проекта
1. Выполнить задания 4.1 и 4.2 ниже
2. Отправить **Pull-request** с названием```Task04 <Имя> <Фамилия> <Аффиляция>``` (добавив в описании вывод работы программы в **pre**-тэгах - см. [пример](https://raw.githubusercontent.com/GPGPUCourse/GPGPUTasks2021/task03/.github/pull_request_example.md))

**Дедлайн**: начало лекции 11 октября.

Если времени не хватит - отправьте то что вы успели сделать с комментарием что вы хотите дополнительную неделю на это задание
(и мне очень поможет если вы сможете детализировать на что у вас ушло слишком много времени, сколько в целом вы времени потратили и т.п.).

Задание 4.1. Транспонирование матрицы
=========

Реализуйте транспонирование матрицы таким образом, чтобы доступ и на чтение и на запись к глобальной видеопамяти был coalesced. (т.е. через локальную память)

Файлы: ```src/main_matrix_transpose.cpp``` и ```src/cl/matrix_transpose.cl```

Задание 4.2. Умножение матриц
=========

Реализуйте умножение матриц через локальную память. (на лекции это вплоть до "Умножение матриц 2: локальная память")

Файлы: ```src/main_matrix_multiplication.cpp``` и ```src/cl/matrix_multiplication.cl```
