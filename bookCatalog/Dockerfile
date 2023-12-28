FROM adoptopenjdk/openjdk11:jdk-11.0.21_9-ubuntu-slim

RUN apt-get update -y && apt-get install -y curl \
  && curl -sL https://deb.nodesource.com/setup_12.x | bash - \
  && apt-get install -y nodejs 

WORKDIR /app

COPY . /app

RUN chmod +x ./mvnw

EXPOSE 8082

CMD ["./mvnw"]