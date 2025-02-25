---
date: 2019-06-12T12:51:02Z
title: "jx step next-buildnumber"
slug: jx_step_next-buildnumber
url: /commands/jx_step_next-buildnumber/
---
## jx step next-buildnumber

Generates the next build unique number for a pipeline.

### Synopsis

Generates the next build unique number for a pipeline

```
jx step next-buildnumber [flags]
```

### Examples

```
  jx step next-buildnumber
```

### Options

```
      --branch string   The Git branch (default "master")
  -h, --help            help for next-buildnumber
  -o, --owner string    The Git repository owner
  -r, --repo string     The Git repository name
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

* [jx step](/commands/jx_step/)	 - pipeline steps

###### Auto generated by spf13/cobra on 12-Jun-2019
