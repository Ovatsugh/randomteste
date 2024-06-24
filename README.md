# Conecta Canaã - Front End

## Inicio do ambiente

1. Clone este repositório
2. Certifique-se que você tenha o Node.js e NPM instalado.
3. Instale as dependências do projeto listadas em `package.json`:

```
npm install --force
```

- ⚠️ É importante que você esteja utilizando a versão correta do Node.js (16.0.0), confira usando `node --version` no terminal. Recomenda-se utilizar o [nvm](https://github.com/nvm-sh/nvm) para gerenciar as versões do Node.js. Caso ainda não tenha o nvm instalado, siga as instruções no [repositório](https://github.com/nvm-sh/nvm) oficial.

## Adicionando as variáveis de ambiente

Para definir a URL das APIs, é necessário criar um arquivo com o nome `.env` na raiz do repositório. Um arquivo com as variáveis de ambiente já configuradas pode ser encontrado na raiz do projeto. Para utilizá-lo, basta executar o comando: 

```
cp env_example
```

Dentro do arquivo `.env`, deverão conter as seguintes variáveis:

- `REACT_APP_BASE_API_URL`
  - Ambiente de produção de Canaã: `https://conecta-api.smartcitycanaadoscarajas.com.br/`
  - Ambiente de homologação de Canaã: `https://conecta-api-hom.smartcitycanaadoscarajas.com.br/`


- `PORT`
  - Esta variável é utilizada ao subir o container utilizando o Docker de produção.
  - Qualquer valor numérico pode ser utilizado; geralmente a porta do React é `3000`.

## Estrutura do projeto

Após fazer o clone do repositório a estrutura do seu projeto irá se parecer com isso:

```

├── README.md
├── nginx
├── node_modules
├── public
├── src
├── .env
├── .eslintcache
├── .gitignore
├── .gitlab-ci.yml 
├── .Brewfile 
├── .env_example 
├── package-lock.json
├── package.json
├── README.md
├── tailwind.config.js
├── webpack.config.js
└── yarn.lock
```

## Executando a aplicação

Para inicializar a aplicação use o comando:

 ```
 npm start
 ```

![Mostrando .env](https://i.imgur.com/1b04WLa.png)

## Navegadores testados

Essa é a lista de navegadores testados e suportados atualmente:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">


## Links úteis

- 📚 [Conecta API](https://gitlab.smartcitycanaadoscarajas.com.br/ramon141/canaa-conecta-api) - Backend da aplicação



