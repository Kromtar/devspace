---
title: "devspace use namespace --help"
sidebar_label: devspace use namespace
---


Tells DevSpace which namespace to use

## Synopsis


```
devspace use namespace [flags]
```

```
#######################################################
############## devspace use namespace #################
#######################################################
Sets the default namespace to deploy to

Example:
devspace use namespace my-namespace
#######################################################
```


## Flags

```
      --create   Create the namespace if it doesn't exist
  -h, --help     help for namespace
      --reset    Resets the default namespace of the current kube-context
```


## Global & Inherited Flags

```
      --debug                        Prints the stack trace if an error occurs
      --disable-profile-activation   If true will ignore all profile activations
      --inactivity-timeout int       Minutes the current user is inactive (no mouse or keyboard interaction) until DevSpace will exit automatically. 0 to disable. Only supported on windows and mac operating systems
      --kube-context string          The kubernetes context to use
      --kubeconfig string            The kubeconfig path to use
  -n, --namespace string             The kubernetes namespace to use
      --no-warn                      If true does not show any warning when deploying into a different namespace or kube-context than before
      --override-name string         If specified will override the devspace.yaml name
  -p, --profile strings              The DevSpace profiles to apply. Multiple profiles are applied in the order they are specified
      --silent                       Run in silent mode and prevents any devspace log output except panics & fatals
  -s, --switch-context               Switches and uses the last kube context and namespace that was used to deploy the DevSpace project
      --var strings                  Variables to override during execution (e.g. --var=MYVAR=MYVALUE)
```

