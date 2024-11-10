FROM openjdk:alpine

WORKDIR /testdir/java

COPY . /testdir/java/

RUN javac calc.java

CMD ["java", "calc"]