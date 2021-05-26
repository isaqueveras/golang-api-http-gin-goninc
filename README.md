# Criando uma API usando golang e Gin
Criando uma api simples, utilizando apenas um array de usuários, onde consigo fazer todo o CRUD dele.
Para inicializar e testar o projeto, basta rodar o seguinte código `go run main.go` dentro do diretorio. Utilize o _Insomnia_ para fazer os testes de requisição

## Requisições http
### Listar usuários
[GET] http://localhost:3131/users/

### Cadastrar usuário
[POST] http://localhost:3131/users/

### Editar usuário
[PUT] http://localhost:3131/users/:id

### Excluir usuários
[DELETE] http://localhost:3131/users/:id
