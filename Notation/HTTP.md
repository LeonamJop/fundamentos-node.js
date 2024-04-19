- HTTP
  - Método HTTP
  - URL

GET, POST, PUT, PATCH, DELETE

GET => Busrcar um recurso do back-end
PSOT => Criar um recurso no back-end
PUT => Atualizar um recurso no back-end
PATCH => Atualizar uma informação específica de um recurso no back-end
DELETE => Deletar um recurso do back-end

GET /users => Buscando usuários do back-end
POST /users => Criar um usuário do back-end

Stateful != Stateless

JSON => JavaScript Object Notation

Cabeçalhos (Requisição/resposta) => Metadados

Query Parameters: URL Stateful => Filtros, paginação, não-obrigatórios, infromações não sensíveis,(http://localhost:3333/users?userId=1).

Route Parameters: Identificação de recurso, infromações não sensíveis,
(http://localhost:3333/users/1).

Request Body: Envio de informações de um formulário (HTTPs)