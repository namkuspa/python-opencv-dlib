FROM namkuspa/python-opencv:3.6.6-alpine

LABEL maintainer="Jose Truyol <jose@namku.cl>"

# Instalando DLIB en Alpine
RUN apk update \
    && apk add --no-cache git \
       cmake \
       g++ \
       make \
       jpeg jpeg-dev \
       libpng libpng-dev \
       giflib giflib-dev \
       openblas \
       openblas-dev \
       ca-certificates wget \
    && rm -rf /var/cache/apk/*
RUN pip install dlib numpy scipy

ENTRYPOINT ["python3"]
