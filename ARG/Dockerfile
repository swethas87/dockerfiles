ARG version
FROM almalinux:${version:-8}
RUN cat /etc/*release
ARG course
ARG trainer
RUN echo "Course is ${course}, Trainer is : ${trainer}"
CMD ["sleep","60"]
