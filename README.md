# Jenkins Test Pipeline

simple pipe with 3 stages:

1. clone
2. build
3. test

run docker 

```sh
$ docker run --name jenkinsci -p 8080:8080 -p 50000:50000 -d -v jenkins_home:/var/jenkins_home jenkins/jenkins:lts
```