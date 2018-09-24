# Helm Chart for etsy/hound
helm package for installing etsy/hound code searching onto k8s

Visit https://github.com/etsy/hound for product description, notes
on how hound works and how to configure it.

## Installation

0. Checkout this repo and go into it.

1. Edit values to add all necessary staff to hound config

2. install helm package

```
helm upgrade --install hound --namespace hound ./
```
