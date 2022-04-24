## Projeto To-Do List em Typescript

Projeto criado para reforçar conceitos em TypeScript

Etapas do Projeto:

- Setup do Typescript
- Bundle Typescript
- Criando o Projeto

### Introdução

**tsconfig.json**

*Algumas configurações iniciais do TypeScript que foram apresentadas*

- outDir : Serve para compilar o seu arquivos TypeScript e escolher uma pasta de destino aonde vai estar o arquivo .js compilado

- module : Serve para informar qual modulo de código ira ser compilado
    Nesse caso alteramos de "commonjs" para "es6" afim de ele conseguir usar as funções de export, caso eu esteja utilizando alguma lib de node_modules

**MAS** temos um grande porém, pois o navegador não sabe utilizar a pasta de node_modules, então para resolver esse problema, iremos utilizar o conceito de Bundle, temos varios Bundle para ser utilizado com o TypeScript

Então nesse mini-projeto iremos utilizar o **Bundle Snowpack**

No terminal:
```
npx create-snowpack-app . --template @snowpack/app-template-blank-typescript
``` 
Explicando o código:
"npx create-snowpack-app" : Estamos criado o nosso projeto com o bundle do snowpack;

"." : Vai ser criado no diretório atual;

"--template": Utilizando a flag para especificar um modelo e após isso declaramos que utilizamos o modelo em branco do typescript;

Verificamos que após a instalação do bundle, ao inspecionar elemento no navegador não ocorre mais erro sobre export e conseguimos utilizar o typescript e todo seu poder






[Projeto do Canal do Youtube - Web Dev Simplified](https://www.youtube.com/watch?v=jBmrduvKl5w)

