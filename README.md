## Запуск контейнера
1) Скопируйте файлы репозитория 
2) Открыть консоль со скопированными файлами
3) Введите команду 

        docker-compose up -d

4) На вашей машине отредактируйте файл hosts добавив в него следующие записи

        127.0.0.1 dev.{domain name}
        127.0.0.1 base.{domain name}

5) Скопируйте код вашего проекта или начните создавать проект в папке /html 
6) Развертка окончена