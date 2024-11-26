## CET HPC User Help
1.To run the Docker image in the background, so that the Docker container remains active even after disconnecting from the terminal \
```Instead of -it use -t -d  ``` \
eg \
```docker run -t -d --gpus all -p xxxx:8888 -v /home/Colleges/cet/EC/Faculty/f-15264/Mamba:/workspace nvcr.io/nvidia/pytorch:22.11-py3```

2.To run a program in the background, prefix with `nohup` and terminate with &  \
eg \
```nohup python3 train.py &``` \
Program output will be stored in `nohup.txt` if not redirected.\


Use `kill` command to stop the program and `docker stop` to release the docker container

    
