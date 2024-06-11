FROM public.ecr.aws/amazoncorretto/amazoncorretto:17-al2-jdk

RUN mkdir /springCloud

COPY target/hello-app*.jar /springCloud/
COPY src/main/resources/env.sh /springCloud/

RUN chmod +x /springCloud/env.sh
