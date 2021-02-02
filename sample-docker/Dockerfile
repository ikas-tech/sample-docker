FROM openjdk
COPY src sample-docker
WORKDIR sample-docker
RUN mkdir -p bin
RUN javac -d bin ./com/sample/docker/SampleDocker.java
WORKDIR bin
CMD ["java", "com.sample.docker.SampleDocker"]