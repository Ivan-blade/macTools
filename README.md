# macTools
+ 远程连接
  ```shell
    ssh user@ip
  ```
+ 远程传输
  ```shell
    #将本地文件传入到远端，目录加-r，文件不加，下载顺序相反
    scp -r /local/directory remote@ip:/usr/local/storage
    scp /local/directory/ remote@ip:/usr/local/sin.sh
  ```
