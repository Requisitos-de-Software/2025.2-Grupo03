## Introdução
Este documento detalha o processo de levantamento e especificação das Histórias de Usuário para o projeto **SAE (Sistema de Apoio Educacional)**, uma etapa essencial no **desenvolvimento ágil** do sistema. As histórias de usuário representam descrições breves e objetivas das funcionalidades do SAE sob a perspectiva do usuário final, destacando o valor que cada funcionalidade proporciona no contexto educacional, especialmente no apoio ao processo de aprendizagem por meio de um tutor inteligente.
Esse tutor inteligente é responsável por acompanhar individualmente os estudantes, monitorando seu desempenho, identificando dificuldades e oferecendo suporte personalizado para aprimorar o aprendizado e tornar a experiência educacional mais eficaz.

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da etapa da Histórias de Usuário, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) | Criação das historias de usuario [US43 – Facilitar Interação entre Monitores, Professores e Alunos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us43-facilitar-interacao-entre-monitores-professores-e-alunos), [US44 – Chat Síncrono para Interação a Distância](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us44-chat-sincrono-para-interacao-a-distancia), [US46 – Exibir Progresso do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us46-exibir-progresso-do-aluno), [US49 – Análise Cognitiva e Apoio à Aprendizagem](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us49-analise-cognitiva-e-apoio-a-aprendizagem), [US50 – Identificar Conhecimento do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us50-identificar-conhecimento-do-aluno) e [US51 – Identificar Comportamento Adequado do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us51-identificar-comportamento-adequado-do-aluno) |
| [Arthur Henrique](https://github.com/arthurhvieira1) |   |
| [Felipe Guimaraes](https://github.com/felipegf1) | Criação das historias de usuario [US07 Visualizar Progresso do Aluno na Disciplina](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us07-visualizar-progresso-do-aluno-na-disciplina), [US08 - Exibir Progresso da Disciplina em Porcentagem](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us08-exibir-progresso-da-disciplina-em-porcentagem), [US09 - Visualizar Porcentagem de Acertos por Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us09-visualizar-porcentagem-de-acertos-por-conteudo), [US10 - Visualizar Porcentagem de Erros por Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us10-visualizar-porcentagem-de-erros-por-conteudo), [US12 - Exibir Média do Usuário Após Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us12-exibir-media-do-usuario-apos-atividade), [US17 - Assistir a uma Videoaula do Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us17-assistir-a-uma-videoaula-do-conteudo) |
| [João Felipe](https://github.com/MrBolt2005) |   |
| [João Sapiência](https://github.com/JoaoSapiencia) |   |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Histórias de Usuário e criação das histórias de usuário [US06 - Combinar Resultados Formais com Inferências Fuzzy](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us06-combinar-resultados-formais-com-inferencias-fuzzy), [US15 - Enviar Notificações para Revisão de Conteúdos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us15-enviar-notificacoes-para-revisao-de-conteudos), [US18 - Definir Forma Preferida de Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us18-definir-forma-preferida-de-notificacao), [US19 - Enviar Notificação sobre Prazo de Entrega de Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us19-enviar-notificacao-sobre-prazo-de-entrega-de-atividade), [US21 - Exibir Dados e Informações Analíticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us21-exibir-dados-e-informacoes-analiticas) e [US22 - Gerar Análises em Tempo Real com Gráficos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us22-gerar-analises-em-tempo-real-com-graficos) |
| [Vilmar José](https://github.com/VilmarFagundes) |   |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Metodologia
A metodologia adotada para a elaboração das Histórias de Usuário baseou-se na **análise dos requisitos funcionais** previamente identificados durante a etapa de elicitação. Cada requisito foi reinterpretado sob a perspectiva do usuário final, transformando-se em narrativas objetivas que descrevem o que o sistema deve realizar e o valor educacional que essa funcionalidade proporciona.
Esse processo garantiu uma visão centrada no usuário, em conformidade com as boas práticas do desenvolvimento ágil, e reforçou o foco do SAE em oferecer suporte personalizado ao aprendizado.

---

A padronização da tabela pode ser observada na Tabela 2.

<div align="center"><strong>Tabela 2: Padronização das Histórias de Usuário</strong></div>

| Elemento        | Descrição |
|-----------------|-----------|
| **ID**              | USN° |
| **Título**          | Nome da história de usuário, geralmente relacionado ao objetivo principal ou ao requisito funcional relacionado. |
| **História** | Descrição no formato: <br>“Como um [tipo de usuário],<br>eu quero [função ou comportamento desejado],<br>para que [benefício ou justificativa].” |
| **Critérios de Aceitação** | Conjunto de condições que definem quando a história é considerada concluída. São expressos com linguagem de comportamento esperado, seguindo o padrão: <br>“Dado que...”, “Quando...”, “Então...”. |
| **Rastreabilidade** | Indicação do(s) requisito(s) funcional(is) ao qual a história está associada. |
| **Épico Relacionado** | Referência ao épico correspondente. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>


## Histórias de Usuário

## [US06](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us06-combinar-resultados-formais-com-inferencias-fuzzy) - Combinar Resultados Formais com Inferências Fuzzy 

<div align="center"><strong>Tabela 8: US06</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US06 |
| **Título** | Combinar Resultados Formais com Inferências Fuzzy |
| **História** | Como um usuário do sistema educacional,<br>eu quero que o assistente virtual combine resultados formais com inferências Fuzzy (com avaliações graduais, como “bom”, “razoável” e “fraco”),<br>para que eu receba respostas mais contextualizadas e inteligentes nas minhas interações. |
| **Critérios de Aceitação** | - Dado que o usuário realiza uma consulta ao assistente virtual,<br>- Quando o sistema identifica incertezas ou ambiguidades,<br>- Então ele deve utilizar inferência Fuzzy para complementar os resultados formais, oferecendo respostas mais adequadas ao contexto. |
| **Rastreabilidade** | [RF06](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP06](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep06-utilizar-logica-fuzzy-para-apoiar-decisoes-pedagogicas) – Utilizar Lógica Fuzzy para Apoiar Decisões Pedagógicas  |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## [US07](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us07-visualizar-progresso-do-aluno-na-disciplina) - Visualizar Progresso do Aluno na Disciplina

<div align="center"><strong>Tabela 9: US07</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US07 |
| **Título** | Visualizar Progresso do Aluno na Disciplina |
| **História** | Como um aluno,<br>eu quero visualizar meu progresso geral na disciplina de forma clara e consolidada,<br>para que eu possa saber quais atividades já concluí, o que ainda preciso fazer e organizar melhor meus estudos. |
| **Critérios de Aceitação** | - **Dado que** o aluno está na página principal da disciplina,<br>- **Quando** ele acessa a área de "Progresso",<br>- **Então** ele deve visualizar uma representação gráfica (ex: barra de progresso com porcentagem) do seu avanço total no curso.<br><br>- **Dado que** o aluno está na tela de progresso,<br>- **Quando** ele observa a lista de atividades,<br>- **Então** as atividades concluídas devem estar claramente diferenciadas das pendentes (ex: por cor, ícone ou status).<br><br>- **Dado que** o aluno está visualizando seu progresso,<br>- **Quando** ele clica em uma atividade pendente listada,<br>- **Então** ele deve ser redirecionado para a página da respectiva atividade. |
| **Rastreabilidade** | [RF07](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** |[EP16](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep16-exibir-progresso-completo-e-percentual-do-aluno) |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

## [US08](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us08-exibir-progresso-da-disciplina-em-porcentagem) - Exibir Progresso da Disciplina em Porcentagem

<div align="center"><strong>Tabela 10: US08</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US08 |
| **Título** | Exibir Progresso da Disciplina em Porcentagem |
| **História** | Como um aluno,<br>eu quero ver o progresso total da disciplina em formato de porcentagem,<br>para que eu tenha uma noção rápida e quantitativa do quanto já avançou e do quanto ainda falta para concluir. |
| **Critérios de Aceitação** | - Dado que o aluno está na página da disciplina,<br>- Quando ele olha para o resumo do andamento,<br>- Então ele deve ver um indicador numérico claro com a porcentagem de conclusão (ex: "75% Concluído").|
| **Rastreabilidade** | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** |[EP16](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep16-exibir-progresso-completo-e-percentual-do-aluno) |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

## [US09](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us09-visualizar-porcentagem-de-acertos-por-conteudo) - Visualizar Porcentagem de Acertos por Conteúdo

<div align="center"><strong>Tabela 11: US09</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US09 |
| **Título** | Visualizar Porcentagem de Acertos por Conteúdo |
| **História** | Como um aluno,<br>eu quero visualizar minha porcentagem de acertos nas atividades, separada por cada conteúdo ou tópico,<br>para que eu possa identificar facilmente em quais assuntos estou com bom desempenho. |
| **Critérios de Aceitação** | - Dado que o aluno está na sua página de desempenho,<br>- Quando ele visualiza a lista de conteúdos da disciplina,<br>- Então ele deve ver, ao lado de cada conteúdo, a porcentagem de acertos das atividades relacionadas (ex: "Tópico 1: 90% de acertos").<br><br>- Dado que um conteúdo ainda não teve atividades realizadas,<br>- Quando o aluno olha para a porcentagem de acertos,<br>- Então deve ser exibido um status indicativo como "N/A" ou "Aguardando realização". |
| **Rastreabilidade** | [RF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP14](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep14-exibir-medias-e-porcentagens-por-conteudo-e-usuario)|

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

## [US10](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us10-visualizar-porcentagem-de-erros-por-conteudo) - Visualizar Porcentagem de Erros por Conteúdo

<div align="center"><strong>Tabela 12: US10</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US10 |
| **Título** | Visualizar Porcentagem de Erros por Conteúdo |
| **História** | Como um aluno,<br>eu quero visualizar minha porcentagem de erros nas atividades, separada por cada conteúdo ou tópico,<br>para que eu saiba exatamente onde estão minhas dificuldades e em quais assuntos preciso focar para estudar mais. |
| **Critérios de Aceitação** | - Dado que o aluno está na sua página de desempenho,<br>- Quando ele visualiza a lista de conteúdos da disciplina,<br>- Então ele deve ver, ao lado de cada conteúdo, a porcentagem de erros das atividades relacionadas (ex: "Tópico 2: 30% de erros").<br><br>- Dado que o aluno visualiza uma alta porcentagem de erros para um tópico,<br>- Quando ele clica nesse tópico,<br>- Então o sistema pode levá-lo para uma página de reforço com os materiais de estudo daquele conteúdo. |
| **Rastreabilidade** | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP14](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep14-exibir-medias-e-porcentagens-por-conteudo-e-usuario) |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

## [US12](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us12-exibir-media-do-usuario-apos-atividade) - Exibir Média do Usuário Após Atividade

<div align="center"><strong>Tabela 14: US12</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US12 |
| **Título** | Exibir Média do Usuário Após Atividade |
| **História** | Como um aluno,<br>eu quero ver minha média ou nota imediatamente após finalizar uma atividade,<br>para que eu possa ter um feedback rápido sobre meu desempenho e saber como fui. |
| **Critérios de Aceitação** | - Dado que o aluno completou todos os itens de uma atividade,<br>- Quando ele clica no botão "Finalizar" ou "Submeter",<br>- Então a interface deve exibir a média obtida (ex: nota, porcentagem de acertos) para aquela atividade específica.<br><br>- Dado que a média é exibida,<br>- Quando o aluno a visualiza,<br>- Então ela deve ser apresentada de forma clara e visível na tela de resultados da atividade. |
| **Rastreabilidade** | [RF12](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** |[EP14](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep14-exibir-medias-e-porcentagens-por-conteudo-e-usuario) |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

## [US15](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us15-enviar-notificacoes-para-revisao-de-conteudos) - Enviar Notificações para Revisão de Conteúdos  

<div align="center"><strong>Tabela 17: US15</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US15 |
| **Título** | Enviar Notificações para Revisão de Conteúdos |
| **História** | Como um aluno do sistema,<br>Eu quero receber notificações que me lembrem de revisar conteúdos estudados,<br>Para que eu mantenha a aprendizagem contínua e evite esquecer informações importantes. |
| **Critérios de Aceitação** | - Dado que o usuário tenha concluído um conteúdo,<br>- Quando chegar o momento ideal de revisão,<br>- Então o sistema deve enviar uma notificação lembrando o usuário de revisar o conteúdo. |
| **Rastreabilidade** | [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP19](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep19-enviar-alertas-sobre-prazos-e-revisoes-de-conteudo) – Enviar Alertas sobre Prazos e Revisões de Conteúdo |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## [US17](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us17-assistir-a-uma-videoaula-do-conteudo) - Assistir a uma Videoaula do Conteúdo  

<div align="center"><strong>Tabela 19: US17</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US17 |
| **Título** | Assistir a uma Videoaula do Conteúdo |
| **História** | Como um aluno,<br>eu quero assistir a videoaulas relacionadas aos conteúdos da disciplina,<br>para que eu possa ter um recurso de aprendizado visual e auditivo que me ajude a compreender melhor os temas. |
| **Critérios de Aceitação** | - Dado que o aluno está na página de um conteúdo da disciplina,<br>- Quando uma videoaula estiver disponível para aquele conteúdo,<br>- Então ele deve visualizar um player de vídeo ou um link claro para acessá-la.<br><br>- Dado que o aluno clica no botão de play,<br>- Quando o vídeo é reproduzido,<br>- Então ele deve ter acesso a controles básicos (play/pause, volume, tela cheia).<br><br>- Dado que o aluno assiste à videoaula até o fim,<br>- Quando ele retorna à lista de atividades,<br>- Então a videoaula deve ser marcada como "concluída". |
| **Rastreabilidade** | [RF17](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP20](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep20-disponibilizar-video-aulas-como-recurso-complementar) |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

## [US18](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us18-definir-forma-preferida-de-notificacao) - Definir Forma Preferida de Notificação  

<div align="center"><strong>Tabela 20: US18</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US18 |
| **Título** | Definir Forma Preferida de Notificação |
| **História** | Como um usuário do sistema,<br>Eu quero escolher a forma pela qual desejo receber notificações (app, e-mail, SMS etc.),<br>Para que eu receba alertas de forma mais conveniente e personalizada. |
| **Critérios de Aceitação** | - Dado que o usuário acesse as configurações de notificação,<br>- Quando ele selecionar o método preferido,<br>- Então o sistema deve registrar e utilizar essa preferência em futuras notificações. |
| **Rastreabilidade** | [RF18](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP18](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep18-configurar-preferencias-de-tempo-e-forma-de-notificacao) – Configurar Preferências de Tempo e Forma de Notificação  |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## [US19](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us19-enviar-notificacao-sobre-prazo-de-entrega-de-atividade) - Enviar Notificação sobre Prazo de Entrega de Atividade  

<div align="center"><strong>Tabela 21: US19</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US19 |
| **Título** | Enviar Notificação sobre Prazo de Entrega de Atividade |
| **História** | Como um aluno,<br>Eu quero receber notificações quando o prazo de entrega de uma atividade estiver próximo,<br>Para que eu não perca o prazo e mantenha meu desempenho acadêmico. |
| **Critérios de Aceitação** | - Dado que o usuário tenha atividades com prazos definidos,<br>- Quando faltar um período configurável (ex: 24h) para o vencimento,<br>- Então o sistema deve enviar uma notificação de alerta. |
| **Rastreabilidade** | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP19](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep19-enviar-alertas-sobre-prazos-e-revisoes-de-conteudo) – Enviar Alertas sobre Prazos e Revisões de Conteúdo |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## [US21](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us21-exibir-dados-e-informacoes-analiticas) - Exibir Dados e Informações Analíticas  
<div align="center"><strong>Tabela 23: US21</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US21 |
| **Título** | Exibir Dados e Informações Analíticas |
| **História** | Como um professor ou gestor,<br>Eu quero visualizar dados e informações analíticas em diferentes níveis (individual, turma, entre turmas),<br>Para que eu possa acompanhar o desempenho e apoiar a tomada de decisão pedagógica. |
| **Critérios de Aceitação** | - Dado que o usuário acesse o painel analítico,<br>- Quando ele selecionar o nível desejado (individual, turma, entre turmas),<br>- Então o sistema deve exibir os dados correspondentes de forma clara e atualizada. |
| **Rastreabilidade** | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP13](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep13-gerar-analises-em-tempo-real-com-graficos-e-indicadores) – Gerar Análises em Tempo Real com Gráficos e Indicadores |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## [US22](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us22-gerar-analises-em-tempo-real-com-graficos) - Gerar Análises em Tempo Real com Gráficos  

<div align="center"><strong>Tabela 24: US22</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US22 |
| **Título** | Gerar Análises em Tempo Real com Gráficos |
| **História** | Como um usuário do sistema,<br>Eu quero visualizar análises de desempenho em tempo real representadas em gráficos (barra, coluna, linha, pizza),<br>Para que eu compreenda facilmente o progresso e os resultados. |
| **Critérios de Aceitação** | - Dado que o sistema possua dados de desempenho,<br>- Quando o usuário acessar o painel de análises,<br>- Então o sistema deve gerar e atualizar gráficos em tempo real conforme os dados são modificados. |
| **Rastreabilidade** | [RF22](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP13](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep13-gerar-analises-em-tempo-real-com-graficos-e-indicadores) – Gerar Análises em Tempo Real com Gráficos e Indicadores |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## US43 – Facilitar Interação entre Monitores, Professores e Alunos

<div align="center"><strong>Tabela 45: US43</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US43 |
| **Título**          | Facilitar Interação entre Monitores, Professores e Alunos |
| **História**        | Como um usuário do sistema educacional,<br>eu quero que o sistema facilite a comunicação entre monitores, professores e alunos, para que a troca de informações e apoio pedagógico seja mais eficiente. |
| **Critérios de Aceitação** | - Dado que o usuário acessa o sistema,<br>- Quando desejar interagir com outro perfil educacional,<br>- Então o sistema deve oferecer meios de comunicação integrados e acessíveis. |
| **Rastreabilidade** | RF43 |
| **Épico Relacionado** | EP26 – Facilitar Comunicação via Chat e Monitoria |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## US44 – Chat Síncrono para Interação a Distância

<div align="center"><strong>Tabela 46: US44</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US44 |
| **Título**          | Chat Síncrono para Interação a Distância |
| **História**        | Como um aluno,<br>eu quero utilizar um chat síncrono no sistema, para que eu possa interagir com professores e monitores em tempo real, mesmo à distância. |
| **Critérios de Aceitação** | - Dado que o aluno está conectado ao sistema,<br>- Quando inicia uma conversa pelo chat,<br>- Então a comunicação deve ocorrer em tempo real, com histórico acessível. |
| **Rastreabilidade** | RF44 |
| **Épico Relacionado** | EP26 – Facilitar Comunicação via Chat e Monitoria |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## US46 – Exibir Progresso do Aluno

<div align="center"><strong>Tabela 48: US46</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US46 |
| **Título**          | Exibir Progresso do Aluno |
| **História**        | Como um aluno,<br>eu quero que o assistente virtual me informe sobre meu progresso,<br>para que eu possa acompanhar meu desempenho e evolução no curso. |
| **Critérios de Aceitação** | - Dado que o aluno acessa o assistente virtual,<br>- Quando solicita informações sobre seu progresso,<br>- Então o sistema deve apresentar dados atualizados e relevantes. |
| **Rastreabilidade** | RF46 |
| **Épico Relacionado** | EP11 – Acompanhar Interações e Progresso do Usuário |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## US49 – Análise Cognitiva e Apoio à Aprendizagem

<div align="center"><strong>Tabela 51: US49</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US49 |
| **Título**          | Análise Cognitiva e Apoio à Aprendizagem |
| **História**        | Como um aluno,<br>eu quero que o assistente virtual compreenda minha situação cognitiva, para que ele possa me ajudar de forma personalizada na aprendizagem. |
| **Critérios de Aceitação** | - Dado que o aluno interage com o assistente virtual,<br>- Quando o sistema identifica dificuldades cognitivas,<br>- Então ele deve oferecer suporte adaptado às necessidades do aluno. |
| **Rastreabilidade** | RF49 |
| **Épico Relacionado** | EP10 – Analisar Dificuldades Cognitivas e Sugerir Conteúdos |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## US50 – Identificar Conhecimento do Aluno

<div align="center"><strong>Tabela 52: US50</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US50 |
| **Título**          | Identificar Conhecimento do Aluno |
| **História**        | Como um professor,<br>eu quero saber quais alunos dominam o conteúdo,<br>para que eu possa planejar melhor minhas aulas e intervenções. |
| **Critérios de Aceitação** | - Dado que o professor acessa o sistema,<br>- Quando solicita informações sobre o conhecimento dos alunos,<br>- Então o sistema deve apresentar dados precisos sobre o domínio de conteúdo. |
| **Rastreabilidade** | RF50 |
| **Épico Relacionado** | EP27 – Fornecer Dados ao Professor sobre Domínio e Comportamento |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## US51 – Identificar Comportamento Adequado do Aluno

<div align="center"><strong>Tabela 53: US51</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US51 |
| **Título**          | Identificar Comportamento Adequado do Aluno |
| **História**        | Como um professor,<br>eu quero visualizar quais alunos têm comportamento adequado,<br>para que eu possa reconhecer e incentivar boas práticas como presença e entrega de atividades. |
| **Critérios de Aceitação** | - Dado que o professor acessa o sistema,<br>- Quando solicita dados comportamentais dos alunos,<br>- Então o sistema deve apresentar indicadores como frequência e pontualidade nas entregas. |
| **Rastreabilidade** | RF51 |
| **Épico Relacionado** | EP27 – Fornecer Dados ao Professor sobre Domínio e Comportamento |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## Gravação da validação do documento

## Agradecimentos
O Grupo 03 agradece o apoio das ferramentas de Inteligência Artificial Generativa — **ChatGPT, Google Gemini e DeepSeek** — na revisão gramatical e de estilo deste artigo. As tecnologias foram utilizadas para tornar o texto mais claro, objetivo e fácil de ler. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Referências

## Históricos de versão

| Versão | Data       | Descrição  | Autor(es)        | Revisor    |
|--------|------------|---------------------------------------------|----|---------------|
| 1.0    | 16/10/2025 | Criação do documento de Histórias de Usuário  | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)| [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.1    | 16/10/2025 | Criação das historias de usuario 7, 8, 9, 10, 12 e 17 | [Felipe Guimaraes](https://github.com/felipegf1)| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.2    | 18/10/2025 | Criação das historias de usuario 43, 44, 46, 49, 50 e 51 | [Arthur Guilherme](https://github.com/ArthurGuilher62)| [Felipe Guimaraes](https://github.com/felipegf1) |
