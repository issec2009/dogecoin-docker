# dogecoin-docker

docker run -d --restart unless-stopped --name dogecoin \
    -v /dogecoin:/opt/dogecoin \
    issec2009/dogecoind