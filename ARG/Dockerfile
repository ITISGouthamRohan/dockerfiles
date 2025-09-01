ARG version
FROM almalinux:${version}
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "Course name is ${COURSE},TRAINER: ${TRAINER}, Version: ${version}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
ENV VERSION=${version}
CMD ["sleep","100"]