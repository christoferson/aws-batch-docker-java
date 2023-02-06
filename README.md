# aws-batch-docker-java

## Aws Batch Docker Java

### Todo

- Update <docker-id>

### Build Application

mvn clean package

### Run Application Jar Locally

java -jar ./target/aws-batch-docker-java-1.0.0.jar

### Create Image

docker build -t <docker-id>/aws-batch-docker-java .

### Run Image

docker run <docker-id>/aws-batch-docker-java

### Login to Running Container

docker exec -ti loving_knuth /bin/sh

### Push Image

docker push <docker-id>/aws-batch-docker-java


