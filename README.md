# Sobones_microservices
Sobones microservices repository

ДЗ 14 урока

В этом ДЗ мы установили Docker (пришлось добавить в группу докер пользователя , без этого работало только sudo Docker )
Запустили первый контейнер  hello-world
Работа с образами Docker
Выполнение команд в запущеном контейнере
Работа с разным функционалом Docker
Удалили все контейнеры и имиджи

ДЗ 15 урока

Был создан проект в GCP с именем docker , был запущен инстанс docker-host через docker-machine
--pid host позволяет запустить процесс используя PID пространства имен хостовой машины, что дает нам возможность не использовать изолированное дерево процессов, а работать в существующем и как следствие видеть все его процессы с реальными ID.
Был собран image reddit:latest
Был запущен container reddir в GCP 
Было создано правило firewall  открывающее порт tcp:9292 для инстансов с network тегом docker-machine
Был загружен образ на DockerHub

ДЗ 16 урока
Были описываны и собираны Docker-образы для сервисного приложения
Были оптимизированы некоторые Docker-образы
Был подключен Volume для контейнера
Разбили приложение на несколько компонентов
После запуска наше микросервисное приложение работает

ДЗ 17 урока

Была выпонена работа с сетями в Docker
контейнеры post и comment были помещены в обе сети

Установил docker-compose на локальную машину
собрал образы приложения reddit с помощью docker-compose
Запустил приложение reddit с помощью dockercompose
базовое имя проекта образуется при помощи container_name:


