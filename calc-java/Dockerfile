FROM openjdk:17-alpine

WORKDIR /files/calc-java

COPY . .

RUN javac calc.java

CMD ["java", "calc"]