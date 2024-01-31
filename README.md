# Install instructions (mostly for me)
## Linux Fish Instructions
Create local bin directory (if it doesn't already exist)
```fish
mkdir ~/.local/bin
```
Add to path in Fish
```fish
fish_add_path ~/.local/bin
```
Install Oh My Posh to ~/.local/bin
```fish
curl -s https://ohmyposh.dev/install.sh | bash -s -- -d ~/.local/bin
```
Initialize Oh My Posh with theme in ~/.config/fish/config.fish:
```
oh-my-posh init fish --config ~/theme.omp.json | source
```
