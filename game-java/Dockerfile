FROM openjdk:17-alpine

WORKDIR /files/game-java

COPY . .

RUN javac game.java

CMD ["java", "game"]