FROM openjdk:11-jre-slim
WORKDIR  usr/src
ENV MONGO_URI=mongodb://54.176.95.76:27017/bookings_db
ADD ./target/bookings-management-0.0.1-SNAPSHOT.jar /usr/src/bookings-management-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java","-jar","bookings-management-0.0.1-SNAPSHOT.jar"]