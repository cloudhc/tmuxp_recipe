# tmuxp_recipe
sessions files by tmuxp.

## install tmuxp
$ sudo apt-get install -y python python-pip
$ cd ~
$ pip install --user tmuxp

## setup 
$ echo 'export PATH=$HOME/.local/bin:$PATH' >> .bashrc
$ source .bashrc
$ git clone git clone https://github.com/cloudhc/tmuxp_recipe.git

## run
$ tmux load tmuxp_recipe/my-tmuxp-for-dev.yaml
