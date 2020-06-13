# manjaroI3

Como instalar o Manjaro com o tiling window manager i3wm.

## Criando o pendrive com o Manjaro

1. Ir no site do [Manjaro](http://manjaro.org)

- clicar em try manjaro
- no menu superior clicar em editions > community > i3
- clicar no botão de "get i3 20.0.3"
- clicar no botão de download

2. Criar o pendrive bootável a partir do Linux

- navegar até a pasta de Downloads
> $ cd ~/Downloads
- criar o disco de boot com o dd
> $ sudo dd if=manjaro-i3-20.0.3-200606-linux56.iso of=/dev/sdb bs=4MB status=progress
- dar boot na máquina e alterar a sequência de boot
> sudo reboot
- apertar F2 para entrar no setup(pode variar para delete ou outra, dependendo do fabricante)
- alterar o boot para iniciar pelo pendrive

3. Continuar
