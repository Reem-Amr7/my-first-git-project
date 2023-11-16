FROM openjdk

WORKDIR /application

COPY reem.java .

RUN javac reem.java

CMD [ "java", "reem.java" ]