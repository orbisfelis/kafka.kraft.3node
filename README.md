3 NODE Kafka Set-up usin KRAFT

UI using kafka UI http://localhost:8080/

UI using kouncil http://localhost:8082/

How to run

docker-compose up -d
Before connecting to cluster from outside docker ( ex from your docker host - your PC ), we also need to config host file:

Example for windows:

C:\Windows\System32\drivers\etc\hosts

127.0.0.1 kafka01
127.0.0.1 kafka02
127.0.0.1 kafka03

Done !
