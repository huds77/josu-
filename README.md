# CRUD

Este projeto é um sistema básico de CRUD (Create, Read, Update, Delete) desenvolvido em TypeScript

## Configuração

### Pré-requisitos

Certifique-se de ter o Node.js e o npm instalados.

```bash
npm install
```

### Instalando Dependências

Instale o TypeScript, o Prisma e o Express junto com suas respectivas definições de tipo.

```bash
npm install typescript ts-node @types/node --save-dev
npx tsc --init
npm install prisma --save-dev
npx prisma init
```

#### Configuração do Banco de Dados

Atualize o arquivo `.env` com as seguintes configurações de banco de dados:

```dotenv
DATABASE_URL=postgresql://hsilva@ep-rapid-limit-10387553-pooler.us-east-2.aws.neon.tech/hudsonj?sslmode=require&pgbouncer=true&connect_timeout=10
DIRECT_URL=postgresql://hsilva@ep-rapid-limit-10387553.us-east-2.aws.neon.tech/hudsonj?sslmode=require&connect_timeout=10
```

### Instalando Express e Definições de Tipo do TypeScript

Instale o Express e as definições de tipo do TypeScript para o Express.

```bash
npm install express
npm install --save-dev @types/express
```

## Rodando o Servidor

Para iniciar o servidor, execute:

```bash
npx tsx server.ts
```

## Desenvolvimento

Se você estiver desenvolvendo o projeto, considere os seguintes passos:

### Instalando Dependências de Desenvolvimento

```bash
npm install --only=dev
```

### Rodando em Modo de Desenvolvimento

```bash
npm run dev
```

