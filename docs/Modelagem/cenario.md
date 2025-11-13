# Cenário

## Introdução
Este documento apresenta os cenários de uso do sistema, ou seja, situações práticas que ilustram como os indivíduos interagem com o **SAE (Sistema de Apoio Educacional)** em seu uso cotidiano.

Cada cenário descreve uma sequência de ações e reações entre o sistema e o participante, demonstrando o funcionamento esperado das funcionalidades ainda não implementadas.

O objetivo é facilitar a compreensão dos requisitos funcionais pendentes, mostrando de forma contextual como eles contribuirão para a experiência e as operações dentro do sistema.

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da construção dos Cenários, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) |  Criou os cenários [07 - Análise Cognitiva e Apoio à Aprendizagem](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/cenario/#cenario-07-analise-cognitiva-e-apoio-a-aprendizagem), [08 - Identificação de Conhecimento sobre o Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/cenario/#cenario-08-identificacao-de-conhecimento-sobre-o-conteudo) e [09 - Avaliação de Comportamento Escola](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/cenario/#cenario-09-avaliacao-de-comportamento-escolar), referente aos requisitos [RF49](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF50](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF51](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| [Arthur Henrique](https://github.com/arthurhvieira1) | Criação dos cenários 12 e 13, referentes, respectivamente aos requisitos [RF16](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF21](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF30](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)|
| [Felipe Guimaraes](https://github.com/felipegf1) |   Criou os cenários 01, 02 e 03, referente aos requisitos [RF08](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| [João Felipe](https://github.com/MrBolt2005) | Criou os cenários 14, 15 e 16, referente aos requisitos [RF24](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF14](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF42](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)                                      |
| [João Sapiência](https://github.com/JoaoSapiencia) |  Criou os cenários 17, 18 e 19, referente aos requisitos [RF32](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF34](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF40](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)                                     |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Cenário e dos cenários [04 - Lembretes de Revisão de Conteúdos](#cenario-04-lembretes-de-revisao-de-conteudos), [05 - Configuração da Forma de Notificação](#cenario-05-configuracao-da-forma-de-notificacao) e [06 - Notificação de Prazo de Entrega](#cenario-06-notificacao-de-prazo-de-entrega), que são referentes, respectivamente, aos requisitos [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF18](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais). |
| [Vilmar José](https://github.com/VilmarFagundes) | Criação dos cenários [10 - Visualização da Média Geral da Turma por Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/cenario/#cenario-10-visualizacao-da-media-geral-da-turma-por-atividade) e [11 - Personalização da Frequência de Alertas de Atividades Atrasadas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/cenario/#cenario-11-personalizacao-da-frequencia-de-alertas-de-atividades-atrasadas), referentes, respectivamente aos requisitos [RF11](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF13](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |

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
| Contexto        | Define a situação e o ambiente em que o cenário ocorre, estabelecendo as pré-condições para o fluxo de eventos. |
| Ator(es)        | Indica as pessoas, sistemas ou entidades que interagem diretamente com a funcionalidade descrita. |
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

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

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

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

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

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

### Cenário 04: Lembretes de Revisão de Conteúdos
**Requisito Associado:** [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve enviar notificações para lembrar o aluno de revisar conteúdos passados.

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
**Requisito Associado:** [RF18](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve pedir ao indivíduo a melhor forma de caminho de notificação.

<div align="center"><strong>Tabela 7: Cenário 05</strong></div>

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE05 |
| **Título** | Escolha da Forma de Notificação |
| **Metas/Objetivos** | Permitir que o indivíduo defina sua preferência de comunicação para receber notificações ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ). |
| **Contexto** | O participante acessa a plataforma e quer receber alertas e lembretes da forma que considera mais conveniente. |
| **Ator(es)** | - Aluno<br> - Docente<br> - Monitor<br> - Coordenador<br> - Administrador<br> - Sistema de configuração de notificações |
| **Recursos** | - Painel de preferências do pessoais<br>- Mecanismo de envio de notificações configurável |
| **Exceções** | - Nenhuma forma de notificação é escolhida, mantendo-se a opção padrão.<br>- Opção selecionada não está disponível no momento do envio. |
| **Restrições** | - Sistema deve garantir que as notificações sejam enviadas conforme a escolha do aluno.<br>- Preferência deve ser atualizável a qualquer momento. |
| **Episódios** | 1. O participante acessa a seção “Preferências de Notificação”.<br>2. Escolhe o canal preferido ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ).<br>3. Sistema salva a configuração e envia notificações conforme a escolha. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

### Cenário 06: Notificação de Prazo de Entrega
**Requisito Associado:** [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve enviar uma notificação quando está chegando perto da data de entrega de uma atividade.

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
| **Restrições** | - Notificações devem ser enviadas com antecedência suficiente para ação do aluno.<br>- Devem respeitar as preferências de comunicação do aluno. |
| **Episódios** | 1. O sistema verifica atividades próximas do prazo.<br>2. Gera alerta de prazo para cada atividade.<br>3. Envia notificação ao aluno. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

### Cenário 07: Análise Cognitiva e Apoio à Aprendizagem  
**Requisito Associado:** [RF49](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve analisar documentos escolares(atividades e provas) para identificar dificuldades cognitivas e sugerir estratégias de reforço ao aluno.

<div align="center"><strong> Tabela 9 - Cenário 07 </strong></div>

| Elemento       | Descrição |
|----------------|-----------|
| **ID** | CE07 |
| **Título**     | Análise Cognitiva e Apoio à Aprendizagem |
| **Metas/Objetivos** | Avaliar a situação cognitiva de cada aluno e oferecer suporte personalizado para melhorar o processo de aprendizagem. |
| **Contexto**    | O sistema educacional utiliza algoritmos de inferência cognitiva para analisar documentos escolares (provas e atividades) e identificar dificuldades específicas de cada aluno. Com base nessa análise, o assistente virtual sugere estratégias de reforço ao aluno. |
| **Ator(es)**    | - Aluno<br>- Professor<br>- Assistente Virtual |
| **Recursos**    | - Módulo de análise documental<br>- Algoritmos de inferência cognitiva<br>- Banco de dados de desempenho escolar |
| **Exceções**    | - Documentos insuficientes para análise<br>- Dados inconsistentes ou corrompidos |
| **Restrições**  | A análise deve respeitar a privacidade dos dados dos alunos e seguir diretrizes pedagógicas. |
| **Episódios**   | 1. O sistema acessa os documentos escolares do aluno.<br>2. Identifica padrões de dificuldade.<br>3. Sugere conteúdo adaptados para suas dificuldades.<br>4. Monitora a evolução do aluno ao longo do tempo. |
<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

### Cenário 08: Identificação de Conhecimento sobre o Conteúdo  
**Requisito Associado:** [RF50](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve apresentar ao professor qual aluno sabe sobre o conteúdo, com base em provas e atividades.

<div align="center"><strong> Tabela 10 - Cenário 08 </strong></div>

| Elemento       | Descrição |
|----------------|-----------|
| **ID** | CE08 |
| **Título**     | Identificação de Conhecimento sobre o Conteúdo |
| **Metas/Objetivos** | Permitir ao professor visualizar o nível de domínio de conteúdo de cada aluno com base em provas e questões, utilizando Lógica Fuzzy para gerar uma análise graduada e confiável. |
| **Contexto**    | Após a realização de atividades avaliativas, o sistema processa os resultados e apresenta ao professor uma visão detalhada do desempenho dos alunos por conteúdo. A análise é feita por meio de Lógica Fuzzy, permitindo identificar quais alunos dominam ou têm dificuldades em cada tema. |
| **Ator(es)**    | - Professor<br>- Sistema de Avaliação Inteligente |
| **Recursos**    | - Banco de questões por conteúdo<br>- Sistema de correção automática<br>- Módulo de inferência com Lógica Fuzzy<br>- Painel de desempenho por aluno |
| **Exceções**    | - Provas não corrigidas ou com erros<br>- Dados insuficientes para inferência confiável |
| **Restrições**  | A visualização deve ser clara, pedagógica e respeitar a privacidade dos alunos. |
| **Episódios**   | 1. Os alunos realizam provas e atividades.<br>2. O sistema aplica Lógica Fuzzy para avaliar o domínio por conteúdo.<br>3. O professor acessa o painel de desempenho dos alunos.<br>4. O sistema apresenta níveis de conhecimento e destaca alunos com dificuldades. |
<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

### Cenário 09: Avaliação de Comportamento Escolar  
**Requisito Associado:** [RF51](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve informar ao professor quais alunos mantêm comportamento adequado segundo critérios pedagógicos.

<div align="center"><strong> Tabela 11 - Cenário 09 </strong></div>

| Elemento       | Descrição |
|----------------|-----------|
| **ID** | CE09 |
| **Título**     | Avaliação de Comportamento Escolar |
| **Metas/Objetivos** | Apresentar ao professor quais alunos mantêm comportamento adequado com base em critérios como presença nas aulas, participação em monitorias, realização de atividades e estudo dos conteúdos sugeridos. |
| **Contexto**    | O sistema educacional monitora continuamente o comportamento dos alunos por meio de registros de presença, entregas de atividades, participação em monitorias e acesso aos conteúdos recomendados. O assistente virtual analisa esses dados e gera relatórios que ajudam o professor a identificar alunos engajados e aqueles que precisam de acompanhamento. |
| **Ator(es)**    | - Aluno<br>- Professor<br>- Assistente Virtual |
| **Recursos**    | - Registro de frequência<br>- Plataforma de entrega de atividades<br>- Sistema de monitoria<br>- Módulo de rastreamento de estudo de conteúdos sugeridos |
| **Exceções**    | - Dados incompletos ou não sincronizados<br>- Aluno ausente em todas as atividades avaliadas |
| **Restrições**  | O sistema deve garantir a integridade e atualização dos dados, respeitando normas de privacidade e acessibilidade. |
| **Episódios**   | 1. O sistema registra a presença do aluno nas aulas.<br>2. Monitora a participação em sessões de monitoria.<br>3. Verifica a entrega de atividades e prazos.<br>4. Acompanha o acesso e estudo dos conteúdos sugeridos.<br>5. O assistente virtual analisa os dados e gera um relatório de comportamento.<br>6. O professor acessa o relatório e identifica os alunos com comportamento adequado. |
<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---
### Cenário 10: Visualização da Média Geral da Turma por Atividade
**Requisito Associado:** [RF11](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - A interface deve exibir a média geral da turma em cada atividade


<div align="center"><strong>Tabela 12: Cenário 10</strong></div>

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE10 |
| **Título** | Visualização da Média Geral da Turma por Atividade |
| **Metas/Objetivos** | - **Para o professor:** Analisar o desempenho agregado da turma em cada avaliação, facilitando a identificação de dificuldades de aprendizagem<br> - **Para o aluno:** Permitir que compare seu próprio desempenho com a média geral da turma, servindo como um parâmetro para seus estudos. |
| **Contexto** | Um participante (professor ou aluno) está autenticado no sistema de gestão de aprendizagem e acessou a área de atividades de uma disciplina. Ele escolhe uma das atividades e verifica se as notas já foram lançadas e a média calculada. |
| **Ator(es)** | - Professor<br>- Aluno |
| **Recursos** | - Banco de dados de atividades<br> - Bance de dados de resultados de atividades |
| **Exceções** | - Cálculo Indisponível: A média não pode ser exibida se nenhuma nota foi lançada para a atividade.<br> - Erro de Carregamento: A página de notas falha ao carregar devido a um problema de conexão ou erro no servidor. |
| **Restrições** | - A média deve ser calculada considerando apenas os alunos que receberam uma nota.<br> - Os alunos podem ver a média geral, mas não têm acesso às notas individuais de seus colegas. |
| **Episódios** | 	1. O participante (professor ou aluno) acessa a plataforma e navega até a disciplina desejada. <br> 2. Sseleciona a opção "Atividades" no menu da disciplina.<br> 3. O sistema exibe uma lista com todas as atividades avaliativas.<br> 4. Para cada atividade, o sistema exibe a nota individual do aluno (se for o aluno logado) e, em uma coluna separada, a "Média da Turma".<br> 5. O participante utiliza essa informação para fins de análise de desempenho (seja da turma ou pessoal). |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

---

### Cenário 11: Personalização da Frequência de Alertas de Atividades Atrasadas
**Requisito Associado:** [RF13](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O aluno deve escolher o tempo em que deseja receber alertas sobre atividades atrasadas

<div align="center"><strong>Tabela 13: Cenário 11</strong></div>

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE11 |
| **Título** | Personalização da Frequência de Alertas de Atividades Atrasadas |
| **Metas/Objetivos** | Oferecer ao aluno a flexibilidade de configurar com que antecedência deseja ser notificado sobre atividades pendentes, a fim de melhorar sua gestão de tempo e reduzir o número de entregas em atraso. |
| **Contexto** | O aluno está logado em seu perfil no sistema e acessa a área de configurações de sua conta para ajustar suas preferências de notificação. |
| **Ator(es)** | Aluno |
| **Recursos** | - Banco de dados de atividades e prazos<br>- Sistema de envio de notificações ( notificações push, mensagens pelo WhatsApp, e-mails e alertas na interface do sistema ou no aplicativo ) |
| **Exceções** |  Falha ao Salvar: O sistema apresenta um erro e não consegue salvar as novas preferências de notificação devido a uma instabilidade na rede |
| **Restrições** | - O aluno deve ter um meio de contato válido cadastrado (e-mail ou permissão para notificação push) para receber os alertas.<br> - As opções de tempo para os alertas são predefinidas pelo sistema (ex: "1 dia antes", "2 dias antes", "No dia do vencimento").<br> - A configuração é aplicada individualmente e não afeta as preferências de outros alunos. |
| **Episódios** | 1. O aluno acessa sua conta no sistema.<br> 2. Ele seleciona a opção "Configurações".<br> 3. Na página de configurações, ele navega até a seção "Notificações".<br> 4. O sistema exibe uma lista de tipos de alerta que podem ser configurados. O aluno localiza a opção "Alertas sobre atividades atrasadas".<br> 5. Ao lado desta opção, há um menu suspenso (dropdown) com os intervalos de tempo disponíveis.<br> 6. O aluno clica no menu e seleciona a opção desejada (por exemplo, "1 dia após o vencimento").<br> 7. Após a seleção, o aluno clica no botão "Salvar" ou "Atualizar Preferências".<br> 8. O sistema exibe uma mensagem de confirmação, como "Suas preferências de notificação foram salvas com sucesso". |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

### Cenário 12: Priorização de Conteúdo por Dificuldade
**Requisito Associado:** [RF16](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)  - O sistema deve ter um índice de conteúdos ordenado pela porcentagem de erros em cada conteúdo

<div align="center"><strong>Tabela 14: Cenário 12</strong></div>

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE12 |
| **Título** | Priorização de Conteúdo por Dificuldade da Turma |
| **Metas/Objetivos** | - **Para o aluno:** Ajudar a identificar e focar nos conteúdos onde a turma apresenta a maior porcentagem de erros, otimizando a preparação para avaliações. |
| **Contexto** | Um aluno está se preparando para uma prova e quer revisar os tópicos de forma mais eficiente. Ele decide acessar o índice de conteúdos para ver quais assuntos a turma, em geral, mais errou e que, portanto, merecem mais atenção. |
| **Ator(es)** | - Aluno |
| **Recursos** | - Banco de dados com resultados de atividades<br>- Módulo de tagueamento de questões por conteúdo<br>- Módulo de cálculo de percentuais de erro |
| **Exceções** | - Dados Insuficientes: O índice não pode ser gerado se poucas atividades foram respondidas pela turma.<br>- Erro de Cálculo: O sistema falha ao processar as porcentagens de erro. |
| **Restrições** | - O índice deve ser baseado em dados anonimizados da turma, sem expor o desempenho individual de outros alunos.<br>- A lista deve ser atualizada periodicamente para refletir os dados mais recentes. |
| **Episódios** | 1. O aluno acessa a plataforma e navega até a disciplina desejada.<br>2. O aluno seleciona a opção "Guia de Estudos" ou "Conteúdos".<br>3. O sistema calcula a porcentagem de erros da turma para cada tópico com base nas atividades já realizadas.<br>4. O sistema exibe uma lista com todos os conteúdos, ordenada do tópico com maior percentual de erro para o menor.<br>5. O aluno utiliza essa informação para priorizar seus estudos. |

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

### Cenário 13: Personalização de Lembretes de Atividades
**Requisito Associado:** [RF21](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)  - O aluno escolhe quando ele recebe a notificação de proximidade da data de entrega de atividade

<div align="center"><strong>Tabela 15: Cenário 13</strong></div>

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE13 |
| **Título** | Personalização de Lembretes de Atividades |
| **Metas/Objetivos** | - **Para o aluno:** Dar controle sobre como e quando ele é notificado sobre os prazos, permitindo que o sistema se adapte ao seu método pessoal de organização. |
| **Contexto** | Um aluno prefere receber um único lembrete 3 dias antes do prazo final de uma atividade, em vez do padrão de 24 horas. Ele acessa as configurações do seu perfil para ajustar essa preferência de notificação. |
| **Ator(es)** | - Aluno |
| **Recursos** | - Painel de configurações do aluno<br>- Banco de dados para armazenar preferências de notificação<br>- Serviço agendador de notificações |
| **Exceções** | - Erro ao Salvar: O sistema não consegue salvar a preferência por uma falha no banco de dados.<br>- Serviço Indisponível: O serviço de notificações está temporariamente fora do ar e não envia o lembrete agendado. |
| **Restrições** | - A configuração de notificação é individual e não deve afetar outros alunos.<br>- As opções de tempo para o lembrete devem ser claras e pré-definidas (ex: 1 dia antes, 3 dias antes, etc.). |
| **Episódios** | 1. O aluno acessa a área de "Configurações" ou "Preferências" do seu perfil.<br>2. Ele navega até a seção "Notificações".<br>3. Na opção "Lembrete de entrega de atividade", ele altera a seleção padrão para a desejada (ex: "3 dias antes").<br>4. O sistema confirma que a alteração foi salva com sucesso.<br>5. O serviço de notificação passa a utilizar essa nova configuração para os futuros lembretes deste aluno. |

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

### Cenário 14: Cálculo do Desempenho do Aluno
**Requisito Associado:** [RF24](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - Deve mostrar como o desempenho está sendo calculado.

<div align="center"><strong>Tabela 16: Cenário 14</strong></div>

| Elemento        | Descrição                                                                 |
|------------------|---------------------------------------------------------------------------|
| **ID**          | CE14                                                                      |
| **Título**      | Cálculo do Desempenho do Aluno                                        |
| **Metas/Objetivos** | Permitir que o indivíduo visualize não apenas o nível de desempenho alcançado em determinada disciplina, mas também o modo como esse valor foi obtido. Essa transparência facilita a compreensão sobre os pontos fortes e fracos específicos, evidenciando quais fatores têm maior influência no desempenho geral. |
| **Contexto**    | O indivíduo (aluno ou professor) acessa a plataforma, vê as estatísticas de desempenho – acadêmico – de aluno e deseja entender por quê em particular elas apresentam os valores que ele acaba de encontrar. |
| **Ator(es)**    | - Aluno<br>- Professor<br>- Sistema de controle de desempenho do aluno<br>- Módulo de configurações pessoais<br>- Sistema de notificações                                                                  |
| **Recursos**    | - Envio de notificações selecionáveis/configuráveis sobre atualizações significantes sobre métricas de computação de desempenho particulares que o indivíduo for desejar;<br>- Interação com os sistemas de análise/inferência cognitiva e de cálculo de desempenho, além da descrição dos métodos que chegam a seus resultados;<br>- Interface(s) de exibição gráfica, com descrições textuais adicionadas onde vier a ser necessário;<br>- Painel de preferências;<br>- Acesso aos bancos de dados de atividades, resultados e desempenho acadêmico das disciplinas;<br>- Comparar o/um desempenho atual com desempenhos anteriores (histórico);<br>- Descrição de inferências com lógica *fuzzy*;<br>- Painéis de desempenho por aluno e por turma. |
| **Exceções**    | - Dados insuficientes (incompletos), inconsistentes e/ou inconclusivos para análise(s);<br>Dados não sincronizados;<br>- Falha na atualização automática de informações;<br>- Resultados de atividade(s) não registrados ou com erro(s);<br>- Falha no envio de notificação;<br>- Ausência de configuração de notificações;<br>- Cálculo indisponível ou falho (exceção genérica);<br>- Erro de carregamento, conexão ou disponibilidade. |
| **Restrições**  | - As métricas de computação devem ser atualizadas em tempo real automaticamente após cada conclusão ou correção de atividade, entrega, avaliação, questionário etc.;<br>- As eventuais interfaces exibidas devem ser claras, acessíveis, concisas e intuitivas em todos os dispositivos (plataformas);<br>- A exibição deve ser clara e comparável entre diferentes conteúdos;<br>- O processamento e a exibição de dados devem respeitar a privacidade, garantir integridade e segurança das informações e seguir critérios pedagógicos adequados;<br>- Os alunos podem ver as métricas gerais para as suas turmas e as suas próprias métricas individuais, mas não as de outros alunos;<br>- Os professores podem ver tanto as métricas gerais para as turmas quanto todas as métricas individuais dos seus (próprios) alunos matriculados;<br>- As configurações que forem se aplicar pelos indivíduos devem ser aplicadas individualmente para cada um destes;<br>- Atividades só podem ser consideradas nos cálculos se e quando corrigidas. |
| **Episódios**   | 1. O indivíduo faz *login* na plataforma se necessário.<br>2. Acessa a página principal ou o painel da plataforma.<br>3. O aluno seleciona uma turma (registrada na plataforma, é claro) na qual ele está matriculado, ou o professor, uma que ele leciona.<br>4. Localiza a seção de informações de desempenho da turma.<br> 5. O sistema de controle de desempenho analisa as métricas de derivação de desempenho tanto individuais como gerais coletivas, calcula essas informações de desempenho – por exemplo, valores numéricos, informações em texto, relatórios, resumos… –.<br>6. O sistema exibe os resultados obtidos, juntamente com as fórmulas e métodos utilizados no cálculo, na página da turma ou em uma subpágina específica.<br>7. Adicionalmente, se for configurado para tal pelo aluno, o sistema também envia as notificações necessárias, seja em *push* como também na própria interface na *web* e/ou no aplicativo, relevantes às atualizações de métricas de derivação de desempenho desejadas. |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

### Cenário 15: Seleção de Disciplinas de Maior Facilidade
**Requisito Associado:** [RF14](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O aluno pode marcar os tópicos da disciplina nos quais sente mais facilidade.

<div align="center"><strong>Tabela 17: Cenário 15</strong></div>

| **Elemento** | **Descrição** |
|---------------|---------------|
| **ID** | CE15 |
| **Título** | Seleção de Disciplinas de Maior Facilidade |
| **Metas/Objetivos** | Permitir que o aluno identifique e marque as disciplinas ou tópicos em que sente maior facilidade, ajudando o sistema a personalizar o acompanhamento e o feedback. |
| **Contexto** | O aluno acessa a plataforma e seleciona, em seu painel pessoal, as disciplinas ou tópicos nos quais tem maior domínio. O sistema pode usar essa informação para ajustar sugestões e análises de desempenho. |
| **Ator(es)** | - Aluno<br>- Sistema de controle de desempenho do aluno<br>- Módulo de configurações pessoais<br> - Sistema de notificações |
| **Recursos** | - Painel de preferências e seleção de tópicos;<br>- Histórico e desempenho acadêmico do aluno;<br>- Sistema de análise cognitiva e inferência de desempenho;<br>- Interface gráfica de seleção com descrições explicativas;<br>- Banco de dados de configuração individual. |
| **Exceções** | - Dados não sincronizados;<br>- Falha ao salvar preferências;<br>- Erro de carregamento ou conexão;<br>- Falha no envio de notificações;<br>- Erro de carregamento, conexão ou disponibilidade. |
| **Restrições** | - As seleções feitas pelo aluno devem ser armazenadas individualmente e de forma segura;<br>- O sistema deve respeitar a privacidade das informações do aluno;<br>- A interface de seleção deve ser clara, acessível e responsiva. |
| **Episódios** | 1. O aluno faz *login* e acessa o painel de preferências.<br>2. Seleciona as disciplinas ou tópicos em que sente maior facilidade.<br>3. O sistema salva essas preferências.<br>4. O sistema utiliza as informações para ajustar relatórios, notificações e recomendações futuras.<br>5. O aluno pode revisar ou alterar suas seleções a qualquer momento. |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

### Cenário 16: Notificação de Conteúdos Mais Difíceis
**Requisito Associado:** [RF42](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O assistente virtual deve notificar qual conteúdo o aluno está tendo mais dificuldade.

<div align="center"><strong>Tabela 18: Cenário 16</strong></div>

| **Elemento** | **Descrição** |
|---------------|---------------|
| **ID** | CE16 |
| **Título** | Notificação de Conteúdos Mais Difíceis |
| **Metas/Objetivos** | Permitir que o aluno saiba em que conteúdo ele anda tendo mais dificuldade de assimilamento e desempenho. Pode ajudá-lo a focar melhor seus esforços de melhoria de avaliação e desempenho acadêmico-cognitivo e requisições de ajuda para tal onde for mais necessário num dado momento. |
| **Contexto** | O aluno recebe notificações da plataforma, seja em *push* como também na própria interface na *web* e/ou no aplicativo, o avisando sobre os conteúdos acadêmicos entre suas disciplinas correntes em que ele está tendo mais dificuldade e, portanto, deveria se esforçar mais e/ou pedir ajuda nesses próprios conteúdos. |
| **Atores** | - Aluno<br>- Sistema de controle de desempenho<br>- Sistema de notificações |
| **Recursos** | - Notificações ao aluno com base no seu próprio desempenho acadêmico;<br>- Acompanhamento das turmas e matérias do aluno no geral;<br>- Interação e integração com os sistemas de análise/inferência cognitiva e de cálculo de desempenho. |
| **Exceções** | - Dados insuficientes (incompletos), inconsistentes e/ou inconclusivos para análise(s);<br>- Dados não sincronizados;<br> - Falha na atualização automática de informações;<br>- Resultados de atividade(s) não registrados ou com erro(s);<br>- Falha no envio de notificação;<br>- aluno não escolhe forma de notificação;<br>- Análise de desempenho indisponível ou falha (exceção genérica);<br>- Erro de carregamento, conexão ou disponibilidade. |
| **Restrições** | - As notificações devem ser enviadas somente com base em dados atualizados e validados pelo sistema de desempenho;<br>- O envio das notificações deve ocorrer em intervalos regulares configuráveis, evitando sobrecarga de alertas;<br>- O sistema deve respeitar as preferências de privacidade e de frequência de notificações definidas pelo aluno;<br>- Os conteúdos indicados como “mais difíceis” devem ser identificados com base em métricas objetivas de desempenho, como médias de acertos, tempo de resposta ou participação. |
| **Episódios** | 1. O sistema analisa periodicamente as métricas de desempenho do aluno em todas as disciplinas;<br>2. Identifica-se os conteúdos em que há desempenho significativamente abaixo da média pessoal;<br>3. O sistema de controle de desempenho envia esses resultados ao assistente virtual;<br>4. O assistente virtual gera uma mensagem de notificação explicando quais conteúdos requerem mais atenção;<br>5. O aluno é notificado por *push*, *web* e/ou aplicativo, conforme (a) sua configuração;<br>6. O aluno pode acessar a área de detalhes para visualizar estatísticas e recomendações de estudo relacionadas;<br>7. Caso o aluno deseje, ele pode ajustar as preferências de frequência e/ou tipo de notificação. |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

### Cenário 17: Organização de Materiais por Tópicos
**Requisito Associado:** [RF32](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - Os materiais devem estar postados em tópicos de conteúdos separados na disciplina.

<div align="center"><strong>Tabela 19: Cenário 17</strong></div>

| Elemento        | Descrição                                                                 |
|------------------|---------------------------------------------------------------------------|
| **ID**          | CE17                                                                      |
| **Título**      | Materiais Organizacionais por Tópicos                                     |
| **Metas/Objetivos** | Garantir que os materiais de estudo sejam organizados e acessíveis por tópicos, facilitando a navegação e aprendizagem. |
| **Contexto**    | O participante acessa uma disciplina e deseja consultar materiais agrupados por tópicos específicos. |
| **Ator(es)**    | - Aluno<br>- Professor                                                   |
| **Recursos**    | - Banco de dados de materiais<br>- Interface de exibição por tópicos      |
| **Exceções**    | - Falha na categorização dos materiais.<br>- Material inexistente ou corrompido. |
| **Restrições**  | - Cada material deve estar vinculado a apenas um tópico.<br>- Exibição deve ser clara e intuitiva. |
| **Episódios**   | 1. O sistema organiza materiais por tópicos.<br>2. O aluno acessa a disciplina.<br>3. Navega pelos tópicos.<br>4. Visualiza materiais correspondentes. |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

### Cenário 18: Integração com Outros Softwares Educacionais
**Requisito Associado:** [RF34](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O sistema deve integrar outros softwares educacionais (como AVAs).

<div align="center"><strong>Tabela 20: Cenário 18</strong></div>

| Elemento        | Descrição                                                                 |
|------------------|---------------------------------------------------------------------------|
| **ID**          | CE18                                                                      |
| **Título**      | Integração com Softwares Educacionais Externos                            |
| **Metas/Objetivos** | Permitir que conteúdos e atividades de outros softwares sejam acessíveis dentro da plataforma, centralizando o aprendizado. |
| **Contexto**    | O aluno ou professor deseja acessar recursos de AVAs e outras plataformas educacionais diretamente pelo sistema. |
| **Ator(es)**    | - Aluno<br>- Professor<br>- Sistema                                       |
| **Recursos**    | - APIs de integração com softwares externos<br>- Banco de dados do sistema |
| **Exceções**    | - Falha na comunicação com softwares externos.<br>- Dados inconsistentes importados. |
| **Restrições**  | - Apenas plataformas autorizadas devem ser integradas.<br>- Integração segura e em tempo real. |
| **Episódios**   | 1. O sistema conecta com o software externo.<br>2. Importa materiais e atividades.<br>3. O conteúdo integrado é exibido de forma organizada dentro do ambiente principal.<br>4. O aluno ou professor interage com materiais normalmente. |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

### Cenário 19: Customização do Assistente Virtual
**Requisito Associado:** [RF40](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) - O assistente virtual deve ser customizável pelo aluno.

<div align="center"><strong>Tabela 21: Cenário 19</strong></div>

| Elemento        | Descrição                                                                 |
|------------------|---------------------------------------------------------------------------|
| **ID**          | CE19                                                                      |
| **Título**      | Customização do Assistente Virtual                                        |
| **Metas/Objetivos** | Permitir que o aluno personalize a aparência, comportamento e notificações do assistente virtual, aumentando engajamento e satisfação. |
| **Contexto**    | O aluno deseja ajustar o assistente virtual de acordo com suas preferências. |
| **Ator(es)**    | - Aluno                                                                  |
| **Recursos**    | - Interface de configuração do assistente<br>- Banco de dados de preferências do aluno |
| **Exceções**    | - Falha ao salvar configurações.<br>- Alterações não aplicadas corretamente. |
| **Restrições**  | - Configurações aplicam-se apenas ao respectibo aluno.<br>- Devem respeitar limites técnicos da plataforma. |
| **Episódios**   | 1. O aluno acessa a seção de customização.<br>2. Ajusta aparência, comportamento e notificações.<br>3. Salva preferências.<br>4. Assistente virtual se adapta às configurações. |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

### **Cenário 20: Importação de Questões Externas**  
**Requisito Associado:** [RF30](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O banco de questões do sistema deve conter questões de outras origens.

<div align="center"><strong>Tabela 22: Cenário 20</strong></div>

| Elemento | Descrição |
|-----------|------------|
| **ID** | CE20 |
| **Título** | Importação de Questões Externas |
| **Metas/Objetivos** | Permitir que professores e administradores ampliem o banco de questões importando perguntas de outras origens (arquivos, bancos de dados ou plataformas externas). |
| **Contexto** | O professor deseja enriquecer o banco de questões do sistema com conteúdos adicionais, obtidos de fontes externas ou arquivos previamente preparados. |
| **Ator(es)** | - Professor<br>- Administrador do sistema |
| **Recursos** | - Banco de questões interno do sistema<br>- Arquivos externos (CSV, JSON, XML, etc.)<br>- APIs ou integrações com outras plataformas educacionais |
| **Exceções** | - O arquivo enviado está em formato inválido.<br>- Falha de conexão com a origem externa.<br>- Questões duplicadas detectadas durante a importação. |
| **Restrições** | - Somente indivíduos com permissão de edição (professores e administradores) podem importar.<br>- Questões importadas devem seguir o formato padrão do sistema (enunciado, alternativas, gabarito). |
| **Episódios** | 1. O indivíduo acessa o módulo **Banco de Questões**.<br>2. Seleciona a opção **Importar Questões**.<br>3. Escolhe a origem externa (arquivo ou integração).<br>4. O sistema valida o formato e os campos obrigatórios.<br>5. As questões são adicionadas ao banco, com metadados sobre sua origem.<br>6. O sistema exibe uma mensagem confirmando o sucesso da importação. |

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

## Gravação da validação do documento
### Usuário entrevistado
Vale ressaltar que o usuário entrevistado se enquadra no nosso perfil de usuário
<div align="center"><strong>Tabela 6: Usuário Real e Informações da Gravação</strong></div>

| Nome | Data | Hora | Local|
|-------------------------|-----------------|-----------------|------------------|
| João Igor | 09/10/2025 | 13:30 | Faculdade de Ciências e Tecnologias em Engenharia – FCTE/UnB |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

Além disso, a gravação da validação pode ser visualizada em: [https://youtu.be/WbPsxPIdTtg](https://youtu.be/WbPsxPIdTtg)

## Agradecimentos
O Grupo 03 agradece o apoio das ferramentas de Inteligência Artificial Generativa — **ChatGPT, Google Gemini e DeepSeek** — na revisão gramatical e de estilo deste artigo. As tecnologias foram utilizadas para tornar o texto mais claro, objetivo e fácil de ler. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Referências
SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Disponível em: [Requisitos_Aula 10](../arquivos/Cenarios_Aula10.pdf). Acesso em: 10 outubro 2025.

## Histórico de Versões

| Versão | Data       | Descrição                                   | Autor(es)                                                   | Revisor       |
|--------|------------|---------------------------------------------|------------------------------------------------------------|---------------|
| 1.0    | 05/10/2025 | Criação do documento de cenários            | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)       | [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.1    | 07/10/2025 | Criação dos cenários CE01, CE02 e CE03      | [Felipe Guimaraes](https://github.com/felipegf1)           | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.2    | 08/10/2025 | Atualização de informações no documento     | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)       | [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.3    | 08/10/2025 | Criação dos cenários CE07, CE08 e CE09      | [Arthur Guilherme](https://github.com/ArthurGuilher62)     | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.4    | 08/10/2025 | Criação dos cenários CE10 e CE11            | [Vilmar Fagundes](https://github.com/VilmarFagundes)       | [Arthur Henrique](https://github.com/arthurhvieira1) |
| 1.5    | 09/10/2025 | Criação dos cenários CE12, CE13 e CE20      | [Arthur Henrique](https://github.com/arthurhvieira1)       | [Vilmar Fagundes](https://github.com/VilmarFagundes) |
| 1.6    | 09/10/2025 | Criação dos cenários CE17, CE18 e CE19      | [João Sapiência](https://github.com/JoaoSapiencia)         | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.7    | 12/10/2025 | Criação dos cenários CE14, CE15 e CE16      | [João Felipe](https://github.com/MrBolt2005)         | [Vilmar Fagundes](https://github.com/VilmarFagundes) |
