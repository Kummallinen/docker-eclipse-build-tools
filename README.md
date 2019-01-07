# Description

Docker image with all the commonly used tools to build Eclipse plugins & applications on Jenkins agents.

# How to use this Docker image

This Docker image is intended to be used with the [Jenkins Docker Pipeline Plugin](https://wiki.jenkins-ci.org/display/JENKINS/CloudBees+Docker+Pipeline+Plugin).

# Versions
-   OS: Ubuntu 18.04
-   Common tools: openssh-client, unzip, wget, curl, git, jq, rsync
-   Ant 1.10.5
-   gcc (latest): 7.3.0
-   Java: OpenJDK 8u191-b12
-   OpenJFX: 8u161-b12
-   Make (latest): 4.1
-   Maven located in `/usr/share/maven/`: 3.6.0
-   Python: 3.6.7-1
-   XVFB: 2:1.19.6

# License

The image is licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).

Based on/inspired by the [cloudbees/java-build-tools](https://github.com/cloudbees/java-build-tools-dockerfile) image:
```
Copyright 2015 CloudBees, Inc & Others


Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.