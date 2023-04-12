FROM ubuntu:22.04

RUN apt-get update && \
    apt-get install -y wget unzip && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

RUN useradd -u 7474 -m neo4j
WORKDIR /home/neo4j
USER neo4j