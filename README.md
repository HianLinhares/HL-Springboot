
📌 Projeto: API de Gestão de Clientes
Este projeto é uma API RESTful desenvolvida com Spring Boot, com o objetivo de gerenciar informações de clientes, incluindo cadastro, atualização, consulta e remoção de registros.

📋 Tecnologias utilizadas
Java 17

Spring Boot📋 Tecnologias utilizadas
Java 17
Spring Boot

🧪 Exemplos de endpoints
GET /clientes → Lista todos os clientes

GET /clientes/{id} → Busca um cliente por ID

POST /clientes → Cria um novo cliente

PUT /clientes/{id} → Atualiza um cliente existente

DELETE /clientes/{id} → Remove um cliente

💡 Git Flow utilizado
Este projeto segue o fluxo de versionamento Git Flow, com as seguintes branches principais:

main → Versão estável em produção

dev → Ambiente de desenvolvimento

feature/* → Novas funcionalidades

hotfix/* → Correções emergenciais

Fluxo resumido:

Criar branchs de feature a partir da dev

Merge na dev após a finalização

Pull Request de dev para main quando for realizar um release
