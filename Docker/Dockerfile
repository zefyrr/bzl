FROM ubuntu:wily

RUN apt-get update
RUN apt-get install -y --force-yes openjdk-8-jdk
RUN apt-get install -y --force-yes pkg-config zip g++ zlib1g-dev unzip
RUN cd \tmp && \
  wget https://github.com/bazelbuild/bazel/releases/download/0.1.4/bazel-0.1.4-installer-linux-x86_64.sh && \
  chmod +x bazel-0.1.4-installer-linux-x86_64.sh && \
  ./bazel-0.1.4-installer-linux-x86_64.sh


