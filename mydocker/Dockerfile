FROM micalab/micapipe:v0.1.5

RUN apt-get update && \
    apt-get install -y git && \
    git clone -b zmaster https://gitee.com/gl_zhong/micapipe.git /tmp/micapipe && \
    rm -rf /opt/micapipe && \
    mv /tmp/micapipe /opt/micapipe
