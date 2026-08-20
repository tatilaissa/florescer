# Florescer — PWA com Supabase Auth

Esta versão usa autenticação real do Supabase para:
- cadastro por e-mail e senha;
- login;
- logout;
- confirmação de e-mail (se habilitada no projeto);
- recuperação/redefinição de senha.

Projeto Supabase já configurado:
https://sbqlqikbmqtnpccuecwm.supabase.co

IMPORTANTE:
1. No Supabase, configure a URL do site e as Redirect URLs para o endereço final do PWA.
2. A chave incluída é uma publishable/anon key apropriada para cliente web; nunca coloque uma service_role/secret key no HTML.
3. Os dados do aplicativo continuam locais nesta versão. A autenticação é real, mas a sincronização dos dados entre dispositivos exige uma tabela com RLS. Essa etapa não foi aplicada ao banco neste ambiente.
