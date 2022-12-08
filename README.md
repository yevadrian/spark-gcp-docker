### Apache Spark deployment using Docker

Apache Spark deployment using custom images and Docker Compose. Example of usage will be added soon.

##### Clone this repository and enter the directory
> git clone https://github.com/yevadrian/spark-docker && cd spark-docker

##### Create Spark container with Docker Compose
> sudo docker compose up -d

##### Run Apache Spark master
> sudo docker exec -it spark bash -c "spark/sbin/start-master.sh"

##### Open Apache Spark via your web browser
> localhost:8080

##### Apache Spark running
![spark](https://user-images.githubusercontent.com/110159876/206534439-825f57e6-9a6a-4448-868d-392e15db7c3f.jpg)
