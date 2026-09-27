# Bolão Garcia 3.0

Protótipo navegável + esquema inicial para migração para Supabase/PostgreSQL.

## Protótipo
Abra `index.html`. Esta versão demonstra cadastro, conta, palpites, código, ranking, fechamento de rodada e painel administrativo. Os dados ficam no localStorage do navegador.

## Produção
Use `supabase_schema.sql` como ponto de partida. A implantação real deve:
1. criar projeto Supabase;
2. executar o schema;
3. configurar Auth;
4. habilitar RLS/policies;
5. conectar o front-end ao Supabase;
6. proteger a área administrativa;
7. configurar domínio/hosting;
8. definir regras de negócio e aspectos jurídicos/regulatórios antes de qualquer cobrança ou premiação.