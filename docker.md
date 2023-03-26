docker exec -it eebf8ef9cbe4 bash

docker cp wine.data eebf8ef9cbe4:/home/jovyan/wine.data

docker run -v /home/sergio/Docker:/home/jovyan/ -p 10000:8888 jupyter/scipy-notebook:2023-02-28


docker build -t my_notebook .

docker run -v /home/sergio/Docker:/home/jovyan/ -p 10000:8888 my_notebook