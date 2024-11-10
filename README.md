# Домашнее задание к занятию "`Практическое применение Docker`" - `Бакулев Евгений`

### Задача 1

[Ccсылка на fork](https://github.com/garrkiss/shvirtd-example-python)

### Задача 3

![Скрин](https://github.com/garrkiss/docker/blob/main/img/task2.png)

### Задача 3

![Скрин](https://github.com/garrkiss/docker/blob/main/img/task3.png)

При нажатии комбинацию клавиш Ctrl-C. Это приведет к остановке контейнера, поскольку Ctrl-C посылает сигнал прерывания процессу в контейнере nginx, когда главный процесс завершает работу, контейнер автоматически останавливается.

Порт 8080 на хосте был связан с портом 80 в контейнере, и из-за изменения на порт 81 контейнер больше не доступен через 8080.

### Задача 4

![Скрин](https://github.com/garrkiss/docker/blob/main/img/task4.png)

### Задача 5

При выполнении команды docker compose up -d, Docker Compose по умолчанию ищет файл с именем docker-compose.yaml. Поскольку в вашей директории два файла с конфигурацией (один называется compose.yaml и другой docker-compose.yaml), будет запущен файл docker-compose.yaml. Причина в том, что именно этот файл является стандартным по умолчанию для Docker Compose. Чтобы использовать другой файл, нужно явно указать его с помощью флага -f.


![Скрин](https://github.com/garrkiss/docker/blob/main/img/task5-1.png)
![Скрин](https://github.com/garrkiss/docker/blob/main/img/task5-2.png)
![Скрин](https://github.com/garrkiss/docker/blob/main/img/task5-3.png)
![Скрин](https://github.com/garrkiss/docker/blob/main/img/task5-4.png)

[Cсылка на файл](https://github.com/garrkiss/docker/blob/main/files/compose.yml)
