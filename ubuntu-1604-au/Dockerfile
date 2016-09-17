# Ubuntu 16.04 pre-configured to use Australian mirrors

FROM ubuntu:16.04

MAINTAINER behrangsa@gmail.com

RUN sed 's@archive.ubuntu.com@au.archive.ubuntu.com@' -i /etc/apt/sources.list \
    && apt-get update \
    && apt-get upgrade -y

CMD ["/bin/bash"]
