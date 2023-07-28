# hash:sha256:ea6e44a0fae715e32c6abc88607b4d484e080f0d5360efbac3f6b02619b7484d
FROM registry.codeocean.allenneuraldynamics.org/codeocean/jupyterlab:3.0.9-miniconda4.9.2-python3.8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip3 install -U --no-cache-dir \
    allensdk --ignore-installed ruamel.yaml
