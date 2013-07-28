dotfiles.git
============
This are the configuration files used for my EC2 Instance running Ubuntu 12.04.2 LTS to
configure my `bash` and `emacs` development environment as follows:

```sh
cd $HOME
git clone https://github.com/berlanga87/dotfiles.git
ln -sb dotfiles/.screenrc .
ln -sb dotfiles/.bash_profile .
ln -sb dotfiles/.bashrc .
ln -sb dotfiles/.bashrc_custom .
mv .emacs.d .emacs.d~
ln -s dotfiles/.emacs.d .
```