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

/ (Raiz do Projeto) |-- Técnico/ | |-- login-tecnico.html | |-- painel-tecnico.html | |-- historico.html | |-- ajuda-tecnico.html | |-- painel.css | |-- style-login.css |-- Encarregado/ | |-- login-encarregado.html | |-- painel-encarregado.html | |-- encarregado-criar-1.html | |-- encarregado-criar-2.html | |-- encarregado-pendentes.html | |-- encarregado-aprovadas.html | |-- encarregado-rejeitadas.html | |-- login-encarregado.css | |-- style-encarregado.css | |-- encarregado-scripts.js |-- Gestor/ | |-- login-gestor.html | |-- painel-gestor.html | |-- gestor-analise.html | |-- gestor-aprovadas.html | |-- gestor-rejeitadas.html | |-- style-gestor.css | |-- painel-gestor.css | |-- gestor-scripts.js |-- recuperar-senha.html |-- senha.css |-- README.md

*(Certifique-se de que esta estrutura corresponde exatamente aos seus arquivos)*

## Como Executar

Este é um projeto puramente front-end. Para visualizá-lo:
1.  Clone ou baixe os arquivos para o seu computador.
2.  Abra qualquer um dos arquivos `.html` (recomendado começar pelos de login: `login-tecnico.html`, `login-encarregado.html` ou `login-gestor.html`) diretamente em um navegador web moderno (Chrome, Firefox, Edge, etc.).
3.  Navegue pelas telas utilizando os links e botões.

## Tecnologias Utilizadas

* **HTML5:** Estruturação do conteúdo.
* **CSS3:** Estilização visual (layouts, cores, fontes). Foram usados arquivos CSS separados por módulo/função. Conceitos como Flexbox foram aplicados para layout.
* **JavaScript (ES6 Básico):** Para simulação de feedback interativo nas telas de criação de solicitação (Encarregado) e análise (Gestor).
* **Bootstrap 5 (Parcial):** Utilizado na refatoração do Painel do Gestor para aplicar conceitos de Grid Responsivo e Componentes (introduzido nas aulas).

## Autor

* [Seu Nome Completo]

## Status do Projeto

* Protótipo Front-End Funcional - Concluído (interfaces principais).

## Próximos Passos / Melhorias Futuras (Sugestões)

* Implementação do Back-End (ex: PHP, Node.js, Python/Django) para processar logins, salvar e recuperar dados.
* Integração com um Banco de Dados (ex: MySQL, PostgreSQL) para persistir as informações.
* Validação completa dos formulários com JavaScript.
* Implementação de autenticação e sessões de usuário seguras.
* Refatoração completa para usar Bootstrap 5 em todo o projeto (opcional).
* Desenvolvimento das funcionalidades "Centro de Custos" e "Detalhes da Solicitação".
* Melhoria da responsividade em todas as telas, especialmente nas partes com CSS customizado.
