FROM google/shaka-packager:latest as packager
FROM jrottenberg/ffmpeg:5.0-alpine
COPY --from=packager /usr/bin /usr/bin
ENTRYPOINT ["sh"]

