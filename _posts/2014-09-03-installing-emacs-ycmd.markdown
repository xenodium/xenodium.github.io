Installing [emacs-ymcd](https://github.com/abingham/emacs-ycmd) (work in progress):

  git clone https://github.com/Valloric/YouCompleteMe.git
  cd YouCompleteMe
  git submodule update --init --recursive
  ./install.sh --clang-completer --omnisharp-completer
  cd third_party/ycmd/examples
  sudo pip install requests
  brew install httpie
  pip install enum34

Reference:

https://github.com/Valloric/YouCompleteMe/blob/master/README.md#mac-os-x-super-quick-installation
