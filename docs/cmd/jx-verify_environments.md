## jx-verify environments

Verifies that the Environments have valid git repositories setup - lazily creating them if needed

***Aliases**: environment,env*

### Usage

```
jx-verify environments
```

### Synopsis

Verifies that the Environments have valid git repositories setup - lazily creating them if needed

### Options

```
  -d, --dir string   The directory to look for the jx-requirements.yml file, by default the current working directory
  -h, --help         help for environments
```

### Options inherited from parent commands

```
  -b, --batch-mode   Runs in batch mode without prompting for user input
      --verbose      Enables verbose output. The environment variable JX_LOG_LEVEL has precedence over this flag and allows setting the logging level to any value of: panic, fatal, error, warn, info, debug, trace
```

### SEE ALSO

* [jx-verify](jx-verify.md)	 - boots up Jenkins and/or Jenkins X in a Kubernetes cluster using GitOps

###### Auto generated by spf13/cobra on 3-Jul-2020