docker build -t fastbook . && docker run --net=host --gpus all --memory 60g --memory-swap 60g --shm-size 8G --rm -it --name f1 fastbook
