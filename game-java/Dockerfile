FROM openjdk:alpine

WORKDIR /testdir/java

COPY . /testdir/java/

RUN javac game.java

CMD ["java", "game"]