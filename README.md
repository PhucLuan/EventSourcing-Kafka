# EventSourcing-Kafka
Learn DDD-EventSourcing-Kafka

Run mongodb: 
docker pull mongo
docker run -d -p 27017:27017 --name mongo-container mongo

Run kafka:
curl --silent --output docker-compose.yml \
  https://raw.githubusercontent.com/confluentinc/cp-all-in-one/7.2.1-post/cp-all-in-one/docker-compose.yml
 
docker-compose up -d

![image](https://user-images.githubusercontent.com/54372656/201966555-f86170b8-eb2b-4ff4-b821-0761cadceb68.png)
