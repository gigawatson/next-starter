## Next.js Starter
```zsh
bun create next-app . --example https://github.com/gigawatson/next-starter
```

### Includes
- TypeScript
- Biome
- Prisma
- Tailwind CSS
- Zod
- next-safe-action
- React Hook Form
- shadcn/ui

Initialize Prisma:
```zsh
# https://bun.sh/guides/ecosystem/prisma
bunx --bun prisma init
```

Set the `DATABASE_URL` in `.env`:
```dotenv
DATABASE_URL="postgresql://{username}@localhost:5432/{database_name}"
```

Populate `schema.prisma` with models and then generate the schema:
```zsh
# https://bun.sh/guides/ecosystem/prisma
bunx prisma generate
```
