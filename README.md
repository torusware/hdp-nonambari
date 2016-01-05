# Hortonworks Data Platform

* Launch the container 
docker run  -p 8080:8080 --rm -ti --privileged --name hdp -h hdp torusware/hdp-nonambari

* Access a running container
```
$ sshpass -p 'torus' ssh root@<container IP>
```

* This image contains the following packages pre-installed (but not configured):
    - Hadoop
    - Hive
    - Spark
    - HBase
