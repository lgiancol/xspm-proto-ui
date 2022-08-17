FROM clojure:tools-deps

SHELL ["/bin/bash", "--login", "-c"]

RUN apt-get update -y && apt-get install -y curl python3.6 g++
RUN curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
RUN nvm install 12.16.3
RUN curl -sSL https://get.docker.com/ | sh
