# Sistema RDO/FVS AVG

Sistema web em React + Vite + Supabase para RDO, FVS, fotos e PDF.

## Instalação local
1. Rode `npm install`
2. Copie `.env.example` para `.env`
3. Preencha `VITE_SUPABASE_URL` e `VITE_SUPABASE_ANON_KEY`
4. Rode `npm run dev`

## Supabase
1. Rode `supabase_schema.sql` no SQL Editor
2. Crie um bucket público chamado `fotos`
3. Cadastre seu usuário pelo site
4. Na tabela `profiles`, altere seu usuário para `role = super_admin` e `status = approved`
