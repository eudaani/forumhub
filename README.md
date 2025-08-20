Aplicação Java com Spring Boot que simula um fórum de discussão, permitindo criar, listar, atualizar e deletar tópicos de forma segura.

Funcionalidades

Registro e login de usuários com JWT
Criação de tópicos vinculados a usuários e cursos
Atualização e exclusão de tópicos (apenas pelo autor)
Listagem de todos os tópicos ou por ID

Endpoints principais

POST /auth/register → Criar usuário
POST /auth/login → Login e gerar token JWT
POST /topics → Criar tópico (Bearer Token)
GET /topics → Listar todos os tópicos
GET /topics/{id} → Buscar tópico por ID
PUT /topics/{id} → Atualizar tópico (apenas autor)
DELETE /topics/{id} → Deletar tópico (apenas autor)
