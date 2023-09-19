ARG BUILD_FROM
FROM $BUILD_FROM
LABEL maintainer="cryorig@gmx.at"

EXPOSE 19999

# Install openssl to claim node
RUN apk add --no-cache openssl

# Execute during the build of the image
RUN curl https://my-netdata.io/kickstart.sh > /tmp/netdata-kickstart.sh && \
    sh /tmp/netdata-kickstart.sh --no-updates --stable-channel \
    --disable-telemetry --dont-start-it --non-interactive --install-version 1.42.4

# Copy data for add-on
COPY rootfs /

CMD [ "/usr/bin/run.sh" ]