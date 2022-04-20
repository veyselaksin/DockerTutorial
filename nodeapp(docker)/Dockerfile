FROM debian:latest
RUN apt update
RUN apt install curl -y
RUN curl -fsSL https://deb.nodesource.com/setup_lts.x | bash -
RUN apt install nodejs -y
COPY . /opt/node-app
WORKDIR /opt/node-app
ENV channel=veyselaksin
CMD ["node", "index.js"];
