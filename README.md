# v13
Colocar v13 na replit

Execute este script no shell para instalar o nó (você pode escolher a versão editando o número 16) e configurar npm.


``` npm init -y && npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd )/node_modules/nó/bin:$PATH ```

2. Crie o .replit para executar o nó da concha em vez do console.

```run = "npm start"```

3. Certifique-se de adicionar o script inicial no seu arquivo package.json
 ```"scripts": {
    "start": "node <main file>.js"
  }
