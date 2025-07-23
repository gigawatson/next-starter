## Next.js Starter

```zsh
npx create-next-app --example https://github.com/gigawatson/next-starter .
```

### Includes

- TypeScript
- Prisma
- Tailwind CSS w/ Prettier Plugin
- Zod
- next-safe-action w/ React Hook Form adapter
- React Hook Form w/ Zod adapter
- ESLint
- Prettier

Initialize Prisma:

```zsh
npx prisma init
```

Set the `DATABASE_URL` in `.env`:

```dotenv
DATABASE_URL="postgresql://{username}@localhost:5432/{database_name}"
```

Populate `schema.prisma` with models and then generate the schema:

```zsh
npx prisma generate
```

Push the changes to the database:

```zsh
npx prisma db push
```

Database UI:

```zsh
npx prisma studio
```
