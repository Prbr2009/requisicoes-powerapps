# 📝 Sistema de Requisições Internas – Power Platform

Aplicação desenvolvida na Power Platform para gerenciamento de requisições internas corporativas, permitindo abertura, acompanhamento e controle de solicitações de forma estruturada e rastreável.

---

## 🎯 Objetivo do Projeto

Digitalizar e padronizar o processo de requisições internas, eliminando solicitações informais via e-mail ou mensagens, garantindo:

- Controle de status
- Rastreabilidade
- Transparência no atendimento
- Histórico organizado de solicitações

---

## 🚀 Funcionalidades Implementadas

✔ Abertura de requisição  
✔ Registro automático de solicitante  
✔ Definição de categoria / tipo de solicitação  
✔ Controle de status (Solicitado, Em andamento, Finalizado)  
✔ Visualização das requisições do usuário logado  
✔ Atualização automática de status  
✔ Histórico de registros  

---

## 🧠 Regras de Negócio

- Toda requisição inicia com status **Solicitado**
- Apenas responsáveis podem alterar o status
- Usuário visualiza apenas suas próprias requisições
- Alterações ficam registradas na base de dados
- Controle de datas para acompanhamento

---

## 🏗 Arquitetura da Solução

Usuário  
⬇  
Power Apps (Canvas App)  
⬇  
Power Automate (Fluxos de atualização e notificação)  
⬇  
Base de Dados (Excel Online / SharePoint)

---

## 🛠 Tecnologias Utilizadas

- Power Apps (Canvas)
- Power Fx
- Power Automate
- Excel Online / SharePoint
- Microsoft 365

---

## 📂 Estrutura do Repositório
****
