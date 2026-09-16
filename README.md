# Shopee Affiliate Store — Netlify

Estrutura para publicar dois sites separados no Netlify usando o mesmo repositório GitHub:

- `vitrine/` → site público
- `admin/` → painel administrativo

Os dois usam o mesmo projeto Supabase.

## Netlify — Vitrine
Base directory: `vitrine`
Build command: deixar vazio
Publish directory: `.`

## Netlify — ADM
Base directory: `admin`
Build command: deixar vazio
Publish directory: `.`

## Responsividade
Os dois arquivos possuem regras CSS para telas menores e foram preparados para uso em celular.

## Importante
A chave publicada no frontend deve ser a chave pública/publishable do Supabase. Nunca coloque uma `service_role` no HTML.
