# Containers Docker para o Gerenciador de Riscos de Projetos

Configuração de containers do [Docker](https://docs.docker.com/engine/install/) para o [Gerenciador de Riscos de Projetos](https://github.com/iuryveloso/project-risk-manager) e sua [API](https://github.com/iuryveloso/api_project-risk-manager).

## Instalação

Primeiramente, é necessario ter instalado o [Docker](https://docs.docker.com/engine/install/) em seu computador.

Depois, clone este repositório e os da [aplicação](https://github.com/iuryveloso/project-risk-manager) e da [api](https://github.com/iuryveloso/api_project-risk-manager) para o diretório `~/Projects` do seu usuário.

Por fim, execute o seguinte comando no terminal:

```bash
docker compose up -d
```

A aplicação será executada em http://localhost:3000, enquanto a api em http://localhost:3333. O banco de dados utilizado é o [MongoDB](https://www.mongodb.com/), e pode ser acessado com o `cli`  [Mongo Express](https://github.com/mongo-express/mongo-express) localizado em http://localhost:8081.

As configuração do sistema devem seu feitas através de um arquivo `.env`, que pode ser criado a partir do arquivo `.env example`.
