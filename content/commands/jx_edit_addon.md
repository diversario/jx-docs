---
date: 2019-06-12T12:51:02Z
title: "jx edit addon"
slug: jx_edit_addon
url: /commands/jx_edit_addon/
---
## jx edit addon

Edits the addon configuration

### Synopsis

Edits an addon

```
jx edit addon [flags]
```

### Examples

```
  # Enables or disables an addon
  jx edit addon
  
  # Enables or disables an addon
  jx edit addon -e true gitea
```

### Options

```
  -e, --enabled string   Enables or disables the addon
  -h, --help             help for addon
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

* [jx edit](/commands/jx_edit/)	 - Edit a resource

###### Auto generated by spf13/cobra on 12-Jun-2019
