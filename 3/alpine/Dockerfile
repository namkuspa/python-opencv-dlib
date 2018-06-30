FROM namkuspa/python-opencv:3.6.6-alpine

LABEL maintainer="Jose Truyol <jose@namku.cl>"

# Instalando DLIB en Alpine
RUN apk update \
    add -U \
       # --virtual .runtime-dependencies \
       openblas \
       jpeg \
       libpng \
       giflib \
    && apk add -U \
       --virtual .build-dependencies \
       git \
       cmake \
       g++ \
       make \
       jpeg-dev \
       libpng-dev \
        giflib-dev \
       openblas-dev \
       ca-certificates wget \
    && apk del .build-dependencies \
    && rm -rf /var/cache/apk/*
RUN pip install dlib numpy scipy

ENTRYPOINT ["python3"]
