FROM java:latest
VOLUME /tmp
COPY target/blog-admin-2.2.2.jar blog-admin.jar
RUN bash -c "touch /blog-admin.jar"
EXPOSE 8085
ENTRYPOINT ["java","-jar","blog-admin.jar"]