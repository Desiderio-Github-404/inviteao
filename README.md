# InviteAO

Plataforma de convites digitais para eventos em Angola: criar, personalizar, publicar e partilhar convites com confirmação de presença (RSVP).

**Estado:** MVP em desenvolvimento | **Lançamento previsto:** dezembro de 2026.

## Stack
- React + TypeScript + Vite
- Supabase: Auth, PostgreSQL e Storage
- Vercel: deploy
- Provedor de pagamentos EMIS: integração após validação técnica e comercial

## Desenvolvimento
```bash
npm install
npm run dev
```

## Variáveis locais
Criar `.env.local` quando o Supabase estiver configurado:
```env
VITE_SUPABASE_URL=
VITE_SUPABASE_ANON_KEY=
```

Nunca colocar service-role keys, segredos ou credenciais de pagamento no frontend ou no Git.

## Módulos do MVP
1. Autenticação e perfil
2. Catálogo de templates
3. Editor de convites
4. Publicação e links públicos
5. RSVP e gestão de convidados
6. Planos e pagamentos
7. Administração

## Princípios
Mobile-first, segurança por defeito, privacidade dos convidados e validação de todos os fluxos.