# Домашнее задание к занятию «Что такое DevOps. СI/СD»

---

### Задание 1

**Что нужно сделать:**

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins [golang](https://golang.org/doc/install).
3. Используя свой аккаунт на GitHub, сделайте себе форк [репозитория](https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится [дополнительный материал для выполнения ДЗ](https://github.com/netology-code/sdvps-materials/blob/main/CICD/8.2-hw.md).
3. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта ```go test .``` и  ```docker build .```.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 1

![options for task 1 part 1](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t1opt1.png)
![options for task 1 part 2](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t1opt2.png)
![result of task 1](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t1fin.png)

---

### Задание 2

**Что нужно сделать:**

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 2

![options for task 2](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t2opt.png)
![result of task 2](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t2fin.png)

---

### Задание 3

**Что нужно сделать:**

1. Установите на машину Nexus.
1. Создайте raw-hosted репозиторий.
1. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
1. Загрузите файл в репозиторий с помощью jenkins.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 3

![options for task 3](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t3opt.png)
![result of task 3 part 1](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t3fin1.png)
![result of task 3 part 2](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t3fin2.png)

---

### Задание 4*

Придумайте способ версионировать приложение, чтобы каждый следующий запуск сборки присваивал имени файла новую версию. Таким образом, в репозитории Nexus будет храниться история релизов.

Подсказка: используйте переменную BUILD_NUMBER.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Решение 4

![options for task 4](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t4opt.png)
![result of task 4 part 1](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t4fin1.png)
![result of task 4 part 2](https://github.com/murtazinilyas/8.2_CI-CD_mia/blob/main/screenshots/t4fin1.png)

