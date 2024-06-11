# Spark_On_Docker

## Create a new cluster 
```bash
sh start-cluster.sh
 ```
## restart an existing Cluster 
 ```bash
sh restart-cluster.sh 
 ```
## Exec master for operating Spark cluster(attached to current terminal)
 ```bash
docker exec -it master bash 
```

## Load the data 

```bash
hdfs dfs -put /data/* /user/root/
 ``` 

## Run jupyter notebook
 ```bash
jupyter notebook --ip 0.0.0.0 --port 8888 --allow-root --no-browser --NotebookApp.token='spark'
```#   B I G - D A T A  
 