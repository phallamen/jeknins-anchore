FROM jenkins/jenkins

USER root

RUN \
    apt-get update && \
    DEBIAN_FRONTEND=noninteractive \
    apt-get install --quiet --yes --fix-missing \
    python3-pip \
    ruby-full \
    jq

