FROM    openjdk
WORKDIR usr/lib

ENV MONGO_DATABASE="userTrack_db"
ENV MONGO_URL="mongodb://localhost:27017/userTrack_db"

ADD ./target/UserTrackService-0.0.1-SNAPSHOT.jar /usr/lib/UserTrackService-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","UserTrackService-0.0.1-SNAPSHOT.jar"]