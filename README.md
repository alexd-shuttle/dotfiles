How to use dotfiles
===================
See https://coder.com/docs/user-guides/workspace-dotfiles

- Add all the setup scripts to the repository (e.g. in install.sh)
- In the devcontainer, to install the dotfile, run:
  coder dotfiles https://github.com/user/repo/

The setup scripts will run on every container restart.
