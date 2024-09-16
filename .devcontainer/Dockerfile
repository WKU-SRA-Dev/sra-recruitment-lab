FROM mcr.microsoft.com/vscode/devcontainers/base:alpine

# 安装基础工具和 Java 运行环境
RUN apk update && \
    apk add --no-cache \
    bash \
    git \
    curl \
    build-base \
    openjdk11-jdk \
    maven

# 设置工作目录
WORKDIR /workspace