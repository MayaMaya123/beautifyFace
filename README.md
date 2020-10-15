# beautifyFace

docker build -t beauty_image .

docker run --rm -dit --name beauty_container -v
images:/home/main/images beauty_image


docker exec -it beauty_container /bin/bash