
```
Ref to Docker Images Developed for Kubernetes Security Assessments
```
_Attackk8s is a glibc compatible Alpine Linux based image designed for Kubernetes security assessments. It builds on top of madhuakula/hacker-container_ & _purple-kali is ~170 MB and was created with only the top common tools_


```
If using OCP - Login with oc login or OCP console

oc/ocp console - create pod

Image placement for the pods YAML

kind: Pod
spec: containers:
image: pjcampbe11/attackk8s

OR

kind: Pod
spec: containers:
image: pjcampbe11/purple-kali

Get a bash shell

oc exec -it attackk8s bash
oc exec -it purple-kali bash

```

_Use shortnames to bypass Regestry/Image Policies_ :moneybag: :moneybag: :moneybag:

- - - -
attackk8s --> https://hub.docker.com/repository/docker/pjcampbe11/attackk8s 

purple-kali --> https://hub.docker.com/repository/docker/pjcampbe11/purple-kali
- - - -
