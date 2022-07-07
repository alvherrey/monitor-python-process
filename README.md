# monitor-python-process
tutorial: 
https://lhchen74.github.io/2021/07/27/python-process-monitor/


ejecucion:
```
sudo su -
/home/ahernandez/miniconda3/envs/dob-docreader/bin/python /home/ahernandez/monitor-python-process/main.py
/home/ahernandez/miniconda3/envs/dob-docreader/bin/python /home/ahernandez/monitor-python-process/main.py --columns name,cpu_usage,memory_usage,status -n 20 --sort-by memory_usage --descending
```
