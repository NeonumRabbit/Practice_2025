<img width="793" height="812" alt="image" src="https://github.com/user-attachments/assets/fc35f726-2978-4e75-9dc5-ed45e1625dad" /># Practice_2025
This repository making for college
$ cd ~/
$ mkdir Practice_2025 && cd Practice_2025
$ touch README.md
$ git init # инициализация локального репозитория
$ echo "# Практика 2025" > README.md
$ git add README.md # добавить файл в индекс
$ git commit -m "First commit" # зафиксировать изменения
$ git remote add origin https://github.com/<username>/Practice_2025.git
$ git push -u origin main # отправляем первую версию
$ git checkout -b feature/new_functionality # создаём новую ветку
$ vim new_file.py # вносим изменения
$ git add .
$ git commit -m "Add new functionality"
$ git push origin feature/new_functionality # отправляем ветку на сервер
