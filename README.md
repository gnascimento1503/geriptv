# IPTV Manager — PWA

Gerenciador completo de clientes IPTV com alertas de vencimento, controle de pagamento e integração WhatsApp.

## Funcionalidades

- **Dashboard** com estatísticas em tempo real (ativos, vencidos, vencem hoje, vencem em 7 dias)
- **Alertas automáticos** por faixa: vencidos/hoje, próximos 3 dias, próximos 7 dias
- **Cadastro completo** de clientes: nome, WhatsApp, plano, valor, data de vencimento, login IPTV
- **Botão WhatsApp** com mensagem pré-pronta e personalizada para cada situação
- **Registrar pagamento** com renovação automática da data (+30/90/180/365 dias)
- **Relatório de inadimplentes** com ação rápida
- **Exportar/Importar CSV** para backup
- **PWA** — funciona offline, pode ser instalado no celular e no PC

## Como subir no GitHub Pages

1. Crie um repositório no GitHub (ex: `iptv-manager`)
2. Faça upload de todos os arquivos desta pasta
3. Vá em **Settings → Pages**
4. Em "Branch", selecione `main` e salve
5. Acesse: `https://seuusuario.github.io/iptv-manager`

## Instalar como app no celular

1. Abra o link no Chrome (Android) ou Safari (iPhone)
2. No Android: menu → "Adicionar à tela inicial"
3. No iPhone: botão compartilhar → "Adicionar à Tela de Início"

## Dados

Todos os dados ficam salvos localmente no navegador (`localStorage`).
Use **Exportar CSV** regularmente para fazer backup.

## Ícones (opcional)

Coloque `icon-192.png` e `icon-512.png` na mesma pasta para o ícone aparecer ao instalar.
