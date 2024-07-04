# use Ubuntu 24.04 LTS
FROM mcr.microsoft.com/devcontainers/base:noble

RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends \
    g++-riscv64-linux-gnu \
    gcc-riscv64-linux-gnu \
    gdb-multiarch \
    qemu-system-misc
