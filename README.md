# Tutorial Básico: Como Rodar o Projeto Localmente

## Pré-requisitos

### 1. **Node.js**

- Baixe e instale a versão LTS do Node.js a partir do site oficial: [Node.js](https://nodejs.org/).

### 2. **MongoDB**

- Baixe, instale e execute o MongoDB localmente a partir de: [MongoDB](https://www.mongodb.com/try/download/community).

### 2. **Cloudinary**

- Crie uma conta grauita em: [Cloudinary](<https://cloudinary.com/>).

- Faça o login na conta criada e entre no Dashboard.

- No Dashboard copie os valores do Cloud Name, depois clique no botão "Go To API Keys".

- Copie os valores de API Key e API Secret.

- Os valores copiados serão usados posteriormente no arquivo `.env` do backend.

## Passos para Rodar o Projeto

1. **Clone o Repositório**

    **Método 1: Baixar direto pelo GitHub**
    - Acesse o repositório no GitHub: [plataforma-de-imoveis-para-universitarios](https://github.com/PedroHenriqueFonsec/plataforma-de-imoveis-para-universitarios)
    - Clique no botão "Code" e selecione "Download ZIP".
    - Baixe e extraia o arquivo ZIP.

    **Método 2: Utilizando Git**
    - Abra o terminal (ou prompt de comando) e execute o seguinte comando:

    ```bash
    git clone <https://github.com/PedroHenriqueFonsec/plataforma-de-imoveis-para-universitarios.git>
    ```

2. **Instale as Dependências**

    - Abra o terminal (ou prompt de comando) e navegue até a pasta raiz do projeto (substitua pelo caminho correto da pasta):

    ```bash
    cd /caminho/para/a/pasta/do/projeto/plataforma-de-imoveis-para-universitarios-main
    ```

- Backend

  - Navegue até a pasta do backend e instale as dependências.

    ```bash
    cd backend
    npm install
    ```

  - Crie um arquivo `.env` dentro da pasta backend com as seguintes variáveis:

    CLOUDINARY_CLOUD_NAME=<Cloud_Name_Do_Seu_Cloudinary>
    CLOUDINARY_API_KEY=<API_Key_Do_Seu_Cloudinary>
    CLOUDINARY_API_SECRET=<API_Secret_Do_Seu_Cloudinary>

  - Ainda dentro da pasta do backend no terminal (ou prompt de comando), inicie o backend com o seguinte comando:

    ```bash
    npm run dev
    ```

- Frontend

  - Abra uma nova aba do terminal, volte à pasta raiz do projeto, navegue até a pasta do frontend e instale as suas dependências:

    ```bash
    cd ../frontend
    npm install
    ```

  - Após instalar as dependências, inicie o frontend:

    ```bash
    npm run dev
    ```

3. **Acesse a plataforma**

- Assim que o frontend for iniciado, acesse o endereço exibido no terminal (geralmente <http://localhost:5173>, ou conforme indicado pelo Vite).
- 
