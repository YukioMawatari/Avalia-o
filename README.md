# Desafio da Leila
### 💻 Como executar:

    ⬇️ Instale as dependências
          npm install
          
    🗄️ Certifique-se de que o MongoDB está rodando localmente e utilize o seguinte trecho no arquivo dsin_test
    
    ⬆️ Inicie o servidor
          npm start

### 🛠️ Tecnologias Utilizadas

          🟢 NodeJS: Plataforma de execução de JavaScript no servidor.
          ⚡ Express.js: Framework para construção de APIs robustas e eficientes.
          🗄️ MongoDB: Banco de dados NoSQL utilizado para armazenamento.
          ⚒️ Mongoose: Biblioteca para modelagem de dados no MongoDB.
          ◾ npm: Gerenciador de pacotes para instalar dependências do projeto.
          🔡 CORS: Middleware para gerenciar compartilhamento de recursos entre origens diferentes.

### Endpoints

              POST /agendamentos: Cria um novo agendamento.
              PUT /agendamentos/:id: Atualiza um agendamento existente pelo ID.
              GET /agendamentos: Retorna todos os agendamentos.
              GET /agendamentos/:id: Retorna um agendamento específico pelo ID.
              DELETE /agendamentos/:id: Exclui um agendamento pelo ID.

http://localhost:3000/agendamentos/
