<div align="center">
  <h1>Enigma ︖</h1>
</div>

## 🖥️ Descrição

O Enigma é um projeto inovador para gestão segura de senhas e dados sensíveis. Nosso objetivo é fornecer uma plataforma confiável e fácil de usar para proteger as informações dos usuários.

---

## 📖 Backlog do Produto

<img src="public/images/backlog parte 1.png" alt="Backlog parte">
<img src="public/images/backlog parte 2.png" alt="Backlog parte">


---

## 🗓️ Cronograma e Sprints do projeto

| Sprint |    Período da Sprint    |                                       Link para a documentação                                       |     Status      |
| :----: | :---------------------: | :--------------------------------------------------------------------------------------------------: | :-------------: |
|   01   | 08/09/2025 a 28/09/2025 | [Relatório](https://github.com/CtrI-Alt-Del/gaia/blob/main/documentation/sprints/sprint-1-report.md) | Em andamento 🚧 |
|   02   | 06/10/2025 a 26/10/2025 | [Relatório](https://github.com/CtrI-Alt-Del/gaia/blob/main/documentation/sprints/sprint-2-report.md) |  Em andamento 🚧 |
|   03   | 03/11/2025 a 23/11/2025 | [Relatório](https://github.com/CtrI-Alt-Del/gaia/blob/main/documentation/sprints/sprint-3-report.md) |  Em andamento 🚧 |

---


## 🛠️ Tecnologias

### 📱 Mobile
- [React Native](https://reactnative.dev/) para construir a interface do aplicativo.
- [TypeScript](https://www.typescriptlang.org/) para garantir a tipagem estrita e a robustez do código.
- [Expo](https://expo.dev/) para facilitar o desenvolvimento e a distribuição do aplicativo.
- [GlueStack UI](https://glue-stack.com/) para criar componentes de interface consistentes e estilizados.

### 📟 Servidor
- [NestJS](https://nestjs.com/) para construir o servidor.
- [TypeScript](https://www.typescriptlang.org/) para garantir a tipagem estrita e a robustez do código.
- [Prisma](https://www.prisma.io/) para gerenciar o banco de dados.

### 📦 Banco de Dados
- [PostgreSQL](https://www.postgresql.org/) para o banco de dados.

---
## 📁 Estrutura do Repositório

O projeto segue uma arquitetura de microserviços com separação clara de
responsabilidades:

- **`enigma-server/`**: API REST desenvolvida em NestJS que gerencia e criptografia as senhas,notas seguras e usuarios.
- **`enigma-mobile/`**: Aplicativo mobile desenvolvida com Expo.
- **`documentation/`**: Documentação técnica e relatórios de progresso do
  projeto
---
## 🚀 Instalação

Para configurar e executar o projeto localmente, siga estas etapas:

### Pré-requisitos

Certifique-se de ter instalado:
- Node.js
- Yarn ou npm
- PostgreSQL

### Passos

1. Clone o repositório:
   ```bash
   git clone https://github.com/kaufon/enigma.git
   ```
2. Configuracao do servidor:
   <br/>
   2.1 Instale as dependencias
  ```bash
    cd enigma-server/
    npm install
   ``` 
  2.2 Configure as variaveis ambientes
  ```bash
    cp .env.example .env
   ```
  2.3 Inicie o container docker
  ```bash
    docker compose up -d &&
    npx prisma migrate dev
   ```
  2.4 Inicie o servidor
  ```bash
    npm run start:dev
   ```
3. Configuracao do mobile:
   <br/>
  3.1 Instale as dependencias
  ```bash
    cd enigma-mobile/
    npm install
   ```
  3.2 Configure as variaveis ambientes
  ```bash
    cp .env.example .env
   ```
  3.3 Inicie a aplicacao
  ```bash
    npm run start
   ```

---
## Documentação 📚
- [Documentação do Projeto]("./docs/README.md")
---

## 📜 Licença

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo [LICENSE](LICENSE).

## 👨‍💻 Autor

<div align="center">
  <img src="https://github.com/kaufon.png?size=220" width=120px> 
</div>
 
### Kauan Fonseca do Vale

> Desenvolvedor de Software Junior e estudante de Desenvolvimento de Sistemas Multiplataforma na [Fatec](https://fatecsjc-prd.azurewebsites.net/)


- <a href="https://github.com/kaufon"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"></a>  

- <a href="https://www.linkedin.com/in/kauan-fonseca-b62188300/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
