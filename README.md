# Sistema de Gerenciamento de Horas Extras (Protótipo Front-End)

## Descrição do Projeto

Este projeto é um protótipo front-end para um sistema web focado no controle e aprovação de solicitações de horas extras. Ele foi desenvolvido como parte de um Projeto Integrador, combinando conceitos de UX/UI (design e wireframes) com Construção Web (HTML, CSS, JavaScript básico e Bootstrap).

O sistema simula as interfaces e fluxos de navegação para três perfis de usuário distintos:
* **Técnico:** Consulta suas horas extras programadas e histórico.
* **Encarregado:** Cria novas solicitações de horas extras para sua equipe, visualiza o status (pendentes, aprovadas, rejeitadas).
* **Gestor:** Analisa as solicitações pendentes (podendo simular aprovação/rejeição), visualiza históricos e um resumo financeiro.

## Contexto Acadêmico

* **Disciplinas:** Projeto Integrador (UX/UI e Construção Web)
* **Objetivo:** Implementar os wireframes e fluxos de usuário definidos na fase de design, utilizando tecnologias front-end para criar um protótipo interativo.

## Funcionalidades Implementadas (Front-End)

* Telas de Login separadas por perfil.
* Tela de Recuperação de Senha (interface).
* **Painel do Técnico:**
    * Visualização de Próximos Agendamentos (simulado).
    * Visualização de Histórico (simulado).
    * Tela de Ajuda/Suporte (interface).
* **Painel do Encarregado:**
    * Tela Inicial com resumo e navegação.
    * Formulário de Criação de Nova Solicitação (2 etapas).
    * Simulação de feedback (sucesso/erro) no envio do formulário (usando JS básico).
    * Visualização de Solicitações Pendentes (tabela).
    * Visualização de Solicitações Aprovadas (tabela).
    * Visualização de Solicitações Rejeitadas (tabela).
* **Painel do Gestor:**
    * Tela Inicial com resumo financeiro (simulado).
    * Tela de Análise de Solicitação Pendente.
    * Simulação de Aprovação/Rejeição com feedback visual (usando JS básico).
    * Visualização de Histórico de Aprovações (tabela).
    * Visualização de Histórico de Rejeições (tabela).

## Estrutura do Projeto

O projeto está organizado com arquivos HTML e CSS separados por perfil:
