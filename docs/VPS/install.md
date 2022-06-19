# [PT] Como instalo FiveM no meu VPS linux?

Porque instalar o FxServer (FiveM) num sistema Linux e não no Windows?

Recomendamos fortemente a utilização do Linux como sistema para o seu servidor porque o Linux utiliza significativamente menos recursos de CPU e memória.
Assim o recursos do seu servidor serão mais eficientes.

## Passo 1: Confirmar a versão do sistema

Por favor use o sistema operativo Ubuntu 20.04

![1](https://media.discordapp.net/attachments/943993455481339925/988144874824015892/unknown.png)

Se já tiver adquirido um servidor, pode ir ao painel de controlo e alterar o seu sistema operativo. Os passos são os seguintes:

1.1
![1](https://media.discordapp.net/attachments/943993455481339925/988146765989572619/unknown.png)
1.2
![1](https://media.discordapp.net/attachments/943993455481339925/988147074883256330/unknown.png)
1.3
![1](https://media.discordapp.net/attachments/943993455481339925/988147293905637386/unknown.png)
1.4
![1](https://media.discordapp.net/attachments/943993455481339925/988147607002021989/unknown.png)

## Passo 2: Ligue-se ao seu VPS por SSH

Nota: Se não sabe como usar o SSH, temos um <a href="/VPS/ssh/">tutorial</a> para si

## Passo 3: Instalar o FiveM

A instalação do FxServer é muito simples, consiste em apenas um simples comando.<br>
No terminal, digite o comando abaixo e aguarde até que a instalação termine.

```
bash <(curl -s https://raw.githubusercontent.com/wynn-dev/fxserver-install-linux/main/install.sh)
```

Após a instalação, pode aceder ao txAdmin com o link que irá aparecer no terminal.

![1](https://media.discordapp.net/attachments/943993455481339925/988187831975440444/unknown.png)

O PIN do txAdmin é o PIN que foi gerado no momento da instalação.

![1](https://media.discordapp.net/attachments/943993455481339925/988189345620037642/unknown.png)
![1](https://media.discordapp.net/attachments/943993455481339925/988188964999548998/unknown.png)

A instalação do FxServer está completa. Agora pode configurar o seu servidor normalmente seguindo o tutorial offical do FiveM. (Partir do passo 3)

<a href="https://docs.fivem.net/docs/server-manual/setting-up-a-server-txadmin/#start-the-server" target="_blank">https://docs.fivem.net/docs/server-manual/setting-up-a-server-txadmin/#start-the-server</a>

Se tiver alguma dúvida, contacte-nos no <a href="https://discord.gg/fmkgRD3vfh" target="_blank">Discord</a>.