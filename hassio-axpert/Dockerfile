ARG BUILD_FROM
FROM $BUILD_FROM

ENV LANG C.UTF-8

COPY requirements.txt /

COPY monitor.py /
COPY run.sh /
RUN chmod a+x /run.sh

CMD [ "/run.sh" ]
