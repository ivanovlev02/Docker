# Сборка контейнера
sudo docker build -t mynginx .

# Запуск контейнера
sudo docker run -p 8080:80 mynginx