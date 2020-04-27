## Desafio 02: Conceitos do Node.js

## **🚀 Sobre o desafio**

Essa é uma aplicação para armazenar repositórios do seu portfólio, que irá permitir a criação, listagem, atualização e remoção dos repositórios, e além disso permitir que os repositórios possam receber "likes".

### **🖥 Instalação**

```
    /* Clonar o repositório */
    git clone https://github.com/Jonathan-Sales/gostack11-conceitos-nodejs

    /* Instalar as dependências */
    yarn

    /* Iniciar o servidor */
    yarn dev
```

- Para rodar os testes, execute o comando abaixo:

```
    yarn test
```

### **Rotas da aplicação**

- **`POST /repositories`**: Rota de cadastro de um novo repositório
- **`GET /repositories`**: Rota que lista todos os repositórios;
- **`PUT /repositories/:id`**: Rota de atualização dos campos de título, url e tecnologias de um repositório;
- **`DELETE /repositories/:id`**: Rota para deletar um repositório;
- **`POST /repositories/:id/like`**: Rota para adicionar um like ao repositório;

## **📝 Licença**

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-01/LICENSE.md) para mais detalhes.
Y
