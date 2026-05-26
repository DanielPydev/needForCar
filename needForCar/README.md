<p align='center'> <h1 align='center'> NEEDFORCAR </h1></p>
<p align='center'><h3 align='center'> Compra e venda de veículos novos, seminovos e usados. <br> Rápido, de qualquer lugar do mundo.</h3></p>

<p align='center'> <h4 align='center'> powered by <a href="https://github.com/needforcar/">NeedForCar</a> </h4></p>

---

<p align='left'>
    <h5>
       A plataforma foi pensada para atuar como um grande mercado seguro e voltado somente para veículos. <br />
       Este projeto permite que o cliente encontre confiabilidade nesse tipo de serviço, pois o mercado de automóveis é bastante inseguro.<br />
       O sistema da NeedForCar utiliza um ecossistema de funcionabilidades e camadas de segurança para que apenas sejam comercializados veículos com informações confiáveis.
    </h5>
</p>

---

<p align="center"><h1 align="center"> Tecnologias Usadas </h1></p>
<p align="center">
    <img src="https://skillicons.dev/icons?i=react,vite,tailwindcss,nodejs,express,postgresql&theme=dark" />
</p>

---

- Entre em contato com a **[NeedForCar](https://github.com/needforcar)** para solucionar problemas não relatados nessa documentação!

## PASSOS PARA EXECUTAR O SISTEMA

* Clonar o projeto
```bash
git clone https://github.com/needforcar/needforcar.git

cd needforcar
```
* Instalar as dependências
  - Frontend
    ```bash
    cd client

    npm install
    ```
  - Backend
    ```bash
    cd server

    npm install
    ```
* Configurar variáveis de ambiente
```env
DATABASE_URL=postgresql://postgres:123456@localhost:5432/marketplace
PORT=3000
```
* Executar backend
```bash
cd server

npm run dev
```
Servidor:
`http://localhost:3000`
* Executar frontend
```bash
cd client

npm run dev
```
Aplicação: `http://localhost:5173`

## ESTRUTURA DO PROJETO
```
needforcar/
│
├── client/
├── server/
├── database/
├── docs/
├── .gitignore
├── README.md
└── package.json
```
`client/` - Frontend da aplicação, desenvolvido usando React e Vite. <br>
`server/` - Backend da aplicação, desenvolvido com Node.js e Express. <br>
`database/` - Arquivos relacionados ao Banco de Dados. <br>
`docs/` - Diretório relacionado a documentação do projeto. <br>
`.gitignore` - Definições de arquivos e diretórios ignorados pelo Git. <br>
`package.json` - Gerenciamneto de dependências e scripts do projeto. <br>

`README.md` - Arquivo principal de documentação do projeto (este documento).

### FUNCIONALIDADES DAS TECNOLOGIAS UTILIZADAS

| Tecnologia         | Categoria                   | Funcionalidade no projeto                                                    |
| ------------------ | --------------------------- | ---------------------------------------------------------------------------- |
| React              | Frontend                    | Desenvolvimento da interface web da aplicação                                |
| Vite               | Build                       | Inicialização do frontend e otimização do ambiente de desenvolvimento.       |
| Tailwind CSS       | Estilização                 | Criação da interface e estilização.                                          |
| Node.js            | Backend                     | Execução do servidor backend e gerenciamento de requisitos.                  |
| Express            | Backend Framework           | Gerenciamento da API.                                                        |
| PostgreSQL         | Banco de Dados              | Armazenamento e manipulação de usuários, anúncios e veículos.                |