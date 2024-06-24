# Conecta Canaã - Front End

## Como iniciar o aplicativo?

### Adicionando as variáveis de ambiente
Para definir a URL das APIs, é necessário criar um arquivo com o nome `.env` na raiz do repositório. Os arquivos do repositório devem ser organizados como na imagem abaixo:

![Listagem dos arquivos](https://i.imgur.com/3wYJ1WM.png)
*Obs: Lembre-se que os arquivos não necessariamente são exatamente esses. Esta imagem apenas ressalta a criação do arquivo `.env`.*

Dentro do arquivo `.env`, deverão conter as seguintes variáveis:

- `REACT_APP_BASE_API_URL`
  - Ambiente de produção de Canaã: `https://conecta-api.smartcitycanaadoscarajas.com.br/`
  - Ambiente de homologação de Canaã: `https://conecta-api-hom.smartcitycanaadoscarajas.com.br/`


- `PORT`
  - Esta variável é utilizada ao subir o container utilizando o Docker de produção.
  - Qualquer valor numérico pode ser utilizado; geralmente a porta do React é `3000`.

O arquivo `.env` ficará assim:

![Mostrando .env](https://i.imgur.com/gBD4MA1.png)

Um arquivo com as variáveis de ambiente já configuradas pode ser encontrado na raiz do projeto. Para utilizá-lo, basta executar o comando: `cp env_example`

### Instalando dependências

Certifique-se de que você está utilizando a versão correta do Node.js (16.0) usando `node --version` no terminal. Recomenda-se utilizar o [nvm](https://github.com/nvm-sh/nvm) para gerenciar as versões do Node.js. Caso ainda não tenha o nvm instalado, siga as instruções no repositório oficial.

Para instalar as dependências do projeto, execute o comando:`npm install --force`

### Executando a aplicação

Para inicializar a aplicação use o comando `npm start`

![Mostrando .env](https://imgur.com/a/5atDYhs.png)


