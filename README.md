⚠️ Archived for [damoun/fleet-infra](https://github.com/damoun/fleet-infra)
<h1 align="center">
  <br><img src="project-logo.svg" height="192px">
  <br>
  k8s-home
  <br>
</h1>

<h4 align="center">My Kubernetes home cluster using <a href="https://helmfile.readthedocs.io">helmfile</a>.</h4>

<p align="center">
  <a href="#getting-started">Getting Started</a>
</p>

# Getting Started

## Install CRDs

```
helmfile apply -l name=connect
helmfile apply -l name=prometheus-operator-crds
```

## Deploy all the applications

```
helmfile apply
```
