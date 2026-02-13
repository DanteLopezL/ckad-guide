# CKAD

Guide for the CKAD linux foundation certificate exam

## Docker

- save image in tar file

```bash
docker save IMAGE > NAME.tar
```

- export image in tar file

```bash
docker export IMAGE > NAME.tar
```

- load image fron tar file

```bash
docker load -i FILE.tar
```

## Vim

- insert

```bash
i
```

- delete

```bash
dd
```

- copy

```bash
yy
```

- paste

```bash
ctrl + v
p
```

- cut

```bash
yy + dd + p
```

- search

```bash
esc + : + /
```

## k8s

- context
- pods
- cronjobs
- deployments
- configmaps
- secrets
- services
- ingress
- service account
- nodeport & cluster ip
- role & role binding
- persistent volume and claims

## tasks

- ping a pod from another one
- set context
- search for a resource in a namespace
- debug a resource
- pod logging and debugging
- pod labels
- liveness and readiness probes
- rolling updates
- canary deployments

