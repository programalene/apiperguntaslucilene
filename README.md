"# apiperguntaslucilene" 
API de Perguntas para Quiz
Este é um projeto desenvolvido em Node.js que consiste em uma API para fornecer perguntas e respostas para um quiz. A API utiliza o framework Express e está conectada a um banco de dados MySQL. Além disso, possui recursos para autenticação de usuários e operações CRUD (Create, Read, Update, Delete) para perguntas.

Este projeto foi desenvolvido como parte de um curso de Programador de Sistemas no Senac Catalão, em 2023, para ser utilizado como uma API para um aplicativo de quiz desenvolvido em Flutter. O aplicativo de quiz foi criado para oferecer uma experiência interativa de perguntas e respostas aos usuários.

A API permite que o aplicativo de quiz faça uma comunicação com o banco de dados MySQL para obter as perguntas, cadastrar novas perguntas, atualizar perguntas existentes, excluir perguntas e autenticar usuários. Ela também fornece endpoints para obter informações sobre os usuários cadastrados.

Esse projeto é uma ótima oportunidade para aprender sobre o desenvolvimento de APIs em Node.js, o uso do framework Express e a integração com um banco de dados MySQL. Além disso, permite a construção de um aplicativo em Flutter que interaja com essa API para criar uma experiência envolvente de quiz para os usuários.

Sinta-se à vontade para explorar e modificar este projeto, adaptando-o às suas necessidades e melhorando-o de acordo com seu aprendizado e experiência.

Configuração
Certifique-se de ter o Node.js instalado em sua máquina.
Clone este repositório para o seu ambiente local.
Execute o comando npm install para instalar as dependências necessárias.
Banco de Dados
A API requer um banco de dados MySQL para armazenar as perguntas e as informações dos usuários. Verifique se você possui um banco de dados configurado e atualize as informações de conexão no arquivo index.js, na variável connection. Você precisará fornecer o host, usuário, senha e nome do banco de dados.

Endpoints
A API possui os seguintes endpoints:

GET /: Retorna uma mensagem de boas-vindas.
GET /perguntas: Retorna todas as perguntas disponíveis no banco de dados.
GET /perguntas_administracao: Retorna todas as perguntas disponíveis no banco de dados, incluindo todas as respostas.
GET /usuarios: Retorna todos os usuários cadastrados no banco de dados.
POST /login: Autentica um usuário com base no login e senha fornecidos.
GET /perguntas/🆔 Retorna uma pergunta específica com base no ID fornecido.
POST /perguntas: Cria uma nova pergunta no banco de dados.
PUT /perguntas/🆔 Atualiza uma pergunta existente com base no ID fornecido.
DELETE /perguntas/🆔 Exclui uma pergunta existente com base no ID fornecido.
Executando a API
Execute o comando node index.js para iniciar a API. Ela estará disponível no localhost na porta 3000 (http://localhost:3000/).

Dependências
A API utiliza as seguintes dependências:

express: Framework web para Node.js.
cors: Middleware para habilitar o CORS (Cross-Origin Resource Sharing) na API.
mysql: Pacote para interagir com o banco de dados MySQL.
body-parser: Middleware para fazer o parsing dos dados recebidos no corpo das requisições.
Certifique-se de ter essas dependências instaladas corretamente antes de executar a API.

Licença
Este projeto está licenciado sob a licença Creative Commons Attribution 4.0 International. Consulte o arquivo LICENSE para obter mais informações.
