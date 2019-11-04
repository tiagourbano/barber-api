Tecnologias e pacotes
- Sequelize - ORM
- YUP - validacao de formulario
- Bcrypt - encriptacao de senha
- JWT - criptografia para autenticacao
- Multer - upload de imagem
- Nodemailer - servico de envio de emails
- HandlebarJS - template engine
- Bee Queue - gerenciador de filas super performatico
- Kue - gerenciador de filas
- Sentry - gerenciamento de erros da aplicacao em tempo real
- dotenv - carrega variaveis de ambiente


SUBIR DOCKER POSTGRES

docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d postgres


SUBIR DOCKER MONGODB

docker run --name mongobarber -p 27017:27017 -d -t mongo

SUBIR DOCKER REDIS

docker run --name redisbarber -p 6379:6379 -d -t redis:alpine



PARA RODAR O PROJETO EXECUTAR OS SEGUINTES COMANDOS:
- npm run dev
- npm run queue

PS: Garantir que os 3 docker estao funcionando
