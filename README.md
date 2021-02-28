# hadoop-auto-install
Install and configure Hadoop 2.6 in a Hadoop Single Cluster Environment in Ubuntu 20 through this shell script in one go. 
## Running the script
For the first time, you need to format your namenode, use below command. 
```$hdfs namenode -format```  
Start hadoop using 
```start-all.sh``` 
start all file is in sbin of hadoop directory. 
```$cd hadoop/sbin```
```$./start-all.sh```
## Note
You can change the Hadoop version to download by specifying the version in the script.
Cheers!
