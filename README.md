# hadoop-auto-install
Install hadoop 2.6 in ubuntu 20 using shell script in one go  Using this script you can install and configure hadoop single node cluster only. once your script is finished.
## Running the script
For the first time, you need to format your namenode, use below command. 
```$hdfs namenode -format```  
Start hadoop using 
```start-all.sh``` 
start all file is in sbin of hadoop directory. 
```$cd hadoop/sbin```
```$./start-all.sh```
