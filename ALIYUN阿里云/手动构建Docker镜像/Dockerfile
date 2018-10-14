FROM java:8u111-jre
RUN mkdir /app
COPY app/. /app
WORKDIR /app
CMD ["java","-jar","application-web.jar"]