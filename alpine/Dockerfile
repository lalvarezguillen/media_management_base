FROM python:alpine3.6

RUN apk --update add git openssh \
    && pip3 install --upgrade setuptools --no-cache-dir \
    && pip3 install pillow --no-cache-dir \

CMD ["python3"]
