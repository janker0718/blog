FROM java:latest
VOLUME /tmp
COPY target/blog-web-2.2.2.jar blog-web.jar
RUN bash -c "touch /blog-web.jar"
EXPOSE 80
ENTRYPOINT ["java","-jar","blog-web.jar"]