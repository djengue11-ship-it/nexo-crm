# Nexo CRM

CRM demonstrativo em português para gestão de clientes, agendamentos, faturas e tarefas.

## Executar
Abra `index.html` num navegador ou publique os ficheiros estáticos no GitHub Pages.

## Incluído
- Painel de indicadores e valores por receber
- Registo e pesquisa de clientes
- Criação de faturas e atualização manual de estado
- Agendamentos e tarefas
- Regras demonstrativas de automação
- Interface responsiva para desktop e telemóvel
- Persistência local via `localStorage`

## Limitações
Esta versão é um protótipo: os dados ficam apenas no navegador e não sincronizam entre utilizadores/dispositivos. Não envia e-mails/WhatsApp, não emite faturas fiscais oficiais e não processa pagamentos. Não utilize dados sensíveis reais.

## Próximas etapas para produção
1. Backend, base de dados, autenticação e cópias de segurança.
2. Perfis e isolamento de dados por organização.
3. PDFs de faturas e configuração fiscal adequada a Angola.
4. Integração autorizada com e-mail e WhatsApp Business.
5. Pagamentos e confirmação via webhook.
6. Lembretes automáticos no servidor, consentimento e logs.
