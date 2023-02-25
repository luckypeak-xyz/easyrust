FROM mcr.microsoft.com/devcontainers/base:jammy
RUN apt-get update && apt-get install -y build-essential curl && curl https://sh.rustup.rs -sSf | bash -s -- -y
ENV PATH="/root/.cargo/bin:${PATH}"