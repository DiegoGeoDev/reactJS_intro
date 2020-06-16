# Optimus Talks - Introdução ao React JS

## 1- Conceitos Gerais

**Desenvolvimento Front-end Moderno:** Em aplicações mais simples o desenvolvimento
front-end consisite em `HTML, CSS e JavaScript`. Dependendo da finalidade da aplicação
o desenvolvimento pode se tornar complexo e possuir múltiplas partes, tornando
difícil a manunteção do código.

Em aplicações modernas são utilizadas bibliotecas como o `React.js`, estas bibliotecas
gerenciam o código e auxiliam no desenvolvimento.

**React.js:** É uma biblioteca front-end criada pelo Facebook que permite o gerenciamento
de aplicações através de `componentes, propriedades e estados`.

**Componentes:** Se refere aos diferentes elementos que formam a aplicação, estes
elementos podem ser divididos para se tornarem reutilizáveis.

**Propriedades:** São utilizadas para passar informação para o componente. As propriedades
são `imutáveis`.

**Estados:** São utilizados para gerenciar as informações do componente.

## 2- Por que React.js ?

**Velocidade:** É utilizado o `Virtual DOM`, que permite a atualização de somente
partes da aplicação.

**Fácil de Usar:** Permite o agrupamento de códigos semelhantes para uma melhor
manutenção da aplicação.

**Comunidade:** React.js é uma das mais populares bibliotecas JavaScript de código aberto,
é mantido pela comunidade e pelo Facebook.

## 3- Programas Necessários

`Node.js` é um interpretador JavaScript.

```bash
node -v
```

`NPM` é um gerenciador de pacotes JavaScript, a instalação é realizada em
conjunto com o Node.js.

```bash
npm -v
```

No lugar do NPM pode ser utilizado o `YARN` que também é um gerenciador de
pacotes JavaScript mas é mantido pelo Facebook.

```bash
yarn -v
```

Existem algumas `extensões para o Visual Studio Code` que auxiliam em tempo de
desenvolvimento e formatação do código (Opcional).

- ES7 React/Redux/React-Native/JS snippets
- Prettier - Code formatter
- ESLint
- Auto Rename Tag
- Bracket Pair Colorizer
- Color Highlight

## 4- Criando um Novo Projeto

Comando mantido pelo Facebook para criar uma aplicação com configurações e dependências
pré-configuradas.

`Criar uma nova pasta para o projeto com o nome do projeto`

```bash
npx create-react-app nome_do_pojeto
```

`Criar o projeto na pasta atual`

```bash
npx create-react-app .
```

## 5- Scripts - package.json

No arquivo pacakge.json existem alguns scripts entre eles:

`Criar um ambiente de desenvolvimento`

```bash
npm start
```

`Transpila e cria os arquivos para disponibilizar a aplicação`

```bash
npm run build
```

## 6- Arquivos Principais

**./public/index.html**<br>
A aplicação é de página única, dentro do arquivo HTML existe uma div (root) onde é renderizado todo o conteúdo.

**./src/index.js**<br>
Onde a aplicação é inicializada e informado a div (root) para o componente principal.

**./src/App.js**<br>
Componente principal da aplicação.

## 7- Regras

**Nome dos componentes:** Pascal Case

## 8- Estrutura de Pastas e Arquivos (Exemplo)

- ./src/index.js
  - Inicializar a aplicação / Renderizar App.js na div (root).
- ./src/App.js
  - Componente principal / Receber as rotas da aplicação.
- .src/App.css
  - CSS principal / Estilos que são compartilhados por toda a aplicação.
- ./src/routes.js
  - Rotas da aplicação / Rotas e componentes.
- ./src/assets
  - Arquivos anexos a aplicação.
- ./src/services
  - Configuração de serviços que a aplicação consome.
- .src/pages
  - Páginas da aplicação.
- ./src/pages/components
  - Componentes reutilizáveis.

## 9- Pacotes Complementares que Auxiliam no Desenvolvimento

Requisições e Respostas de Serviços

```bash
npm i axios
```

Criação de Rotas

```bash
npm i react-router-dom
```

## 10- Outros

Nenhum conteúdo até o momento.

## 11- Exemplos
