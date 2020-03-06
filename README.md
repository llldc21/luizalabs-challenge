# <center> Desafio Técnico - LuizaLabs </center>

### Requisitos
- [NodeJS]()
- [Docker]()
- [Docker Compose]()
- [Yarn]() / [NPM]()

### Funcionamento
Os comandos a seguir serão exibidos na expectativa de que o gerenciador de pacotes para o Node escolhido seja o Yarn. Mas podem ser reproduzidos de igual forma caso o gerenciador escolhido sejam o NPM.

1. Iniciar o banco de dados.
```
yarn container:up
```

2. Rodar as migrations e seeds do banco de dados.
```
yarn migrate:run && yarn seeds:run
```

3. Iniciar a api.
```
yarn start
```

### Outros comandos
1. Para o container.
```
yarn container:down
```

2. Rodar o projeto em modo de desenvolvimento.
```
yarn start:dev
```

3. Rodar os testes.
```
yarn test
```

Para visualizar o *code coverage* inserir ao final do comando que roda os testes `--coverage`