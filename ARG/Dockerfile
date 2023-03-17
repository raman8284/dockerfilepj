# ARG VERSION
# FROM almalinux:${VERSION:-8}
# ARG GREETING="HAI RAM"
# RUN echo "$GREETING"
# RUN echo "$VERSION"

##using env&arg for best results ###

ARG VERSION
FROM almalinux:${VERSION:-8}
ARG GREETING="HAI RAMN"
ENV GREET=${GREETING}
RUN echo "$GREETING"
RUN echo "$VERSION"