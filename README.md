# tmuxp_recipe
sessions files by tmuxp.

## install tmuxp
```{r, engine='bash', count_lines}
$ sudo apt-get install -y python python-pip
$ cd ~
$ pip install --user tmuxp
```

## setup 
```{r, engine='bash', count_lines}
$ echo 'export PATH=$HOME/.local/bin:$PATH' >> .bashrc
$ source .bashrc
$ git clone https://github.com/cloudhc/tmuxp_recipe.git
```

## run
```{r, engine='bash', count_lines}
$ tmux load tmuxp_recipe/my-tmuxp-for-dev.yaml
```
