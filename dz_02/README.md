# Домашнее задание 2 

## Задание 1


Запустите контейнер из образа веб-сервера, например, nginx.

Запустите контейнер в режиме, чтобы он продолжал работать длительное время (не останавливался мгновенно).

Войдите в контейнер, используя команду exec, и проверьте наличие  конфигурационного файла веб-сервера (/usr/share/nginx/html/index.html).

В строке <title>Welcome to nginx!</title> конфигурационного файла (/usr/share/nginx/html/index.html) замените Welcome to nginx! на Welcome from dcbc5bbf0564 , где dcbc5bbf0564 - результат выполнения команды hostname.

Скопируйте из контейнера (docker cp) этот конфигурационный файл с исправленной строкой Welcome from dcbc5bbf0564 , где dcbc5bbf0564 - результат выполнения команды hostname и пришлите его.



## Задание 2


Тест на знание команд Docker

Укажите, какая команда используется для ….


1. создания и запуска нового контейнера из Docker образа:

docker create

docker run

docker start

2. запуска остановленного контейнера.

docker pause

docker run

docker start


3. принудительного удаления контейнера, даже если он запущен.

docker rm -f

docker kill

docker stop



4. отображения списка работающих контейнеров.

docker ps -a

docker ps

docker logs



5. просмотра вывода журналов контейнера.

docker ps -a

docker ps

docker logs



6. отображения списка процессов, работающих внутри контейнера.

docker top

docker logs

docker logs -f



7. предоставления подробной информации о контейнере в формате JSON.

docker top

docker diff

docker inspect


8. присоединения к работающему контейнеру и взаимодействия с ним через его стандартные ввод и вывод.

docker cp

docker attach

docker exec


9. создания нового Docker образа на основе изменений в контейнере.

docker commit

docker exec

docker export


10. удаления одного или нескольких образов Docker с хостовой системы.

docker inspect

docker tag

docker rmi
