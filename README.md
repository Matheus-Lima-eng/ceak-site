# CEAK Cambé — Site institucional com painel administrativo

Projeto em Next.js 14 + Tailwind CSS + Supabase, pronto para Git e Vercel.

## Recursos
- Site institucional responsivo com visual em azul-claro
- Estrutura inspirada em sites institucionais
- Seções: destaque, história, agenda, Instagram, contato e localização
- Painel administrativo com login
- Edição de telefone, e-mail, endereço, horário, textos e links
- Botão para sincronizar publicações do Instagram com 1 clique

## Instagram
A sincronização automática confiável depende da Instagram Graph API da Meta, com conta profissional vinculada a uma Página do Facebook. Sem isso, o projeto continua funcionando, mas a atualização real das postagens não pode operar de forma oficial.

## Instalação
```bash
npm install
npm run dev
```

## Banco
Execute `supabase/schema.sql` no SQL Editor do Supabase e depois opcionalmente `supabase/seed.sql`.

## Deploy
1. Suba para um repositório Git
2. Importe no Vercel
3. Configure as variáveis do `.env.example`
4. Faça o deploy
# ceak-site
