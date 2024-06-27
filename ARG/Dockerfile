ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG course=docker
ARG trainer=siva
RUN echo "Course is ${course}, Trainer is : ${trainer}"
CMD ["sleep","60"]
