# Node With Prisma Working

## Make it work

1 - Clone the repo
2 - go to node-working
3 - then install dependencies

```bash
npm i
```

4 - Put your mongo db url inside the .env (I say mongo since it's this one I use in seeders and who make the bug with the bun version)

5 - execute the prisma generate

```bash
npm run generate
```

6 - execute the seeder

```bash
npm run seed
```

# Node With Prisma Working

## Make it work

1 - Clone the repo
2 - go to bun-bugged
3 - then install dependencies

```bash
bun i
```

4 - Put your mongo db url inside the .env (I say mongo since it's this one I use in seeders and who make the bug with the bun version)

5 - execute the prisma generate

```bash
bun generate
```

6 - execute the seeder

```bash
bun seed
```

And now you will see the difference. Nothing happen in DB + silent error since nothing is prompted, the catch seems to not work and no console.log or console.error