# cheatsheet

## Config

Change default namespace

```bash
kubectl config set-context $(kubectl config current-context) --namespace=app
```

## debug

```bash
kubectl run -it --rm --restart=Never busybox --image=busybox /bin/sh
```

