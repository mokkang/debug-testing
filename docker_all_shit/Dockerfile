FROM adoptopenjdk:11-jre-openj9
RUN mkdir /opt/app
COPY ./out_jar/verademo.jar /opt/app
CMD ["java", "-jar", "/opt/app/verademo.jar"]

