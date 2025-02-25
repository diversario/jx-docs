---
date: 2019-06-12T12:51:02Z
title: "jx get eks"
slug: jx_get_eks
url: /commands/jx_get_eks/
---
## jx get eks

List EKS clusters.

### Synopsis

Display one or many EKS cluster resources

```
jx get eks [flags]
```

### Examples

```
  # List EKS clusters available in AWS
  jx get eks
  
  # Displays someCluster EKS resource
  jx get eks someCluster
  
  # Displays someCluster resource in YAML format
  jx get eks someCluster -oyaml
```

### Options

```
  -h, --help             help for eks
  -o, --output string    The output format such as 'yaml'
      --profile string   AWS profile to use.
      --region string    AWS region to use. Default: us-west-2
```

### Options inherited from parent commands

```
      --advanced-mode             Advanced install options. This will prompt for advanced install options
  -b, --batch-mode                Runs in batch mode without prompting for user input (default true)
      --install-dependencies      Enables automatic dependencies installation when required
      --no-brew                   Disables brew package manager on MacOS when installing binary dependencies
      --skip-auth-secrets-merge   Skips merging the secrets from local files with the secrets from Kubernetes cluster
      --verbose                   Enables verbose output
```

### SEE ALSO

* [jx get](/commands/jx_get/)	 - Display one or more resources

###### Auto generated by spf13/cobra on 12-Jun-2019
