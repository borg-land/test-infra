# Mahamed's Prow Instance

prow.m.rack.gold

Commands to run first.

```
k create cm -n prow config --from-file=prow/config.yaml
k create cm -n prow plugins --from-file=prow/plugins.yaml
```
