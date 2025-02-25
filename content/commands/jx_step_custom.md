---
date: 2019-06-12T12:51:02Z
title: "jx step custom"
slug: jx_step_custom
url: /commands/jx_step_custom/
---
## jx step custom

Triggers a pipeline in a custom Jenkins server using the local Jenkinsfile

### Synopsis

This pipeline step lazily creates a Pipeline job inside a custom Jenkins App and then triggers it

```
jx step custom pipeline [flags]
```

### Examples

```
  # triggers the Jenkinsfile in the current directory in the custom Jenkins App
  jx step custom pipeline
```

### Options

```
  -d, --dir string             the directory to look for the Jenkisnfile inside (default ".")
  -h, --help                   help for custom
  -j, --jenkins-name string    The name of the custom Jenkins App if you don't wish to use the default execution engine in Jenkins X
  -p, --jenkins-path string    The Jenkins folder path to create the pipeline inside. If not specified it defaults to the git 'owner/repoName/branch'
  -f, --jenkinsfile string     The name of the Jenkinsfile to use (default "Jenkinsfile")
      --multi-branch-project   Use a Multi Branch Project in Jenkins
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
