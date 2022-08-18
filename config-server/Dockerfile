FROM openjdk
WORKDIR usr/lib

ADD ./target/config-server-0.0.1-SNAPSHOT.jar /usr/lib/config-server-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","config-server-0.0.1-SNAPSHOT.jar"]