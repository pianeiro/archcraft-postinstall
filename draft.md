# Procedimentos para personalização do Archcraft

## 1) Criar swapfile

```sh
```
sudo fallocate -l 1G /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
sudo vim /etc/fstab # Acrescentar /swapfile swap swap 0 0
```

```

## 2) Instalar o Ungoogled Chromium
O Firefox será removido posteriormente

- Instalar YAY e suas dependências

```sh
sudo pacman -S base-devel yay
```

- Instalar ungoogled-chromium-bin do AUR

```sh
sudo yay ungoogled-chromium-bin
```

## 3) Instalar softwares não instalados por default

### IDE - Lazyvim
- Neovim: `sudo pacman -S neovim python-pynvim`

### Outros
- Tlp

## 4) Remover bloatwares
- Remoção de softwares: Estão em remove_bloatwares.sh
- Remoçã de temas não usados.

Outros pacotes
sudo rm top vi vim nano

## 5) Modificar o tema

Alterações na Polybar
- Alterar o ícone do navegador
- Colocar o Chromium para iniciar no workspace 2
- Remover workspaces desnecessários
- Remover monitores de RAM e CPU
- Remover gadget do mpd
- Tornar o bluetooth off na inicialização
- Remover o nome do Wi-Fi

Alterações no Picom
- Cantos arredondados
- Transparência

Alterar a imagem no wallpaper, no gestor de login e no lock screen

## 6) Consertar teclas de atalho do teclado
