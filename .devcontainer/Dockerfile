FROM clojure:tools-deps

SHELL ["/bin/bash", "--login", "-c"]

RUN apt-get update -y && apt-get install -y curl python3.6 g++
RUN curl -sSL https://get.docker.com/ | sh
