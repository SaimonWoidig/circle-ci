FROM scratch as app
LABEL org.opencontainers.image.source "https://github.com/SaimonWoidig/circle-ci"
ENV PORT 8080
EXPOSE 8080
WORKDIR /
COPY dist/backend /backend
ENTRYPOINT [ "/backend" ]