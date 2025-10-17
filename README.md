~/.zshrc
```zsh
if [[ -d ~/Scripts/script && -e ~/Scripts/_setup ]]; then
  export PATH=$PATH:~/Scripts/script
  source ~/Scripts/_setup
fi
```
