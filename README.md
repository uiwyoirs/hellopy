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
python3 src/hello_world/main.py
```

### additional, docker :
build docker image 
```bash
docker build -t hello-world .
```

run via docker image di container via desktop/terminal