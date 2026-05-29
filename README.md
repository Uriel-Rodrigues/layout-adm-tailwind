## Requisitos

* conferir a versão do node.js 22 ou superior: node -v
* conferir se está instalado o GIT: git -v

## como rodar o projeto baixado 
instalar todas as dependencias indicadas no package.json
```
npm install
```

executar o projeto baixado e gerar a build do css
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
- instale a extenção **live server** no vs code <br>
- abrir o arquivo **"index.html"** com live server   <br>

### metodos para abrir live server
1. **opção 1:** abrir o arquivo no editor e cliacar em ALT + O ou ALT + L  
2. **opção 2:** botão direito sobre o arquivo **"index.html"** -> "open with live server" 
sera aberto o endereço: http://127.0.0.1:5500/src/index.html

## sequencia para criar o projeto

criar o projeto com tailwind 
```
npm install tailwindcss @tailwindcss/cli
```
executar o projeto, gerar a biuld do css
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```
instale a extenção **live server** no vs code <br>
abrir o arquivo **"index.html"** com live server   <br>

### metodos para abrir live server
1. **opção 1:** abrir o arquivo no editor e cliacar em ALT + O ou ALT + L  
2. **opção 2:** botão direito sobre o arquivo **"index.html"** -> "open with live server" 
sera aberto o endereço: http://127.0.0.1:5500/src/index.html


## como enviar e baixar os arquivos do github

criar o repositorio **"layout -adm-tailwind"** no github. <br>
criar o branch **"develop"** no repositorio

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
commit representa um conjunto de alterações e um ponto especifico da historia do seu projeto, registra apenas as alterações adicionadas ao indice de preparação. o comando -m permite que insira a mensagem de commit diretamente na linha de comando
```
git commit -m "base projeto"
```
enviar os commit locais, para um repositorio remoto
```
git push <remote> <branch>
git push origin develop
```
