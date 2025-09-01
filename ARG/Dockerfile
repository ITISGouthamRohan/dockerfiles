FROM almalinux:9
ARG username
RUN adduser $username
USER $username
ARG COURSE
ARG TRAINER
RUN echo "Course name is ${COURSE},TRAINER: ${TRAINER}"
ENV COURSE=${COURSE}
ENV TRAINER=${TRAINER}
CMD ["sleep","100"]