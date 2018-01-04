FROM java:8-jre
MAINTAINER saurabh seth <sss@sss.com>

ADD ./target/hello-service.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/hello-service.jar"]

EXPOSE 6000