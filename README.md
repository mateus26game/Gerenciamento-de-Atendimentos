# Gerenciamento de Atendimentos - API em Node.js com Express e MySQL

Este projeto é uma API para gerenciamento de atendimentos, desenvolvida em Node.js com o framework Express e MySQL para armazenamento de dados. A aplicação permite realizar operações de criação, leitura, atualização e exclusão (CRUD) de atendimentos, com estrutura modular e organizada para fácil manutenção e expansão.


# Funcionalidades

* CRUD de Atendimentos:

* GET /atendimentos - Retorna todos os atendimentos cadastrados.

* POST /atendimentos - Adiciona um novo atendimento ao banco de dados.

* PUT /atendimento/:id - Atualiza as informações de um atendimento específico.

* DELETE /atendimento/:id - Remove um atendimento pelo ID.

* Conexão com MySQL: Configuração e criação de tabelas no banco de dados MySQL, incluindo criação automática da tabela atendimentos se ainda não existir.

* Estrutura modular: Separação em rotas, modelos, controladores e infraestrutura de banco de dados, facilitando a manutenção e expansão.


#  Estrutura do Projeto


* Rotas: Define endpoints para interagir com os atendimentos

* Modelos: Define a interação com o banco de dados, encapsulando as consultas SQL.

* Controladores: Implementa a lógica de cada endpoint para comunicação entre o modelo e a rota.

* Infraestrutura: Configuração da conexão com o MySQL e criação de tabelas.

# Tecnologias Utilizadas

* Node.js e Express: Para criar o servidor e definir a API.
* MySQL: Banco de dados relacional para armazenamento de informações.
* Config: Gerenciamento de variáveis de ambiente e configurações.
