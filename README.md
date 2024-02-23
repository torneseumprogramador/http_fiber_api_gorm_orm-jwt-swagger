## Descrição
Este é um aplicativo desenvolvido em Go (Golang) utilizando o framework Fiber, o ORM GORM, JWT para autenticação e Swagger para documentação da API. Ele foi criado como parte do desafio do curso "Torne-se um Programador" sobre Go Lang. O objetivo deste aplicativo é fornecer um sistema básico com funcionalidades de login e gestão de recursos.

## Estrutura do Projeto
O projeto está estruturado da seguinte forma:

```
.
├── app
│   ├── controllers
│   ├── dtos
│   ├── model_views
│   ├── models
│   └── services
├── docs
├── pkg
│   ├── config
│   ├── middleware
│   └── routes
└── platform
    ├── database
    └── migrations
```

### Diretórios Principais

- **app**: Contém a lógica principal do aplicativo.
- **docs**: Documentação do projeto, incluindo especificações do Swagger.
- **pkg**: Pacotes reutilizáveis que podem ser usados em diferentes partes do projeto.
- **platform**: Configurações específicas da plataforma, como configurações de banco de dados e migrações.

## Funcionalidades

O aplicativo possui as seguintes funcionalidades:

- **Login**: Permite que os usuários façam login na plataforma.
- **Gestão de Recursos**: Possibilita a gestão de recursos do sistema.

## Instalação

1. Certifique-se de ter o Go instalado. Se não tiver, siga as instruções em [golang.org](https://golang.org/doc/install).

2. Clone o repositório:

```
git clone https://github.com/torneseumprogramador/http_fiber_api_gorm_orm-jwt-swagger.git
```

3. Navegue até o diretório do projeto:

```
cd http_fiber_api_gorm_orm-jwt-swagger
```

4. Execute o aplicativo:

```
go run main.go
```

## Documentação

A documentação do projeto pode ser encontrada na pasta `docs`, incluindo as especificações do Swagger para a API.

## Contribuindo

Sinta-se à vontade para contribuir com este projeto. Se encontrar algum problema ou tiver sugestões, por favor, abra uma *issue* ou envie um *pull request*.

## Comunidade

Este projeto é uma iniciativa da comunidade "Torne-se um Programador". Junte-se a nós para aprender e colaborar em mais projetos emocionantes. Visite [torneseumprogramador.com.br](https://www.torneseumprogramador.com.br) para mais informações e confira o curso [Desafio Go Lang](https://www.torneseumprogramador.com.br/cursos/desafio_go_lang).

## Licença

Este projeto está licenciado sob a licença [MIT](https://opensource.org/licenses/MIT).
