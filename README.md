# Домашнее задание к занятию "`Практическое применение Docker`" - `Бакулев Евгений`

### Задача 1

[Cсылка на fork](https://github.com/garrkiss/shvirtd-example-python)

### Задача 3

![Скрин](https://github.com/garrkiss/shvirtd2/blob/main/img/task3.png)

### Задача 4

![Скрин](https://github.com/garrkiss/shvirtd2/blob/main/img/task4.png)

```
#!/bin/bash

# Установить рабочий каталог
TARGET_DIR="/opt/shvirtd-example-python"

# Клонирование репозитория в /opt
echo "Клонируем репозиторий в $TARGET_DIR..."
sudo git clone https://github.com/garrkiss/shvirtd-example-python.git "$TARGET_DIR"

# Переход в каталог проекта
cd "$TARGET_DIR" || exit 1

# Запуск проекта
echo "Запускаем проект с помощью Docker Compose..."
sudo docker compose -f compose.yaml up -d

echo "Проект успешно запущен."
```

[Cсылка на fork](https://github.com/garrkiss/shvirtd-example-python)

### Задача 6

![Скрин](https://github.com/garrkiss/shvirtd2/blob/main/img/task6_1.png)
![Скрин](https://github.com/garrkiss/shvirtd2/blob/main/img/task6_2.png)

### Задача 6.1

![Скрин](https://github.com/garrkiss/shvirtd2/blob/main/img/task6.1.png)