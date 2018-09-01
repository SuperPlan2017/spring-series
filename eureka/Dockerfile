FROM java:8
ADD eureka-0.0.1-SNAPSHOT.jar  app.jar
VOLUME /data/result
RUN echo "Asia/shanghai" > /etc/timezone;
RUN bash -c 'touch /app.jar'
ENTRYPOINT ["java","-jar","/app.jar"]
