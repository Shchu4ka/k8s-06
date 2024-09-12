# Домашнее задание к занятию «Хранение в K8s. Часть 1»

## Задание 1

- Создаем Deployment приложения, делаем так, чтобы busybox писал каждые пять секунд в файл output.txt в директории /output, даем контейнеру multitool читать файл output.txt из директории /input

  ![image](https://github.com/user-attachments/assets/ac5592e2-9891-42fd-9e9a-96176f14ba48)

- Проверяем все это

  ![image](https://github.com/user-attachments/assets/0f530089-0dd1-478a-8f0a-0cb5584b40f7)

- Проверяем возможность чтения через multitool файла из volume

  ![image](https://github.com/user-attachments/assets/812a56e0-007b-416e-a70d-48f21b8f9968)

## Задание 2

- Создаем DaemonSet и применяем его

  ![image](https://github.com/user-attachments/assets/7fa35e24-775e-43e1-97bb-8b5697a66ef2)

- Проверяем чтение логов

  ![image](https://github.com/user-attachments/assets/8feb51ad-b2e1-45f5-8f4d-0fab066bbbdb)
