## 1- Conceitos Gerais

**Desenvolvimento Front-end Moderno:** Em aplicações mais simples o desenvolvimento
front-end consisite em `HTML, CSS e JavaScript`. Dependendo da finalidade da aplicação
o desenvolvimento pode se tornar complexo e possuir múltiplas partes, tornando
difícil a manunteção do código.<br>
Em aplicações modernas são utilizadas bibliotecas como o `React.js`, estas bibliotecas
gerenciam o código e auxiliam no desenvolvimento.<br>

**React.js:** É uma biblioteca front-end criada pelo Facebook que permite o gerenciamento
de aplicações através de `componentes, propriedades e estados`.<br>

**Componentes:** Se refere aos diferentes elementos que formam a aplicação, estes
elementos podem ser divididos para se tornarem reutilizáveis.<br>

**Propriedades:** São utilizadas para passar informação para o componente. As propriedades
são `imutáveis`.<br>

**Estados:** São utilizados para gerenciar as informações do componente.

## 2- Por que React.js ?

**Velocidade:** É utilizado o `Virtual DOM`, que permite a atualização de somente
partes da aplicação.<br>

**Fácil de Usar:** Permite o agrupamento de códigos semelhantes para uma melhor
manutenção da aplicação.<br>

**Comunidade:** React.js é uma das mais populares bibliotecas JavaScript de código aberto,
é mantido pela comunidade e pelo Facebook.

## 3- Programas Necessários

`Node.js` é um interpretador JavaScript.

> node -v

`NPM` é um gerenciador de pacotes JavaScript, a instalação é realizada em
conjunto com o Node.js.

> npm -v

No lugar do NPM pode ser utilizado o `YARN` que também é um gerenciador de
pacotes JavaScript mas é mantido pelo Facebook.

> yarn -v

Existem algumas `extensões para o Visual Studio Code` que auxiliam em tempo de
desenvolvimento e formatação do código.<br>

- ES7 React/Redux/React-Native/JS snippets<br>
- Prettier - Code formatter

## 4- Criando um Novo Projeto

Comando mantido pelo Facebook para criar uma aplicação com configurações e dependências
pré-configuradas.

`Criar uma nova pasta para o projeto (nome do projeto)`

> npx create-react-app nome_do_pojeto

`Criar o projeto na pasta atual`

> npx create-react-app .
