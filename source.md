# Installation from source

1. Clone cli into `~/.githubcli`
```
$ git clone https://github.com/cli/cli.git ~/.githubcli
```

2. Compile
```
$ cd ~/.githubcli && make
```

3. Add `~/.githubcli/bin` to your $PATH for access to the gh command-line utility.

  * For **bash**:
  ~~~ bash
  $ echo 'export PATH="$HOME/.githubcli/bin:$PATH"' >> ~/.bash_profile
  ~~~
  
  * For **Zsh**:
  ~~~ zsh
  $ echo 'export PATH="$HOME/.githubcli/bin:$PATH"' >> ~/.zshrc
  ~~~
  
  * For **Fish shell**:
  ~~~ fish
  $ set -Ux fish_user_paths $HOME/.githubcli/bin $fish_user_paths
  ~~~

4. Restart your shell so that PATH changes take effect.

