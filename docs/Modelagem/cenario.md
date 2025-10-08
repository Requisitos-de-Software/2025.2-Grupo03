# Cenário

## Introdução
Este documento mostra os cenários de uso, ou seja, situações que representam como o usuário utilizaria o sistema. Cada cenário descreve uma ação do usuário e mostra como as funções que ainda não existem no SAE seriam usadas no dia a dia. Esses cenários foram criados para entender melhor os **requisitos funcionais não-implementados** e como eles vão interagir com o usuário quando forem adicionados ao sistema.

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da construção dos Cenários, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) |                                       |
| [Arthur Henrique](https://github.com/arthurhvieira1) |                                       |
| [Felipe Guimaraes](https://github.com/felipegf1) |   Criou os cenários 01, 02 e 03, referente aos requisitos [RF08](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| [João Felipe](https://github.com/MrBolt2005) |                                       |
| [João Sapiência](https://github.com/JoaoSapiencia) |                                       |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  Criou os cenários 04, 05 e 06, que são referentes, respectivamente, aos requisitos [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF20](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais).                                 |
| [Vilmar José](https://github.com/VilmarFagundes) |                                       |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Metodologia
A metodologia usada nesta documentação segue os conceitos e a estrutura mostrados nos slides da aula “Requisitos – Aula 10”, de Milene Serrano e Maurício Serrano, disponíveis [clicando aqui](../arquivos/Cenarios_Aula10.pdf).  
Cada cenário foi criado com base na identificação dos **requisitos funcionais que ainda não foram implementados** no sistema.  
Foram aplicadas abstrações para tornar a documentação clara, organizada e de fácil compreensão, conforme o modelo apresentado no material de apoio, ilustrado na Figura 1.

<div align="center"><strong>Figura1: Abstrações </strong></div>

![Figura 1: Abstração Cenários](../imagens/AbstracaoCenarios.png)

A estrutura adotada para cada cenário seguiu uma **padronização em formato de tabela**, baseando-se nos seguintes elementos:

- **ID:** Identificador único do cenário, usado para facilitar seu rastreamento e manutenção. Segue o padrão “CE”, referente ao cenário, junto ao número do cenário.      *Exemplo:* `CE07`.
- **Título:** Nome do cenário, geralmente relacionado ao objetivo principal ou ao requisito funcional ainda não implementado.
- **Metas/Objetivos:** Explica o propósito do cenário e o que se espera alcançar com a futura implementação da funcionalidade.
- **Contexto:** Define a situação e o ambiente em que o cenário ocorre, estabelecendo as pré-condições para o fluxo de eventos.
- **Ator(es):** Indica as pessoas, sistemas ou entidades que interagem diretamente com a funcionalidade descrita.
- **Recursos:** Lista as ferramentas ou componentes do sistema necessários para executar o cenário.
- **Exceções:** Aponta situações inesperadas ou problemas que podem interromper o fluxo normal do cenário.
- **Restrições:** Mostra as limitações, regras de negócio ou condições que devem ser respeitadas durante a execução.
- **Episódios:** Descreve, passo a passo, o fluxo principal de ações e decisões realizadas pelos atores no cenário.

---

A **padronização da tabela** se baseou nesses elementos apresentados acima e pode ser observada na **Tabela 2**.

<div align="center"><strong>Tabela 2: Padronização dos Cenários</strong></div>

| Elemento        | Descrição |
|-----------------|-----------|
| ID              | CEN° |
| Título          | Nome do cenário, geralmente relacionado ao objetivo principal ou ao requisito funcional ainda não implementado. |
| Metas/Objetivos | Explica o propósito do cenário e o que se espera alcançar com a futura implementação da funcionalidade. |
| Contexto        | Define a situação e o ambiente em que o cenário ocorre, estabelecendo as pré-condições para o fluxo de eventos.
 |
| Ator(es)        | Indica as pessoas, sistemas ou entidades que interagem diretamente com a funcionalidade descrita.
 |
| Recursos        | Lista as ferramentas ou componentes do sistema necessários para executar o cenário. |
| Exceções        | Aponta situações inesperadas ou problemas que podem interromper o fluxo normal do cenário. |
| Restrições      | Mostra as limitações, regras de negócio ou condições que devem ser respeitadas durante a execução. |
| Episódios       | Descreve, passo a passo, o fluxo principal de ações e decisões realizadas pelos atores no cenário. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Cenários

### Cenário 01: Exibição do Progresso Geral na Disciplina
**Requisito Associado:** [RF08](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - A interface deve exibir um progresso em porcentagem do andamento da disciplina.

<div align="center"><strong>Tabela 3: Cenário 01</strong></div>

| **Elemento**        | **Descrição**  |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **ID**              | CE01    |
| **Título**          | Progresso Geral da Disciplina  |
| **Metas/Objetivos** | Permitir que o aluno visualize o quanto já avançou na disciplina, incentivando o acompanhamento contínuo e a conclusão dos conteúdos.                                                                                          |
| **Contexto**        | O aluno acessa a plataforma e deseja entender seu progresso global dentro de uma disciplina específica.                                                                                                                        |
| **Ator(es)**        | - Aluno<br>- Sistema de controle de progresso                                                                                                                                                                                  |
| **Recursos**        | - Banco de dados de atividades concluídas e pendentes<br>- Módulo de cálculo de progresso<br>- Interface de exibição gráfica (ex: barra de progresso ou percentual numérico)                                                   |
| **Exceções**        | - Falha na atualização automática do progresso após novas atividades concluídas.<br>- Dados inconsistentes no banco de atividades.                                                                                             |
| **Restrições**      | - O progresso deve ser atualizado em tempo real após cada conclusão de atividade.<br>- A interface deve ser clara e acessível em todos os dispositivos.                                                                        |
| **Episódios**       | 1. O aluno acessa a página da disciplina.<br>2. O sistema consulta os dados de atividades concluídas e pendentes.<br>3. Calcula o percentual de progresso.<br>4. Exibe o progresso em formato visual (porcentagem e/ou barra). |

### Cenário 02: Exibição da Porcentagem de Acertos por Conteúdo
**Requisito Associado:** [RF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - A interface deve exibir como está a porcentagem de acertos das atividades de cada conteúdo.

<div align="center"><strong>Tabela 4: Cenário 02</strong></div>

| **Elemento**        | **Descrição**   |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **ID**              | CE02    |
| **Título**          | Desempenho de Acertos por Conteúdo  |
| **Metas/Objetivos** | Fornecer ao aluno uma visão detalhada de seu desempenho em cada conteúdo, destacando pontos fortes e incentivando o aprimoramento.                                             |
| **Contexto**        | O aluno deseja acompanhar sua taxa de acertos em cada conteúdo para entender onde está indo bem e onde precisa melhorar.                                                       |
| **Ator(es)**        | - Aluno<br>- Sistema de monitoramento de desempenho                                                                   |
| **Recursos**        | - Banco de dados de resultados das atividades<br>- Módulo de cálculo de desempenho<br>- Interface de exibição de desempenho (gráficos ou indicadores numéricos)              |
| **Exceções**        | - Dados incompletos de atividades podem afetar o cálculo da porcentagem.<br>- Atividades ainda não corrigidas não entram no cálculo.                                           |
| **Restrições**      | - A porcentagem deve ser atualizada automaticamente após a correção de cada atividade.<br>- Deve ser exibida de forma compreensível e visualmente intuitiva.                   |
| **Episódios**       | 1. O aluno acessa o banco de questões.<br>2. O sistema calcula o percentual de acertos em cada conteúdo.<br>3. Exibe a porcentagem de forma gráfica ou numérica. |

### Cenário 03: Exibição da Porcentagem de Erros por Conteúdo
**Requisito Associado:** [RF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - A interface deve exibir como está a porcentagem de erros das atividades de cada conteúdo.

<div align="center"><strong>Tabela 5: Cenário 03</strong></div>

| **Elemento**        | **Descrição**  |
| ------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **ID**              | CE03 |
| **Título**          | Desempenho de Erros por Conteúdo  |
| **Metas/Objetivos** | Permitir que o aluno identifique conteúdos com maiores índices de erro, auxiliando no direcionamento dos estudos e revisões.   |
| **Contexto**        | O aluno quer verificar em quais conteúdos tem mais dificuldades, observando a taxa de erros.     |
| **Ator(es)**        | - Aluno<br>- Sistema de monitoramento de desempenho   |
| **Recursos**        | - Banco de dados de atividades e resultados<br>- Módulo de cálculo de desempenho<br>- Interface de exibição de desempenho (gráficos ou indicadores numéricos)   |
| **Exceções**        | - Falha no registro correto dos resultados das atividades.<br>- Atividades ainda não finalizadas não devem ser contabilizadas. |
| **Restrições**      | - O cálculo deve considerar apenas atividades concluídas.<br>- A exibição deve ser clara e comparável entre diferentes conteúdos. |
| **Episódios**       | 1. O aluno acessa o banco de questões.<br>2. O sistema identifica a quantidade de erros em cada atividade.<br>3. Calcula a porcentagem de erros por conteúdo.<br>4. Exibe a porcentagem de forma gráfica ou numérica. |


### Cenário 04: Lembretes de Revisão de Conteúdos
**Requisito Associado:** [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve enviar notificações para lembrar o usuário de revisar conteúdos passados.

<div align="center"><strong>Tabela 6: Cenário 04</strong></div>

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

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

### Cenário 05: Configuração da Forma de Notificação
**Requisito Associado:** [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve pedir ao usuário a melhor forma de caminho de notificação.

<div align="center"><strong>Tabela 7: Cenário 05</strong></div>

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE05 |
| **Título** | Escolha da Forma de Notificação |
| **Metas/Objetivos** | Permitir que o usuário defina sua preferência de comunicação para receber notificações ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ). |
| **Contexto** | O usuário acessa a plataforma e quer receber alertas e lembretes da forma que considera mais conveniente. |
| **Ator(es)** | - Aluno<br> - Docente<br> - Monitor<br> - Coordenador<br> - Administrador<br> - Sistema de configuração de notificações |
| **Recursos** | - Painel de preferências do usuário<br>- Mecanismo de envio de notificações configurável |
| **Exceções** | - Usuário não escolhe forma de notificação, permanecendo a padrão.<br>- Opção selecionada não está disponível no momento do envio. |
| **Restrições** | - Sistema deve garantir que as notificações sejam enviadas conforme a escolha do aluno.<br>- Preferência deve ser atualizável a qualquer momento. |
| **Episódios** | 1. O usuário acessa a seção “Preferências de Notificação”.<br>2. Escolhe o canal preferido ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ).<br>3. Sistema salva a configuração e envia notificações conforme a escolha. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

### Cenário 06: Notificação de Prazo de Entrega
**Requisito Associado:** [RF20](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve enviar uma notificação quando está chegando perto da data de entrega de uma atividade.

<div align="center"><strong>Tabela 8: Cenário 06</strong></div>

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

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---


## Referências

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 05/10/2025 | Criação do documento de cenários | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.1    | 07/10/2025 | Criação dos cenarios CE01 , CE02 e CE03 | [Felipe Guimaraes](https://github.com/felipegf1) |  [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.2    | 08/10/2025 | Atualização de informações no documento | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [Felipe Guimaraes](https://github.com/felipegf1) |
