ARG version
FROM almalinux:${version}
RUN cat /etc/*release
ARG course
ARG trainer
RUN echo "Course is ${course}, Trainer is : ${trainer}"
CMD ["sleep","60"]
