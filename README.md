# Deploying Ghost to DigitalOcean Kubernetes

## Prerequsities

- Create kubernetes cluster
- [Install doctl](https://github.com/digitalocean/doctl#installing-doctl)

## Install

```
kubectl create -f volume.yaml
kubectl create -f deployment.yaml
kubectl create -f service.yaml
```

## SSL Certificate
[The domain must be on digitalocean](https://www.digitalocean.com/community/tutorials/how-to-point-to-digitalocean-nameservers-from-common-domain-registrars)

[Documentation here](https://www.digitalocean.com/docs/networking/load-balancers/how-to/ssl-termination/)
