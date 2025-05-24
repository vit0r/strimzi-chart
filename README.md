# install charts

## strimzi kafka

```console
helm upgrade -i  strimzi-kafka  . --create-namespace -n kafka
```

## uptime-kuma

```console
helm upgrade -i  uptime-kuma  . --create-namespace -n uptime-kuma --wait
```
