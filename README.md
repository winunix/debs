# Repositório Debian para sistemas baseados no Ubuntu 22.04 LTS

Apps para (X|L)Ubuntu Jammy Jellyfish.

## Como instalar via Terminal

Adicione a chave:
```bash
wget -qO - "https://winunix.github.io/debs/winunix.asc" | sudo tee /etc/apt/trusted.gpg.d/
```

Adicione o repositório:
```bash
echo "deb https://winunix.github.io/debs jammy main" | sudo tee /etc/apt/sources.list.d/winunix-jammy.list
sudo apt update
```
