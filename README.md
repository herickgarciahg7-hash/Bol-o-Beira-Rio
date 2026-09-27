BOLÃO BEIRA RIO 4.0

Esta versão é uma evolução do protótipo 3.0, com:
- layout e fluxo mobile;
- cadastro de participante;
- palpites 1/X/2;
- código de participação;
- envio para WhatsApp;
- painel administrativo;
- abertura/fechamento da rodada;
- cadastro de jogos;
- resultados e ranking;
- backup dos dados em JSON;
- esquema SQL preparado para Supabase.

IMPORTANTE
Ainda há localStorage nesta entrega. Portanto, alterações feitas no painel deste navegador NÃO são compartilhadas automaticamente com outros celulares. A etapa seguinte é conectar o front-end ao Supabase e colocar autenticação do administrador.

ANTES DE PUBLICAR
- Troque o PIN 1234 no index.html.
- Troque 5534999999999 pelo WhatsApp real.
- Para uso multiusuário, não use localStorage como banco definitivo.
- Avalie separadamente as regras aplicáveis caso haja cobrança, prêmio ou outra forma de participação financeira.

ARQUIVOS
- index.html: sistema
- supabase_schema.sql: estrutura inicial do banco online