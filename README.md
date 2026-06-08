# sistema_login

# 1. Instala a ferramenta de linha de comando do NestJS globalmente no computador
npm install -g @nestjs/cli

# 2. Cria a estrutura inicial de um novo projeto NestJS chamado "backend"
npx nest new backend

# 3. Entra na pasta do projeto que acabou de ser criada
cd backend

# 4. Inicia o servidor de desenvolvimento para testar se tudo está rodando (opcional)
npm run start

# 5. Instala o banco de dados (SQLite), o ORM (TypeORM) e a biblioteca de criptografia de senhas (bcrypt)
npm i @nestjs/typeorm typeorm better-sqlite3 bcrypt

# 6. Instala os tipos do bcrypt para o TypeScript não acusar erros no código
npm i --save-dev @types/bcrypt

# 7. Gera automaticamente a estrutura (módulo, controller, service) para a autenticação
npx nest generate resource autenticacao