# Cenário

## Introdução

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da construção dos Cenários, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) |                                       |
| [Arthur Henrique](https://github.com/arthurhvieira1) |                                       |
| [Felipe Guimaraes](https://github.com/felipegf1) |                                       |
| [João Felipe](https://github.com/MrBolt2005) |                                       |
| [João Sapiência](https://github.com/JoaoSapiencia) |                                       |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  Criou os cenários 04, 05 e 06, que são referentes, respectivamente, aos requisitos RF15, RF19 e RF20.                                 |
| [Vilmar José](https://github.com/VilmarFagundes) |                                       |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Metodologia

## Cenários

### Cenário 04: Lembretes de Revisão de Conteúdos
**Requisito Associado:** RF15 - O sistema deve enviar notificações para lembrar o usuário de revisar conteúdos passados.

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE04 |
| **Título** | Notificações de Revisão de Conteúdos |
| **Metas/Objetivos** | Garantir que o aluno seja lembrado de revisar conteúdos estudados anteriormente, promovendo aprendizado contínuo. |
| **Contexto** | O aluno acessa a plataforma periodicamente e deseja receber lembretes automáticos sobre conteúdos já concluídos. |
| **Ator(es)** | - Aluno<br>- Sistema de notificações da plataforma |
| **Recursos** | - Banco de dados de conteúdos concluídos<br>- Mecanismo de envio de notificações ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ) |
| **Exceções** | - Falha no envio da notificação.<br>- Conteúdo revisado recentemente não gera novo lembrete. |
| **Restrições** | - As notificações devem respeitar as preferências de comunicação do aluno. |
| **Episódios** | 1. O sistema identifica conteúdos já estudados.<br>2. Envia lembrete ao aluno para revisar o conteúdo. |

---

### Cenário 05: Configuração da Forma de Notificação
**Requisito Associado:** RF19 - O sistema deve pedir ao usuário a melhor forma de caminho de notificação.

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE05 |
| **Título** | Escolha da Forma de Notificação |
| **Metas/Objetivos** | Permitir que o aluno defina sua preferência de comunicação para receber notificações ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ). |
| **Contexto** | O aluno acessa a plataforma e quer receber alertas e lembretes da forma que considera mais conveniente. |
| **Ator(es)** | - Aluno<br>- Sistema de configuração de notificações |
| **Recursos** | - Painel de preferências do usuário<br>- Mecanismo de envio de notificações configurável |
| **Exceções** | - Usuário não escolhe forma de notificação, permanecendo a padrão.<br>- Opção selecionada não está disponível no momento do envio. |
| **Restrições** | - Sistema deve garantir que as notificações sejam enviadas conforme a escolha do aluno.<br>- Preferência deve ser atualizável a qualquer momento. |
| **Episódios** | 1. O aluno acessa a seção “Preferências de Notificação”.<br>2. Escolhe o canal preferido ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ).<br>3. Sistema salva a configuração e envia notificações conforme a escolha. |

---

### Cenário 06: Notificação de Prazo de Entrega
**Requisito Associado:** RF20 - O sistema deve enviar uma notificação quando está chegando perto da data de entrega de uma atividade.

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE06 |
| **Título** | Alertas de Prazos de Entrega |
| **Metas/Objetivos** | Informar o aluno sobre atividades com prazo próximo, evitando atrasos na entrega. |
| **Contexto** | Um aluno possui atividades agendadas na plataforma e deseja receber alertas próximos ao prazo final. |
| **Ator(es)** | - Aluno<br>- Sistema de notificações da plataforma |
| **Recursos** | - Banco de dados de atividades e prazos<br>- Sistema de envio de notificações ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ) |
| **Exceções** | - Falha no envio do alerta.<br>- Prazo da atividade é alterado após envio da notificação. |
| **Restrições** | - Notificações devem ser enviadas com antecedência suficiente para ação do aluno.<br>- Devem respeitar as preferências de comunicação do usuário. |
| **Episódios** | 1. O sistema verifica atividades próximas do prazo.<br>2. Gera alerta de prazo para cada atividade.<br>3. Envia notificação ao aluno. |

---


## Referências

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 05/10/2025 | Criação do documento dos Cados de Uso | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [Felipe Guimaraes](https://github.com/felipegf1) |
