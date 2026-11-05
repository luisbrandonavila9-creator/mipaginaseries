---
name: supabase-cli
description: Usa el CLI de Supabase para crear migraciones, aplicar cambios y revisar el estado de la base de datos
---
# Supabase CLI

Comandos principales:
- `npx supabase migration new <nombre>`: crea una migración vacía
- `npx supabase db push`: aplica las migraciones al proyecto remoto
- `npx supabase migration list`: muestra migraciones aplicadas
- `npx supabase db diff`: muestra diferencias de esquema

Flujo: crear migración, escribir SQL, hacer push y verificar con migration list.