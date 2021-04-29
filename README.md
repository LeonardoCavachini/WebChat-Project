# WebChat Project

## Tabela de conteúdos

- [Sobre](https://github.com/LeonardoCavachini/TryBeer.git#Sobre)
- [Instalação](https://github.com/LeonardoCavachini/TryBeer.git#Instalação)
- [Como-usar](https://github.com/LeonardoCavachini/TryBeer.git#Como-usar)
- [Tecnologias](https://github.com/LeonardoCavachini/TryBeer.git#Tecnologias)

## Sobre

Aplicação de Chat desenvolivda durante curso de formação backend pela Trybe, onde foi construido uma aplicação de chat simples.

## Instalação

#### Pré-requisitos

Certifique-se de ter instalado em sua maquina estas ferramentas: Git, Node.js, MongoDB e um editor de textos como o VSCode.

#### Rodando a aplicação localmente

1. Clone o repositório

- `git clone https://github.com/LeonardoCavachini/WebChat-Project.git`

2. Instale as dependências:

- `npm install`

3. adicione um arquivo `.env` com as seguintes vaiaveis de ambiente.

DB_URL=mongodb://localhost:27017

DB_NAME=Trybeer

- Inicie o projeto com `npm start`  
  Por padrão o React procura rodar as aplicações na porta 3000.
  Uma página no browser será aberta com a aplicação.  
  Divirta-se!!

## Como Usar

Ao iniciar a aplicação o usuario receberar uma identificação aleatória, haver um campo usuário onde o mesmo poderá inserir um nickName de sua preferência, quando a aplicação for aberta em outra janela haverá uma conxeção entre os dois usuários, sendo possivel realizar troca de mesnsagens entre si em tempo real, todas as mensagens são armazenadas no banco, sendo que, sempre que inicia a aplicação um historico de mensagens é mostrado.

## Tecnologias

Tecnologias utilizadas para construção da aplicação:

- Node
- Socket.io
- banco de dados: mongodDB

Ferramentas para controle e organização de código:

- ESLint
- Git
