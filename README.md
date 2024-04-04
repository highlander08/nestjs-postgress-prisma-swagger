# Servidor PostgreSQL conectado a ele o Prisma. Por fim, API REST com nestjs e a documentação com Swagger.

command: npm install
command: docker-compose up -d
command: npx prisma migrate dev --name 'init'
command: npx prisma studio
command: npx run start:dev
