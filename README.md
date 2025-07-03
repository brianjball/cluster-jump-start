# Quckstart for RHOAI

This is an example of how to setup OpenShift AI

## Quickstart

Run default demo

```sh
until oc apply -k demo/default; do : ; done
```

## Development

Cherry pick from catalog with `rsync`

```sh
rsync -av ../demo-ai-gitops-catalog/components/operators/rhods-operator modules/operators/
```
