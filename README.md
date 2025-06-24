How to use dotfiles
===================
See https://coder.com/docs/user-guides/workspace-dotfiles

- Set up your own dotfile repository
- Add all the scripts you want to run on workspace restart to install.sh or setup.sh (or one of the [other files](https://coder.com/docs/user-guides/workspace-dotfiles))
- In the devcontainer, to install the dotfile, run:
  coder dotfiles https://github.com/user/repo/

The setup scripts will run on every container restart.
