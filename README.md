## CET HPC User Help
1.To run the Docker image in the background, so that the Docker container remains active even after disconnecting from the terminal \
```Instead of -it use -t -d  ``` \
1.Example
    ```docker run -t -d --gpus all -p 7013:8888 -v /home/Colleges/cet/EC/Faculty/f-15264/Mamba:/workspace nvcr.io/nvidia/pytorch:22.11-py3```
    
