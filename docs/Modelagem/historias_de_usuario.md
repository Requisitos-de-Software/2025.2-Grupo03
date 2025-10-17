## Introdução
Este documento detalha o processo de levantamento e especificação das Histórias de Usuário para o projeto **SAE (Sistema de Apoio Educacional)**, uma etapa essencial no **desenvolvimento ágil** do sistema. As histórias de usuário representam descrições breves e objetivas das funcionalidades do SAE sob a perspectiva do usuário final, destacando o valor que cada funcionalidade proporciona no contexto educacional, especialmente no apoio ao processo de aprendizagem por meio de um tutor inteligente.
Esse tutor inteligente é responsável por acompanhar individualmente os estudantes, monitorando seu desempenho, identificando dificuldades e oferecendo suporte personalizado para aprimorar o aprendizado e tornar a experiência educacional mais eficaz.

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da etapa da Histórias de Usuário, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) |   |
| [Arthur Henrique](https://github.com/arthurhvieira1) |   |
| [Felipe Guimaraes](https://github.com/felipegf1) |   |
| [João Felipe](https://github.com/MrBolt2005) |   |
| [João Sapiência](https://github.com/JoaoSapiencia) |   |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Histórias de Usuário e criação das histórias de usuário [US06](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us06-combinar-resultados-formais-com-inferencias-fuzzy), [US15](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us15-enviar-notificacoes-para-revisao-de-conteudos), [US18](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us18-definir-forma-preferida-de-notificacao), [US19](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us19-enviar-notificacao-sobre-prazo-de-entrega-de-atividade), [US21](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us21-exibir-dados-e-informacoes-analiticas) e [US22](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us22-gerar-analises-em-tempo-real-com-graficos) |
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


## Gravação da validação do documento

## Agradecimentos
O Grupo 03 agradece o apoio das ferramentas de Inteligência Artificial Generativa — **ChatGPT, Google Gemini e DeepSeek** — na revisão gramatical e de estilo deste artigo. As tecnologias foram utilizadas para tornar o texto mais claro, objetivo e fácil de ler. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Referências

## Históricos de versão

| Versão | Data       | Descrição                                   | Autor(es)                                                   | Revisor       |
|--------|------------|---------------------------------------------|------------------------------------------------------------|---------------|
| 1.0    | 16/10/2025 | Criação do documento de Histórias de Usuário           | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)       | [Felipe Guimaraes](https://github.com/felipegf1) |
