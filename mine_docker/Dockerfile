FROM openjdk:17

ARG RAM_AMOUNT 

ENV ram={RAM_AMOUNT}

WORKDIR /server

CMD echo "Docker minecraft server is starting\n" && java -Xmx4G -jar server.jar
