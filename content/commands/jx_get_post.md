---
date: 2019-06-12T12:51:02Z
title: "jx get post"
slug: jx_get_post
url: /commands/jx_get_post/
---
## jx get post

Create a job which is triggered after a Preview is created

### Synopsis

Gets the jobs which are triggered after a Preview is created

```
jx get post preview job [flags]
```

### Examples

```
  # List the jobs triggered after a Preview is created
  jx get post preview job
```

### Options

```
  -h, --help   help for post
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
