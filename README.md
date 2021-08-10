# getns

This repo contains a kubectl plugin which is used to get the namespace of passed resource

**Installation**
```
curl https://raw.githubusercontent.com/rahulii/getns/main/kubectl-getns
chmod +x kubectl-getns
```
Then add this file to the PATH.

**Usage**
```kubectl getns resourcetype resourcename
eg:
kubectl getns serive kubernetes
```
Resources:
 - https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/
 - https://www.youtube.com/watch?v=fN8s52gkkTk&list=PLh4KH3LtJvRRcSwTZgmW60lkhVrzKU1jA&index=9
