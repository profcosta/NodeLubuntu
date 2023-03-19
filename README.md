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
Esta versão é valida para um sistema 32 bits
```
nvm install 17.9.1
```
Última versão atualmente
```
nvm install 18.15.0
```

## Instalando o expo
Entre no terminal, digite o código abaixo:
```
npx expo -h
```

## Criando projeto expo
Entre no terminal, digite o código abaixo:
```
npx create-expo-app nomeProjeto
```
onde esta nomeProjeto substituir pelo nome do seu projeto

## rodando o projeto expo
Entre no terminal, digite o código abaixo:
```
cd nomeProjeto
npm run web
```
onde esta nomeProjeto substituir pelo nome do seu projeto

## Erro
Caso ocorra um erro no código acima.
Entre no terminal, digite o código abaixo:
```
npx expo install react-native-web@~0.18.10 react-dom@18.2.0 
npx expo install @expo/webpack-config@^18.0.1
```

## Entre no vsCode
Entre no terminal, digite o código abaixo:
```
code .
```

## Ajuste no package.json
No arquivo package.json será necessário realizar uma alteração de código na linha:
``` 
"web": "expo start --web"
```
Mude para a linha
```
"web": "NODE_OPTIONS=--openssl-legacy-provider expo start --web"
```

# Sites interessantes

[Expo](https://expo.dev/)

[Expo Docs](https://docs.expo.dev/)

[Tutorial de instalação do nvm no linux](https://www.freecodecamp.org/portuguese/news/como-instalar-o-nodejs-no-ubuntu-e-atualizar-o-npm-para-a-versao-mais-recente/)
