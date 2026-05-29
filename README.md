## como rodar o projeto baixado 
instalar todas as dependencias indicadas no package.json
```
npm install
```
## sequencia para criar o projeto

criar o projeto com tailwind 
```
npm install tailwindcss @tailwindcss/cli
```
executar o projeto, gerar a biuld do css
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
instalar a intenção live server no vs code <br>
clicar sobre o arquivo "index.html" que deve ser aberto "open with live server" ou abrir o arquivo no editor e cliacar em ALT + O ou ALT + L <br>
sera aberto o endereço: http://127.0.0.1:5500/src/index.html

## como enviar e baixar os arquivos do github

criar o repositorio "layout -adm-tailwind" no github
criar o branch "develop" no repositorio

baixar os arquivos do git
```
git clone -b <branch_name> <repository_url> .
```

verificar em qual branch está
```
git branch
``` 
baixar as atualizações do gitHub
```
git pull
```
adicionar todos os arquivos modificados no staging area - area de preparação
```
git add .
```
