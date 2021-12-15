# v13
//1. Cole este código no Shell da Replit e aguarde terminar:

npm i --save-dev node@16 && npm config set prefix=$(pwd)/node_modules/node && export PATH=$(pwd)/node_modules/node/bin:$PATH

//Execute isto para limpar a npm e reinstalar o pacote:

rm -rf node_modules && rm package-lock.json && npm cache clear --force && npm cache clean --force && npm i

//2. Crie um arquivo chamado .replit para que ele execute pelo Shell ao invés do console:


run= "npm start"

//3. Vá no package.json e SUBSTITUA o scripts atual por esse:

"scripts": {
    "start": "node index.js",
    "test": "echo \"Error: no test specified\" && exit 1"
},

//OBS: Caso tenha pacotes como canvas, ou qualquer outro que cause problema, reinstale ele:

npm uninstall canvas && npm i canvaso
