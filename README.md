# SonarQube
[![Kubescape Scan](https://github.com/almacareer/dex-sonarQube--k8s/actions/workflows/kubescape.yaml/badge.svg)](https://github.com/almacareer/dex-sonarQube--k8s/actions/workflows/kubescape.yaml)[![Release](https://github.com/almacareer/dex-sonarQube--k8s/actions/workflows/release.yaml/badge.svg?branch=master)](https://github.com/almacareer/dex-sonarQube--k8s/actions/workflows/release.yaml)[![Transfer DI from DockerHub to ECR](https://github.com/almacareer/dex-sonarQube--k8s/actions/workflows/di-dockerhub2ecr.yml/badge.svg)](https://github.com/almacareer/dex-sonarQube--k8s/actions/workflows/di-dockerhub2ecr.yml)



## Current Version

9.9.2 LTS

## Installing the chart

```bash
$ cd sonarqube
$ kubectl create namespace sonarqube
$ helm upgrade --install sonarqube -n sonarqube -f alma-values.yaml . 
```

## Prerequisites
Important to check new versions of [Community Branch Plugin](https://github.com/mc1arke/sonarqube-community-branch-plugin).
