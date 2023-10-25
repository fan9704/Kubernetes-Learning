# ETCD

---

## Introduction 

The most apparently difference with Docker-Compose and Kubernetes is Kubernetes use database to manage definition file(List file).

After Kubernetes read file will write its content to etcd.

Kubernetes will follow information to manage **Pod**

Docker Compose will use docker-compose.yml to modify content.

therefore after Kubernetes read definition file use command to modify content.It will happen definition file is differ then etcd information.We recommended you formulate rules to manage execution.