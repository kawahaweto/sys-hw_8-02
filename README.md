# Домашнее задание к занятию «Что такое DevOps. СI/СD»

---

### Задание 1

**Что нужно сделать:**

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins [golang](https://golang.org/doc/install).
3. Используя свой аккаунт на GitHub, сделайте себе форк [репозитория](https://github.com/netology-code/sdvps-materials.git). В этом же репозитории находится [дополнительный материал для выполнения ДЗ](https://github.com/netology-code/sdvps-materials/blob/main/CICD/8.2-hw.md).
3. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта ```go test .``` и  ```docker build .```.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Ответ

<details>

<summary>Screenshots</summary>

![8-1](https://github.com/kawahaweto/sys-hw_8-02/assets/150899286/4ae5649a-9404-4916-ac75-10d653f5a785)



![8-2](https://github.com/kawahaweto/sys-hw_8-02/assets/150899286/0a31a450-c4c2-48e2-9f40-2f3fbeb6ad6b)



![8-3](https://github.com/kawahaweto/sys-hw_8-02/assets/150899286/6c0fa327-ed7c-4ff3-a325-9830d2af12c4)

</details>

  ---
### Задание 2

**Что нужно сделать:**

1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

### Ответ

<details>

<summary>Screenshots</summary>

![8-2-2](https://github.com/kawahaweto/sys-hw_8-02/assets/150899286/d209f752-bce6-4433-b631-8fb06ca9dc8d)

![Снимок экрана от 2023-11-25 15-22-57](https://github.com/kawahaweto/sys-hw_8-02/assets/150899286/01b02602-327a-4617-8e6e-9ad840a83ac1)

![8-2-1](https://github.com/kawahaweto/sys-hw_8-02/assets/150899286/4fe66ccc-1435-4b8b-8f51-7338dbb7be81)

</details>

---

### Задание 3

**Что нужно сделать:**

1. Установите на машину Nexus.
1. Создайте raw-hosted репозиторий.
1. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
1. Загрузите файл в репозиторий с помощью jenkins.

В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

---

### Ответ

<details>

<summary>Screenshots</summary>

![Снимок экрана от 2023-11-25 15-11-51](https://github.com/kawahaweto/sys-hw_8-02/assets/150899286/cd4e1fb7-a58c-46bf-bf7f-f9c95393110f)

![Снимок экрана от 2023-11-25 15-12-03](https://github.com/kawahaweto/sys-hw_8-02/assets/150899286/a911b248-70ca-417a-aca5-2ca155cdf882)

</details>



