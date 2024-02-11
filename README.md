# Cara pakai

### install Nix
link download nixpkgs https://nixos.org/download (tdk perlu NixOS)

### masuk ke nix-shell
```bash
nix-shell
```
nanti dia akan download dependencies yg ada di shell.nix. saya cuma masukin git, python 3.11, pip dan pdm

### run python code
```bash
python3 src/hellopy/main.py
```

### additional, docker :
build docker image 
```bash
docker build -t hellopy .
```

run via docker image di container via desktop/terminal
