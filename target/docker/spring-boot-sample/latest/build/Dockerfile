FROM fabric8/s2i-java:2.3
ENV JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="" org.label-schema.version=0.0.1-SNAPSHOT org.label-schema.schema-version=1.0 org.label-schema.build-date=2019-12-02T13:28:27.709 org.label-schema.name="Spring Boot OCP Sample"
EXPOSE 8080 8778 9779
COPY maven /deployments/
