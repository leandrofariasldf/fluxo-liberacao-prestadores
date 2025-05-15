# Fluxo Power Automate: Liberação de Prestadores 🛠️

Este repositório contém um fluxo automatizado desenvolvido no Power Automate para gerenciar a entrada e aprovação de prestadores de serviço em ambientes corporativos.

## ✅ Funcionalidades

- Recebe dados via Microsoft Forms (nome, empresa, CPF/RG, placa)
- Envia e-mail de solicitação para aprovação
- Registra os dados dos prestadores liberados
- Notifica portaria ou setor responsável

## 📦 Arquivos

- `fluxo_liberacao_anonimizado.zip` – fluxo exportado, pronto para importação no Power Automate
- `fluxo_liberacao_anonimizado_final.json` – definição detalhada do fluxo, anonimizada
- `package.json`, `definition.json` etc. – arquivos internos do pacote, úteis para revisão manual

## 🚀 Como importar no Power Automate

1. Acesse [Power Automate](https://make.powerautomate.com/)
2. Vá em **Meus fluxos > Importar > Pacote (.zip)**
3. Faça upload de `fluxo_liberacao_anonimizado.zip`
4. Escolha "Criar como novo"
5. Conecte com suas credenciais e clique em **Importar**

## 🧽 Segurança e privacidade

Todos os dados sensíveis (e-mails, nomes, domínio da empresa, tenant ID) foram removidos ou substituídos por valores genéricos, garantindo a segurança da publicação pública.

## 💡 Dicas de uso

- Combine com Power BI para relatórios de acesso
- Pode ser estendido para controle de visitantes ou técnicos
- Integre com SharePoint ou Excel Online para armazenar históricos

## 📃 Licença

Este projeto é open-source e está licenciado sob a [MIT License](LICENSE).
