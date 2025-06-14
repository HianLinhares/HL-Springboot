📌 Projeto: API de Gestão de Clientes
Este projeto é uma API RESTful desenvolvida com Spring Boot, com o objetivo de gerenciar informações de clientes, incluindo cadastro, atualização, consulta e remoção de registros.

📋 Tecnologias utilizadas
Java 17

Spring Boot

Spring Web

Spring Data JPA

Banco de Dados H2 (ou outro de sua escolha)

Maven

🚀 Funcionalidades
✅ Cadastro de clientes

✅ Listagem de clientes

✅ Atualização de informações de clientes

✅ Exclusão de clientes

✅ Consulta de clientes por ID

🏗️ Estrutura do Projeto
css
Copiar
Editar
src/
 └─ main/
     ├─ java/
     │    └─ com/
     │         └─ linhare/
     │              └─ apiclientes/
     │                   ├─ controller/
     │                   ├─ service/
     │                   └─ repository/
     └─ resources/
          ├─ application.properties
          └─ data.sql (opcional para dados iniciais)
⚙️ Como executar o projeto localmente
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/HianLinhares/HL-Bota-de-mola.git
Acesse a pasta do projeto:

bash
Copiar
Editar
cd HL-Bota-de-mola
Execute o projeto (via Maven ou sua IDE):

bash
Copiar
Editar
./mvnw spring-boot:run
A API será executada na porta padrão:

arduino
Copiar
Editar
http://localhost:8080
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

✍️ Autor
Hian Linhares
