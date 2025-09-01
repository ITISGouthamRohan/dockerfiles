ARG version
FROM almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
ARG version
RUN echo "Course name is ${COURSE},TRAINER: ${TRAINER}, Version: ${version}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep","100"]