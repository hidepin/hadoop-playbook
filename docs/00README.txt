Hadoopサーバの構築手順

============================================================
(サーバ構成)
共通:
        root: root/hadoop123
        user: hadoop/hadoop123

hadoop-master01:
        CPU: 1
        Mem: 1024MB
        Disk: 50GB
        IP(ext): 192.168.0.15
        IP(int): 172.16.100.15

hadoop-slave01:
        CPU: 1
        Mem: 1024MB
        Disk: 50GB
        IP(ext): 192.168.0.16
        IP(int): 172.16.100.16

hadoop-slave02:
        CPU: 1
        Mem: 1024MB
        Disk: 50GB
        IP(ext): 192.168.0.17
        IP(int): 172.16.100.17

hadoop-slave03:
        CPU: 1
        Mem: 1024MB
        Disk: 50GB
        IP(ext): 192.168.0.18
        IP(int): 172.16.100.18

hadoop-slave04:
        CPU: 1
        Mem: 1024MB
        Disk: 50GB
        IP(ext): 192.168.0.19
        IP(int): 172.16.100.19

hadoop-slave05:
        CPU: 1
        Mem: 1024MB
        Disk: 50GB
        IP(ext): 192.168.0.20
        IP(int): 172.16.100.20
============================================================

1. hadoopのplaybookをclone
   $ git clone https://github.com/hidepin/hadoop-playbook.git

