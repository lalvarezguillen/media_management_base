FROM python:3.6-slim

RUN apt-get update \
    && apt-get install python3-dev python3-pip git openssh -y \
    && pip3 install --upgrade setuptools --no-cache-dir \
    && pip3 install pillow --no-cache-dir \

CMD ["python3"]
