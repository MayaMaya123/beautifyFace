# beautifyFace

# Создаем образ с Python3.7 и библиотекой openCV
docker build -t beauty_image .

# Создаем контейнер beauty_container
docker run --rm -dit --name beauty_container -v t /Users/mayafleyser/Desktop/new/images:/home/main/images beauty_image


# Запускаеbashм
docker exec -it beauty_container /bin/bash