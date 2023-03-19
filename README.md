# NodeLubuntu
Instação do nodo no Lubuntu


## Atualizando o sistema
Entre no terminal, digite o código abaixo:
```
sudo apt-get update
sudo apt-get upgrade
```

## Instalar o Curl
Entre no terminal, digite o código abaixo:
```
sudo apt install curl
```

## instalando o nvm via curl
Entre no terminal, digite ou cole o código abaixo:
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash

```
Para colar no terminal, utilize ctrl+shift+v


## Configurando as variaveis de ambiente
Entre no terminal, digite ou cole o código abaixo:
```
export NVM_DIR="$HOME/.nvm" 

[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm 

[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"

```
Para colar no terminal, utilize ctrl+shift+v



## instalando o node
Entre no terminal, digite o código abaixo:
```
nvm install 18.15.0

```
Para colar no terminal, utilize ctrl+shift+v



## Sites interessantes

[Expo](https://expo.dev/)

[Expo Docs](https://docs.expo.dev/)

[Tutorial de instalação do nvm no linux](https://www.freecodecamp.org/portuguese/news/como-instalar-o-nodejs-no-ubuntu-e-atualizar-o-npm-para-a-versao-mais-recente/)
