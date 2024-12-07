3 NODE Kafka Set-up using KRAFT

UI using kafka UI http://localhost:8080/

UI using kouncil http://localhost:8082/

How to run:

1. Build your Docker image file.
2. Update Docker Compose with image file name.
3. docker-compose up -d

N.B:

Before connecting to cluster from outside docker ( ex from your docker host - your PC ), config your host file.

Example for windows:

C:\Windows\System32\drivers\etc\hosts
127.0.0.1 kafka01
127.0.0.1 kafka02
127.0.0.1 kafka03
