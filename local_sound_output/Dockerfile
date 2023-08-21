ARG BUILD_FROM
FROM $BUILD_FROM

# install ffmpeg and other dependencies to have the ffplay command available

# Copy data for add-on
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]