FROM micalab/micapipe:v0.1.5

RUN apt-get update && \
    apt-get install -y git && \
    git clone https://github.com/ZhongGangliang/micapipe.git /tmp/micapipe && \
    rm -rf /opt/micapipe && \
    mv /tmp/micapipe /opt/micapipe
