# 📰 Portal de Notícias PBE (Backend)

👤 Identificação
Nome Completo: Emilly Raissa Nascimento 

🌟 Este projeto é um Portal de Notícias desenvolvido como parte do curso de Programação Backend (PBE). O foco desse sistema é a pesquisa automatizada utilizando uma API (NewsAPI.org) que possibilita a busca personalizada por notícias em tempo real.

🚀 Como Rodar o Projeto Localmente

1. Pré-requisitos
Possuir o Node.js e o npm instalados.

2. Obtenção da Chave API
Acesse https://newsapi.org/ e clique em "Get API Key".
(Copie sua chave e a guarde para ser utilizada posteriormente.)

3. Configuração do Ambiente e Estrutura do Projeto

Instale as dependências do projeto via terminal:
npm install
Crie o arquivo de configuração de segurança .env na raiz do projeto.
Adicione sua chave de API e a porta de execução no arquivo .env (sem aspas):

```
API_KEY=SUA_CHAVE_OBTIDA_AQUI
PORT=3000
```

4. Execução do Servidor
Execute o servidor Node.js no terminal:

node app.js

Uma mensagem de sucesso será exibida:
```
Servidor rodando em http://localhost:3000
```

Abra seu navegador e acesse o endereço: http://localhost:3000

📂 Estrutura final do Projeto
```
portal-backend/
├── public/                # Arquivos estáticos como Imagens
│ └── img/
├── views/                 # Arquivos EJS (HTML)
│ └── index.ejs
├── .env                   # Variáveis de ambiente e chave de API
├── app.js                 # Servidor principal 
├── package.json         
└── .gitignore             # Probir .env e node_modules de serem enviados ao GitHub

```
