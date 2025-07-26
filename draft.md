# Procedimentos para personalização do Archcraft

## 1) Criar swapfile
```sh
sudo fallocate -l 1G /swapfile
sudo chmod 600 /swapfile
sudo mkswap /swapfile
sudo swapon /swapfile
sudo vim /etc/fstab # Acrescentar /swapfile swap swap 0 0
```

## 2) Instalar o Ungoogled Chromium
O Firefox será removido posteriormente

- Instalar YAY e suas dependências
`sudo pacman -S base-devel yay`

- Instalar ungoogled-chromium-bin do AUR
`sudo yay ungoogled-chromium-bin`

## 3) Remover bloatwares
- Remoção de softwares: Estão em remove_bloatwares.sh
- Remoçã de temas não usados.

`sudo rm top vi vim nano`


## 4) Instalar softwares

- IDE
- Tlp

## 5) Modificar o tema
