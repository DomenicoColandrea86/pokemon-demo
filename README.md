# Which Pokémon is most round?

Answering all of life's toughest questions

## Quick Start

Copy and paste the following into Terminal:

```bash
git clone git@github.com:DomenicoColandrea86/pokemon-demo.git
cd pokemon-demo
nvm use
npm install
npm run dev
```

FYI - You will need to create a `.env` file and add a env config for `DATABASE_URL`. Feel free to ping me offline for that.

Alternatively, you could just spin up any database i.e. mongo, mysql, postgres, etc, and run a prisma schema migration to upload the projects schema. Just make sure to add your DB connection string to the env config `DATABASE_URL` so that Prisma can connect to it.

To run the Prisma schema migration you can run:

```bash
npm run db:push
```

## Prisma Studio

A Visual Interface for Your Database

```bash
npm run prisma:studio
```

## Database

[Planetscale](https://planetscale.com/) - The MySQL-compatible serverless database platform

Dashboard: https://app.planetscale.com/domenico-colandrea-msci/roundest-pokemon
