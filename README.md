# kustomize-examples
this repos is created with purpose to illustrate how to use kustomize and its use cases.

## Override the namespace and count of replicas:

To override the namespace and count of replica's using patch, please take a look on files present in `overlay` folder  and then run below for test:

 ```
kustomize build overlay > staging.yaml
```
