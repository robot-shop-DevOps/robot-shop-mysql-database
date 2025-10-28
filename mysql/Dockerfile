FROM robotshopdevacr.azurecr.io/baseimages/mysql:9.5.0-internal

RUN mkdir -p /docker-scripts && chmod -R 755 /docker-scripts

COPY ./mysql/scripts/ /docker-scripts/