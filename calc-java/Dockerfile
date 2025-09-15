FROM openjdk:alpine

WORKDIR /files/calc-java

COPY . /files/calc-java

RUN javac calc.java

CMD ["java", "calc"]