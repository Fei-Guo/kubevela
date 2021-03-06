# KubeVela CLI

Learn about general configurations for `vela` command line tool. For the usage of the CLI, please check the KubeVela's [user documentation](../../README.md) instead.

### Auto-completion

#### bash

```bash
To load completions in your current shell session:
$ source <(vela completion bash)

To load completions for every new session, execute once:
Linux:
  $ vela completion bash > /etc/bash_completion.d/vela
MacOS:
  $ vela completion bash > /usr/local/etc/bash_completion.d/vela
```

#### zsh

```bash
To load completions in your current shell session:
$ source <(vela completion zsh)

To load completions for every new session, execute once:
$ vela completion zsh > "${fpath[1]}/_vela"
```
