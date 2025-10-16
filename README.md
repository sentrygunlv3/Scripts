~/.zshrc
```zsh
if [[ -e ~/Scripts && -e ~/Scripts/script && -e ~/Scripts/_setup ]]; then
  export PATH=$PATH:~/Scripts/script
  source ~/Scripts/_setup
fi
```
