FROM openjdk:8-jdk
MAINTAINER khiempm1 (khiem.pm170084@sis.hust.edu.vn)
COPY target/TwitterStreamKafka-1.0-SNAPSHOT.jar /usr/local/service/
COPY conf /usr/local/service/
COPY target/classes/lib/* /usr/local/service/
WORKDIR /usr/local/service/
CMD ["java", "-cp", "TwitterStreamKafka-1.0-SNAPSHOT.jar", "vn.hust.kstn.bigdata.StreamTweetProcessor"]