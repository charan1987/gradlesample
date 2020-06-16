FROM java

VOLUME /tmp

ADD sample-0.0.1.jar sample-0.0.1sample.jar

RUN bash -c 'touch /sample-0.0.1.jar'

ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/sample.jar"]
