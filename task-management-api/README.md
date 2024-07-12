# Task Management API

## Descrição
API para gerenciamento de tarefas utilizando Flask.

## Instalação
1. Clone o repositório:
git clone <repo-url>

2. Navegue até o diretório:
cd task-management-api

3. Construa o container Docker:
docker build -t task-management-api .

Copiar código
4. Execute o container:
docker run -p 5000:5000 task-management-api
 
## Endpoints
- `GET /tasks`
- `POST /tasks`
- `PUT /tasks/{id}`
- `DELETE /tasks/{id}`