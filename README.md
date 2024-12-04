Site UNIESP 2024:

Projeto REACT JS criado através da IDE VsCode, com objetivo de modelar um site para instituição UNIESP
com páginal inicial, dando informações sobre o que é a instituição de modo geral e exibindo as parcerias,
página "a faculdade", onde apresenta somente informações sobre a faculdade, página "DPO LGPD", que basicamente
apresenta os conceitos de proteção de dados da instituição, página "notícias", onde exibe algumas noticias globais
e pra finalizar, página "admin" onde um usuário com permissão pode gerenciar notícias, as editando ou removendo.

O código é composto por várias etapas e pastas, começando pela criação, onde usamos o comando npm create vite@latest
dentro da pasta do projeto e definimos todas as dependências iniciais para criação, como nome do projeto, a biblioteca
escolhida, etc, no caso do site UNIESP foi usado React Javascript.

As principais pastas desse projeto são:

data: pasta onde criamos o arquivo db.json, arquivo onde está o banco de dados fake com todas as notícias.

node modules: pasta onde estarão todos os arquivos criados pelo npm install.

public: pasta onde armazenamos as imagens estáticas do site.

src: uma das pastas mais importantes onde damos origem a outras pastas, arquivos e ao componente pai, que receberá
import de outros componentes filhos.

assets: pasta criada dentro de "src" para armazenar todos os assets privados do site.

components: pasta onde criamos os componentes filhos do site, que serão importados dentro do componente pai.

pages: pasta criada para armazenar todas as páginas do site, todas estarão linkadas na barra de navegação.

App.jsx: componente pai onde importaremos todos os componentes filhos do site e as bibliotecas usadas

.gitignore: arquivo para o git ignorar tudo o que queremos.

package.json: arquivo json onde estarão todas as dependencias e scripts do projeto.

README.md: arquivo para ler, onde documentamos o projeto.

Bibliotecas utilizadas no projeto:

mui/material: biblioteca externa de estilização, substituindo o CSS do site.
comandos: "npm install @mui/material @emotion/react @emotion/styled" e "npm install @mui/icons-material --legacy-peer-deps"

react-router-dom: biblioteca externa para criar as rotas do site, que irão linkar uma página a outra através do
mapeamento de URL.
comandos: "npm install react-router-dom"

json-server: biblioteca que cria um backend fake sem a necessidade de um banco de dados real, no caso do site UNIESP
oferecendo um CRUD de notícias dentro de db.json.
comandos: "npm install json-server"

axios: biblioteca usada para fazer as requisições HTTP do site.
comandos: "npm install axios"
