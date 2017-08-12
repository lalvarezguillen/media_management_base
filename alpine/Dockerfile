FROM python:alpine3.6

ENV LIBRARY_PATH=/lib:/usr/lib

RUN apk --update add git openssh build-base \
    && python3-dev jpeg-dev zlib-dev \
    && pip3 install --upgrade setuptools --no-cache-dir \
    && pip3 install pillow --no-cache-dir

CMD ["python3"]
