# pratica_prisma_cars

Prática de Pair Programming com prisma e TS.

O obbjetivo é migrar uma aplicação que utiliza o pacote pg que faz conexão com banco de dados Postgres para a ORM prisma.

As rotas disponpiveis são:

GET cars -> retorna os carros do banco <br>
GET cars/:id -> retorna um carro específico do banco <br>
POST cars ->  insere um carro no banco <br>
DELETE cars/:id -> deleta um carro específico do banco <br>
UPDATE cars/:id -> atualiza informações de um carro no banco. <br>

Instruções:

1. Rodar no terminal dentro da pasta do projeto o comando 'npm i' para instalar as dependências do banco.

2. Criar o banco de dados 'cars' no postgres.

3. Configurar a variàvel de ambiente para o correto acesso do banco pelo prisma.

4. Rodar o comando 'npx prisma db seed' para popular o banco.
