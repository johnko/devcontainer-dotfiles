FROM --platform=linux/amd64 mcr.microsoft.com/devcontainers/universal:5-noble

RUN sudo apt update ; \
  sudo apt install --yes shellcheck

RUN go install github.com/mikefarah/yq/v4@v4.50.1

RUN go install mvdan.cc/sh/v3/cmd/shfmt@v3.12.0
