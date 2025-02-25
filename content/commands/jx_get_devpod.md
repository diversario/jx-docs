---
date: 2019-06-12T12:51:02Z
title: "jx get devpod"
slug: jx_get_devpod
url: /commands/jx_get_devpod/
---
## jx get devpod

Lists the DevPods

### Synopsis

Display the available DevPods 

For more documentation see: https://jenkins-x.io/developing/devpods/

```
jx get devpod [flags]
```

### Examples

```
  # List all the possible DevPods
  jx get devPod
```

### Options

```
      --all-usernames     Gets devpods for all usernames
  -h, --help              help for devpod
      --username string   The username to create the DevPod. If not specified defaults to the current operating system user or $USER'
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
