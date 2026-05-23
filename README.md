# BRRJ02 - Gestão de Salas (Mercado Livre)

Sistema interno para solicitação, aprovação e gestão de agendamentos de salas, desenvolvido utilizando **Google Apps Script**, **Bootstrap 5** e **Google Sheets** como banco de dados.

## 🚀 Funcionalidades

- **Painel do Usuário (Index):** Solicitação de salas (até 2 por pedido), verificação de e-mail `@mercadolivre.com`, consulta e cancelamento de agendamentos próprios e grade de disponibilidade semanal.
- **Painel Administrativo (Admin):** Controle de solicitações pendentes (aprovação/recusa individual ou em massa), agenda ativa dividida por períodos, gestão de bloqueios diários (Onwboarding) e criação de treinamentos por faixa horária.
- **Backend (Code.gs):** Sistema de travas (`LockService`) contra concorrência de agendamentos, indexação e cache de performance (`CacheService`), além de triggers assíncronas para disparos consolidados de notificações por e-mail.

## 🛠️ Tecnologias Utilizadas

- **Frontend:** HTML5, CSS3 (CSS Variables, Responsive Design), JavaScript (ES6, DOM Manipulation, AudioContext API).
- **Framework Visual:** Bootstrap 5 & Bootstrap Icons.
- **Fonts:** Sora (Google Fonts).
- **Backend:** Google Apps Script (GAS).
- **Database:** Google Sheets.
