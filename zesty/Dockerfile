FROM ubuntu:zesty
MAINTAINER Youngbin Han <sukso96100@gmail.com>

COPY sources.list /etc/apt/sources.list
RUN apt update && apt dist-upgrade -y && apt install -y snapcraft build-essential nano vim git && apt clean

CMD ["/bin/bash"]
