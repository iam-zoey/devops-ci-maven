# syntax=docker/dockerfile:1

ARG BASE_IMAGE=maven:latest

FROM ${BASE_IMAGE}
ARG APP_NAME="my-sample-app"
WORKDIR /app
COPY ./target/${APP_NAME}.jar .
CMD ["java", "-jar", "${APP_NAME}"]