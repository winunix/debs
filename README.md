# Repositório Debian para sistemas baseados no Ubuntu 22.04 LTS

Apps para (X,L)Ubuntu Jammy Jellyfish.

## Como instalar via Terminal

Adicione a chave:
```bash
wget -qO - "https://winunix.github.io/debs/winunix.asc" | sudo tee /etc/apt/trusted.gpg.d/winunix.asc
```

Adicione o repositório:
```bash
echo "deb https://winunix.github.io/debs jammy main" | sudo tee /etc/apt/sources.list.d/winunix-jammy.list
```

Faça o update do catálogo:
```bash
sudo apt update
```

Dúvidas? [Veja esse tutorial no Youtube!](https://youtu.be/fXcuUzftY18)