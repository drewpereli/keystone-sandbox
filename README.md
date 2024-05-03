# Keystone Project Starter

To make db change:
1. Change model file (schema.ts or file in ./models)
2. Run `npx keystone dev --no-db-push`. This updates `schema.prisma` without force-updating the database.
3. Run `npx keystone prisma migrate dev`
