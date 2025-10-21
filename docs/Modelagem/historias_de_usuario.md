## Introdução
Este documento detalha o processo de levantamento e especificação das Histórias de Usuário para o projeto **SAE (Sistema de Apoio Educacional)**, uma etapa essencial no **desenvolvimento ágil** do sistema. As histórias de usuário representam descrições breves e objetivas das funcionalidades do SAE sob a perspectiva do usuário final, destacando o valor que cada funcionalidade proporciona no contexto educacional, especialmente no apoio ao processo de aprendizagem por meio de um tutor inteligente.
Esse tutor inteligente é responsável por acompanhar individualmente os estudantes, monitorando seu desempenho, identificando dificuldades e oferecendo suporte personalizado para aprimorar o aprendizado e tornar a experiência educacional mais eficaz.

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da etapa da Histórias de Usuário, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) | Criação das historias de usuario [US43 – Facilitar Interação entre Monitores, Professores e Alunos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us43-facilitar-interacao-entre-monitores-professores-e-alunos), [US44 – Chat Síncrono para Interação a Distância](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us44-chat-sincrono-para-interacao-a-distancia), [US46 – Exibir Progresso do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us46-exibir-progresso-do-aluno), [US49 – Análise Cognitiva e Apoio à Aprendizagem](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us49-analise-cognitiva-e-apoio-a-aprendizagem), [US50 – Identificar Conhecimento do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us50-identificar-conhecimento-do-aluno) e [US51 – Identificar Comportamento Adequado do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us51-identificar-comportamento-adequado-do-aluno) |
| [Arthur Henrique](https://github.com/arthurhvieira1) | Criação das histórias de usuário [US03 - Mapeamento de Conceitos segundo a Teoria da Aprendizagem Significativa (TAS)](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us03-mapeamento-de-conceitos-segundo-a-teoria-da-aprendizagem-significativa-tas), [US04 - Alinhamento do Plano de Ensino ao AVA](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us04-alinhamento-do-plano-de-ensino-ao-ava), [US05 - Integração de Avaliações ao AVA](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us05-integracao-de-avaliacoes-ao-ava), [US16 - Índice de Conteúdos Ordenado por Porcentagem de Erros](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us16-indice-de-conteudos-ordenado-por-porcentagem-de-erros), [US20 - Configuração de Notificação de Prazos pelo Usuário](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us20-configuracao-de-notificacao-de-prazos-pelo-usuario), [US25 - Interação com Questões (Avaliação Informativa e Formativa)](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us25-interacao-com-questoes-avaliacao-informativa-e-formativa) e [US26 - Assistência ao Professor no Módulo de Interação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us26-assistencia-ao-professor-no-modulo-de-interacao) |
| [Felipe Guimaraes](https://github.com/felipegf1) | Criação das historias de usuario [US07 Visualizar Progresso do Aluno na Disciplina](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us07-visualizar-progresso-do-aluno-na-disciplina), [US08 - Exibir Progresso da Disciplina em Porcentagem](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us08-exibir-progresso-da-disciplina-em-porcentagem), [US09 - Visualizar Porcentagem de Acertos por Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us09-visualizar-porcentagem-de-acertos-por-conteudo), [US10 - Visualizar Porcentagem de Erros por Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us10-visualizar-porcentagem-de-erros-por-conteudo), [US12 - Exibir Média do Usuário Após Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us12-exibir-media-do-usuario-apos-atividade), [US17 - Assistir a uma Videoaula do Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us17-assistir-a-uma-videoaula-do-conteudo) |
| [João Felipe](https://github.com/MrBolt2005) | Criação das histórias de usuário [US14](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us14-selecao-de-disciplinas-mais-faceis), [US24](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us24-calculo-do-desempenho-do-aluno), [US30](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us30-direcionamento-sob-medida-de-materiais-aos-alunos), [US37](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us37-inferencias-com-logica-fuzzy), [US42](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us42-notificacao-de-conteudos-mais-dificeis) e [US47](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us47-informacoes-sobre-horarios-e-locais-de-monitoria). |
| [João Sapiência](https://github.com/JoaoSapiencia) |   |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Histórias de Usuário e criação das histórias de usuário [US06 - Combinar Resultados Formais com Inferências Fuzzy](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us06-combinar-resultados-formais-com-inferencias-fuzzy), [US15 - Enviar Notificações para Revisão de Conteúdos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us15-enviar-notificacoes-para-revisao-de-conteudos), [US18 - Definir Forma Preferida de Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us18-definir-forma-preferida-de-notificacao), [US19 - Enviar Notificação sobre Prazo de Entrega de Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us19-enviar-notificacao-sobre-prazo-de-entrega-de-atividade), [US21 - Exibir Dados e Informações Analíticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us21-exibir-dados-e-informacoes-analiticas) e [US22 - Gerar Análises em Tempo Real com Gráficos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us22-gerar-analises-em-tempo-real-com-graficos) |
| [Vilmar José](https://github.com/VilmarFagundes) | Criação das histórias de usuário [US01 - Identificação e Autenticação de Usuários](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us01-identificacao-e-autenticacao-de-usuarios), [US02 - Visualizar e Gerenciar Perfil Individual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us02-visualizar-e-gerenciar-perfil-individual), [US11 - Exibir média geral da turma](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us11-exibir-media-geral-da-turma), [US13 - Configurar Alertas de Atividades Atrasadas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us13-configurar-alertas-de-atividades-atrasadas), [US28 - Gerenciar Banco de Questões do Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us28-gerenciar-banco-de-questoes-do-professor) e [US38 - Visualizar Personagem do Assistente Virtual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us38-visualizar-personagem-do-assistente-virtual) |

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

## [US01](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us01-identificacao-e-autenticacao-de-usuarios) - Identificação e Autenticação de Usuários

<div align="center"><strong>Tabela 3: US01</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US01 |
| **Título** | Identificação e Autenticação de Usuários |
| **História** | Como um usuário (aluno, monitor, professor, coordenador, diretor ou administrador),<br>eu quero me identificar e autenticar no sistema,<br>para que eu possa acessar as funcionalidades e informações específicas do meu perfil. |
| **Critérios de Aceitação** | - **Dado que** o usuário acessa a tela de login do sistema,<br>- **Quando** ele insere suas credenciais válidas (ex: usuário e senha),<br>- **Então** o sistema deve identificá-lo e carregar a interface correspondente ao seu papel (aluno, monitor, professor, etc.).<br><br>- **Dado que** o usuário está logado,<br>- **Quando** ele tenta acessar uma funcionalidade restrita a outro perfil,<br>- **Então** o sistema deve negar o acesso. |
| **Rastreabilidade** | [RF01](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP01](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep01-gerenciar-perfis-de-usuarios) – Gerenciar Perfis de Usuários |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

---

## [US02](https://www.google.com/search?q=https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/%23us02-visualizar-e-gerenciar-perfil-individual) - Visualizar e Gerenciar Perfil Individual

<div align="center"><strong>Tabela 4: US02</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US02 |
| **Título** | Visualizar e Gerenciar Perfil Individual |
| **História** | Como um usuário do sistema,<br>eu quero ter um perfil individual onde possa visualizar e gerenciar minhas informações pessoais e preferências,<br>para que minha experiência no sistema seja personalizada e meus dados estejam sempre atualizados. |
| **Critérios de Aceitação** | - **Dado que** o usuário está logado no sistema,<br>- **Quando** ele acessa a seção "Meu Perfil",<br>- **Então** ele deve visualizar suas informações cadastrais (nome, e-mail, papel no sistema, etc.).<br><br>- **Dado que** o usuário está na sua página de perfil,<br>- **Quando** ele clica em "Editar Informações",<br>- **Então** o sistema deve permitir a alteração de dados permitidos, como senha, foto de perfil ou preferências de notificação. |
| **Rastreabilidade** | [RF02](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP01](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep01-gerenciar-perfis-de-usuarios) – Gerenciar Perfis de Usuários |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

<div align="center"><strong>Tabela 5: US03</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US03 |
| **Título** | Mapeamento de Conceitos segundo a TAS |
| **História** | Como um coordenador pedagógico,<br>eu quero mapear conceitos do conteúdo respeitando a hierarquia da Teoria da Aprendizagem Significativa (TAS),<br>para que pré-requisitos e relações entre tópicos orientem atividades e recomendações. |
| **Critérios de Aceitação** | - Dado que defino conceitos e pré-requisitos,<br>- Quando salvo o mapa conceitual,<br>- Então o sistema deve representar a hierarquia (do mais inclusivo ao menos inclusivo) e validar ciclos inconsistentes.<br><br>- Dado que o aluno possui lacunas em pré-requisitos,<br>- Quando ele acessa um tópico avançado,<br>- Então o sistema deve recomendar estudo dos conceitos base antes de prosseguir.<br><br>- Dado o mapa conceitual publicado,<br>- Quando o professor cria atividades,<br>- Então o sistema deve sugerir questões alinhadas aos conceitos e níveis hierárquicos. |
| **Rastreabilidade** | [RF03]((https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

<div align="center"><strong>Tabela 6: US04</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US04 |
| **Título** | Alinhamento do Plano de Ensino ao AVA |
| **História** | Como um professor,<br>eu quero agregar o processo formal de avaliação do Plano de Ensino ao ambiente virtual,<br>para que prazos, pesos e critérios avaliativos fiquem sincronizados com as atividades online. |
| **Critérios de Aceitação** | - Dado que importo o Plano de Ensino (prazos, pesos, critérios),<br>- Quando confirmo o alinhamento,<br>- Então o sistema deve criar/exigir as avaliações no AVA com as configurações correspondentes.<br><br>- Dado que há alterações no Plano de Ensino,<br>- Quando publico uma nova versão,<br>- Então o calendário, pesos e rubricas do AVA devem ser atualizados mantendo histórico de versões.<br><br>- Dado o Plano de Ensino em vigor,<br>- Quando os alunos acessam a disciplina,<br>- Então devem ver cronograma, pesos e critérios consolidados em uma única visão. |
| **Rastreabilidade** | [RF04]((https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

<div align="center"><strong>Tabela 7: US17</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US05 |
| **Título** | Integração de Avaliações ao AVA |
| **História** | Como um professor,<br>eu quero integrar as avaliações (provas, atividades, rubricas) diretamente ao AVA,<br>para que a criação, aplicação, correção e lançamento de notas ocorram em um fluxo único. |
| **Critérios de Aceitação** | - Dado que crio uma avaliação no módulo de avaliações,<br>- Quando eu a publico,<br>- Então ela deve aparecer automaticamente no AVA com prazos, tentativas e rubricas configuradas.<br><br>- Dado que os alunos submetem respostas,<br>- Quando a avaliação encerra,<br>- Então o sistema deve disponibilizar correção (automática ou por rubrica), feedback e lançar notas no boletim da disciplina.<br><br>- Dado que há ajustes após a publicação,<br>- Quando atualizo instruções, rubrica ou prazo,<br>- Então o AVA deve refletir as mudanças e notificar os alunos. |
| **Rastreabilidade** | [RF05]((https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)) |
| **Épico Relacionado** ||
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

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

## [US11](https://www.google.com/search?q=https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/%23us11-exibir-media-geral-da-turma) - Exibir Média Geral da Turma

<div align="center"><strong>Tabela 13: US11</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US11 |
| **Título** | Exibir Média Geral da Turma por Atividade |
| **História** | Como um usuário do sistema,<br>eu quero visualizar a média geral da turma em cada atividade,<br>para que eu possa avaliar o desempenho coletivo e identificar quais atividades apresentaram maior dificuldade para o grupo. |
| **Critérios de Aceitação** | - **Dado que** o usuário está na página de atividades da turma,<br>- **Quando** ele visualiza a lista de atividades concluídas,<br>- **Então** o sistema deve exibir a média geral da turma (ex: nota ou porcentagem) para cada atividade. |
| **Rastreabilidade** | [RF11](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP13](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep13-gerar-analises-em-tempo-real-com-graficos-e-indicadores) – Gerar Análises em Tempo Real com Gráficos e Indicadores |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

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

## [US13](https://www.google.com/search?q=https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/%23us13-configurar-alertas-de-atividades-atrasadas) - Configurar Alertas de Atividades Atrasadas

<div align="center"><strong>Tabela 15: US13</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US13 |
| **Título** | Configurar Tempo de Alerta para Atividades Atrasadas |
| **História** | Como um usuário,<br>eu quero escolher o tempo em que desejo receber alertas sobre minhas atividades atrasadas,<br>para que eu possa gerenciar minhas pendências conforme minha preferência, sem receber notificações excessivas. |
| **Critérios de Aceitação** | - **Dado que** o usuário acessa seu painel de "Configurações de Notificação",<br>- **Quando** ele seleciona a opção "Atividades Atrasadas",<br>- **Então** o sistema deve exibir opções de tempo (ex: "1 dia após o prazo", "A cada 3 dias", "Não notificar").<br><br>- **Dado que** o usuário salvou sua preferência de tempo,<br>- **Quando** uma atividade sua ficar atrasada pelo período configurado,<br>- **Então** o sistema deve enviar um alerta pelo canal preferido (definido na US18). |
| **Rastreabilidade** | [RF13](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP18](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep18-configurar-preferencias-de-tempo-e-forma-de-notificacao) – Configurar Preferências de Tempo e Forma de Notificação |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

---

## [US14](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us14-selecao-de-disciplinas-mais-faceis) - Seleção de Disciplinas Mais Fáceis

<div align="center"><strong>Tabela 26: US14</strong></div>

| Campo | Descrição |
|-------|-----------|
| **ID** | US14 |
| **Título** | Seleção de Disciplinas Mais Fáceis |
| **História** | **Como** um aluno no sistema educacional, **quero** selecionar as disciplinas matriculadas onde me sinto mais confortável e com maior facilidade, **para** o melhor ajuste das minhas sugestões e análises de desempenho. |
| **Critérios de Aceitação** | - **Dado** que o aluno acesse o seu painel de preferências,<br>- **Quando** ele selecionar, revisar ou alterar as disciplinas ou (os) tópicos em que sentir maior facilidade,<br>- **Então** o sistema salva essas preferências e as utiliza para ajustar relatórios, notificações e recomendações futuras. |
| **Rastreabilidade** | [RF14](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP17](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep17-personalizar-sugestoes-e-analises-com-base-em-disciplinas-facilitadas) – Personalizar Sugestões e Análises com Base em Disciplinas Facilitadas |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

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

<div align="center"><strong>Tabela 18: US16</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US16 |
| **Título** | Índice de Conteúdos Ordenado por Porcentagem de Erros |
| **História** | Como um aluno,<br>eu quero visualizar um índice de conteúdos ordenado pela porcentagem de erros,<br>para que eu identifique facilmente quais tópicos tenho mais dificuldade e priorize meus estudos nesses assuntos. |
| **Critérios de Aceitação** | - Dado que o aluno acessa a página de desempenho,<br>- Quando o sistema carrega o índice de conteúdos,<br>- Então os conteúdos devem ser listados em ordem decrescente de porcentagem de erros (do maior para o menor).<br><br>- Dado que dois conteúdos tenham a mesma porcentagem de erros,<br>- Quando o sistema exibe o índice,<br>- Então deve aplicar ordenação secundária alfabética pelo nome do conteúdo.<br><br>- Dado que o aluno clique em um conteúdo no índice,<br>- Quando ele acessa os detalhes,<br>- Então o sistema deve exibir gráficos e atividades relacionadas a esse conteúdo específico. |
| **Rastreabilidade** | [RF16]((https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

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

<div align="center"><strong>Tabela 22: US20</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US20 |
| **Título** | Configuração de Notificação de Prazos pelo Usuário |
| **História** | Como um aluno,<br>eu quero escolher quando quero receber notificações sobre a proximidade da data de entrega de uma atividade,<br>para que eu possa me organizar conforme minha rotina e evitar atrasos. |
| **Critérios de Aceitação** | - Dado que o aluno acessa as configurações de notificações,<br>- Quando ele seleciona o tempo de antecedência (ex: 1 dia, 3 dias, 1 semana),<br>- Então o sistema deve salvar a preferência e exibir uma confirmação visual de que a configuração foi atualizada.<br><br>- Dado que uma atividade está próxima do prazo configurado,<br>- Quando a antecedência definida é atingida,<br>- Então o sistema deve enviar uma notificação via canal escolhido (e-mail, push, ou WhatsApp).<br><br>- Dado que o aluno desative as notificações,<br>- Quando salvar a configuração,<br>- Então o sistema deve deixar de enviar alertas até que o recurso seja reativado. |
| **Rastreabilidade** | [RF20]((https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

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

## [US24](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us24-calculo-do-desempenho-do-aluno) – Cálculo do Desempenho do Aluno

<div align="center"><strong>Tabela 26: US24</strong></div>

| Campo                | Descrição |
|----------------------|-----------|
| **ID**              | US24 |
| **Título**          | Cálculo do Desempenho do Aluno |
| **História**        | **Como** um usuário do sistema educacional, **quero** visualizar tanto o quão bem minha turma no geral ou alunos individuais – eu mesmo, se for um aluno, ou qualquer aluno, se eu for o professor –, está se saindo numa disciplina, como também como se chegou a esse resultado, **para** saber mais especificamente os pontos fortes e fracos em particular no exercício na disciplina, e quais deles estão sendo mais influentes no próprio desempenho geral finalmente obtido. |
| **Critérios de Aceitação** | - **Dado** que o usuário acesse a página de uma turma em que esteja matriculado ou lecione, <br>- **Quando** abrir as informações de desempenho individual e geral dessa turma, <br>- **Então** deve visualizar esses desempenhos, mais as suas métricas de computação e os métodos usados para os próprios cálculos. <br><br>- **Dado** que o usuário tenha configurado para ser notificado sobre tal, <br>- **Quando** houver atualizações significantes sobre métricas de computação de desempenho que ele for escolher, <br>- **Então** deverá ser notificado sobre isto pelo sistema nos canais desejados. |
| **Rastreabilidade** | [RF24](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) | |
| **Épico Relacionado** | [EP15](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep15-calcular-desempenho-do-aluno-com-base-em-metricas-definidas) – Calcular Desempenho do Aluno com Base em Métricas Definidas |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

<div align="center"><strong>Tabela 27: US25</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US25 |
| **Título** | Interação com Questões (Avaliação Informativa e Formativa) |
| **História** | Como um aluno,<br>eu quero interagir com questões que avaliem meu conhecimento informativo e formativo,<br>para aprender com feedback imediato e acompanhar minha evolução. |
| **Critérios de Aceitação** | - Dado que o aluno responde a uma questão,<br>- Quando submete a resposta,<br>- Então deve receber feedback imediato com explicação, referência de estudo e sugestão de próximo passo (formativa).<br><br>- Dado um conjunto de questões de um tópico,<br>- Quando o aluno conclui o bloco,<br>- Então o sistema deve mostrar resumo com acertos, erros e recomendações de reforço (informativa + formativa).<br><br>- Dado que o aluno revisite uma questão,<br>- Quando visualizar o histórico,<br>- Então deve ver suas tentativas, feedbacks e progresso ao longo do tempo. |
| **Rastreabilidade** | [RF25]((https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

<div align="center"><strong>Tabela 28: US26</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US26 |
| **Título** | Assistência ao Professor no Módulo de Interação |
| **História** | Como um professor,<br>eu quero receber assistência do SAE para planejar, aplicar e revisar atividades no módulo de interação,<br>para otimizar o tempo e melhorar a qualidade pedagógica. |
| **Critérios de Aceitação** | - Dado que informo objetivos de aprendizagem e o conteúdo,<br>- Quando solicito sugestões,<br>- Então o sistema deve recomendar tipos de questões, níveis de dificuldade e materiais de apoio coerentes.<br><br>- Dado que a turma concluiu uma atividade,<br>- Quando abro o relatório do módulo,<br>- Então devo ver estatísticas por questão/tópico, principais erros, padrões de confusão e sugestões de intervenção.<br><br>- Dado que tenho pouco tempo para preparar uma aula,<br>- Quando aciono o assistente do SAE,<br>- Então ele deve gerar um roteiro com sequência de atividades e checkpoints avaliativos. |
| **Rastreabilidade** | [RF26]((https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---


## [US28](https://www.google.com/search?q=https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/%23us28-gerenciar-banco-de-questoes-do-professor) - Gerenciar Banco de Questões do Professor

<div align="center"><strong>Tabela 30: US28</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US28 |
| **Título** | Gerenciar Banco de Questões do Professor |
| **História** | Como um professor,<br>eu quero cadastrar, organizar e gerenciar meu próprio banco de questões,<br>para que eu possa reutilizá-las facilmente na criação de diferentes atividades e avaliações. |
| **Critérios de Aceitação** | - **Dado que** o professor acessa a área "Meu Banco de Questões",<br>- **Quando** ele clica em "Adicionar Nova Questão",<br>- **Então** o sistema deve permitir que ele insira o enunciado, as alternativas (se aplicável), a resposta correta e associe a um tópico/conteúdo.<br><br>- **Dado que** o professor está montando uma nova atividade,<br>- **Quando** ele seleciona a opção "Importar do Banco de Questões",<br>- **Então** o sistema deve permitir que ele filtre e selecione as questões que ele gerou anteriormente. |
| **Rastreabilidade** | [RF28](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP23](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep23-gerenciar-banco-de-questoes-de-professores-e-outras-fontes) – Gerenciar Banco de Questões de Professores e Outras Fontes |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

---

## [US30](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us30-direcionamento-sob-medida-de-materiais-aos-alunos) – Direcionamento Sob Medida de Materiais aos Alunos

<div align="center"><strong>Tabela 32: US30</strong></div>

| Campo                | Descrição |
|----------------------|-----------|
| **ID**              | US30 |
| **Título**          | Direcionamento Sob Medida de Materiais aos Alunos |
| **História**        | **Como** um docente no sistema educacional, **quero** que o sistema direcione cada aluno a materiais adequados à sua situação cognitiva e às suas preferências **para** que eles foquem melhor seus esforços e pedidos de ajuda quando for mais necessário. |
| **Critérios de Aceitação** | - **Dado** que o professor tenha cadastrado materiais de estudo no sistema, <br>- **Quando** o sistema analisar o desempenho e preferências dos alunos periodicamente, <br>- **Então** ele deve sugerir materiais específicos para cada aluno conforme suas necessidades. <br><br>- **Dado** que o docente tenha acesso ao painel de gerenciamento de materiais, <br>- **Quando** ele configurar os parâmetros para direcionamento de materiais (ex: tipo de material, nível de dificuldade, formato preferencial) por aluno ou grupo de alunos, <br>- **Então** o sistema deve aplicar essas configurações para selecionar e apresentar os materiais mais relevantes. <br><br>- **Dado** que um aluno acesse a área de materiais de estudo, <br>- **Quando** o sistema exibir os materiais direcionados, <br>- **Então** esses materiais devem estar alinhados com suas características cognitivas e de desempenho (identificadas pelo sistema) e suas preferências (configuradas pelo aluno ou docente). |
| **Rastreabilidade** | [RF30](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) | |
| **Épico Relacionado** | [EP21](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep21-direcionar-materiais-de-estudo-com-base-em-desempenho-e-preferencias) – Direcionar Materiais de Estudo com Base em Desempenho e Preferências |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

## [US37](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us37-inferencias-com-logica-fuzzy) – Inferências com Lógica *Fuzzy*

<div align="center"><strong>Tabela 39: US37</strong></div>

| Campo                | Descrição |
|----------------------|-----------|
| **ID**              | US37 |
| **Título**          | Inferências com Lógica *Fuzzy* |
| **História**        | **Como** um usuário do sistema educacional, **quero** que as inferências avaliadas nesse sistema envolvam a lógica *fuzzy*, isto é, com a possibilidade de níveis intermediários entre apenas “bom” e “fraco”, **para** aumentar/melhorar a sua granularidade, precisão e clareza perante a mim próprio. |
| **Critérios de Aceitação** | - **Dado** que o sistema esteja avaliando o desempenho do usuário, <br>- **Quando** qualquer métrica de desempenho, seja ela geral ou específica de um conteúdo, for calculada ou atualizada, <br>- **Então** o sistema deve aplicar lógica fuzzy para determinar os níveis de desempenho (ex.: "fraco", “razoável”, "regular", "bom", "muito bom" etc.) em vez de uma simples dicotomia binária. |
| **Rastreabilidade** | [RF37](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) | |
| **Épico Relacionado** | [EP06](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep06-utilizar-logica-fuzzy-para-apoiar-decisoes-pedagogicas) – Utilizar Lógica Fuzzy para Apoiar Decisões Pedagógicas |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

## [US38](https://www.google.com/search?q=https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/%23us38-visualizar-personagem-do-assistente-virtual) - Visualizar Personagem do Assistente Virtual

<div align="center"><strong>Tabela 40: US38</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US38 |
| **Título** | Visualizar o Personagem do Assistente Virtual |
| **História** | Como um usuário do sistema,<br>eu quero que o assistente virtual seja visível na interface como um personagem interativo,<br>para que eu possa acessá-lo rapidamente e ter uma experiência de interação mais engajadora. |
| **Critérios de Aceitação** | - **Dado que** o usuário está logado no sistema,<br>- **Quando** a interface principal é carregada,<br>- **Então** um personagem interativo representando o assistente virtual deve estar visível em um local fixo da tela.<br><br>- **Dado que** o personagem está visível,<br>- **Quando** o usuário clica nele,<br>- **Então** a janela de chat do assistente virtual deve ser aberta para interação. |
| **Rastreabilidade** | [RF38](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP09](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep09-criar-personagem-interativo-customizavel) – Criar Personagem Interativo Customizável |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

---

## [US42](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us42-notificacao-de-conteudos-mais-dificeis) – Notificação de Conteúdos Mais Difíceis

<div align="center"><strong>Tabela 44: US42</strong></div>

| Campo                | Descrição |
|----------------------|-----------|
| **ID**              | US42 |
| **Título**          | Notificação de Conteúdos Mais Difíceis |
| **História**        | **Como** um aluno no sistema educacional, **quero** saber em que conteúdo(s) eu ando tendo mais dificuldade de assimilamento e desempenho acadêmico(s), **para** focar melhor meus esforços de melhoria e minhas requisições de ajuda para tal onde for mais necessário num dado momento. |
| **Critérios de Aceitação** | - **Dado** que o aluno tenha desempenho significativamente abaixo da média pessoal em quaisquer conteúdos, <br>- **Quando** o sistema de análise de desempenho estiver analisando periodicamente as métricas de desempenho do aluno em suas disciplinas e o assistente virtual receber desse sistema que se encontrou esse tipo de valores de desempenho, <br>- **Então** o aluno deverá ser notificado sobre isto conforme as suas configurações de canais, frequência, tipo(s) de notificação etc. |
| **Rastreabilidade** | [RF42](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) | |
| **Épico Relacionado** | [EP27](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep27-notificar-aluno-sobre-dificuldades-em-conteudos) – Notificar Aluno sobre Dificuldades em Conteúdos |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

## US43 – Facilitar Interação entre Monitores, Professores e Alunos

<div align="center"><strong>Tabela 45: US43</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US43 |
| **Título**          | Facilitar Interação entre Monitores, Professores e Alunos |
| **História**        | Como um usuário do sistema educacional,<br>eu quero que o sistema facilite a comunicação entre monitores, professores e alunos, para que a troca de informações e apoio pedagógico seja mais eficiente. |
| **Critérios de Aceitação** | - Dado que o usuário acessa o sistema,<br>- Quando desejar interagir com outro perfil educacional,<br>- Então o sistema deve oferecer meios de comunicação integrados e acessíveis. |
| **Rastreabilidade** | [RF43](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP26](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep26-facilitar-comunicacao-via-chat-e-monitoria) – Facilitar Comunicação via Chat e Monitoria |

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
| **Rastreabilidade** | [RF44](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP26](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep26-facilitar-comunicacao-via-chat-e-monitoria) – Facilitar Comunicação via Chat e Monitoria |

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
| **Rastreabilidade** | [RF46](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP11](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep11-acompanhar-interacoes-e-progresso-do-usuario) – Acompanhar Interações e Progresso do Usuário |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## [US47](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us47-informacoes-sobre-horarios-e-locais-de-monitoria) – Informações sobre Horários e Locais de Monitoria

<div align="center"><strong>Tabela 49: US47</strong></div>

| Campo                | Descrição |
|----------------------|-----------|
| **ID**              | US47 |
| **Título**          | Informações sobre Horários e Locais de Monitoria |
| **História**        | **Como** um aluno no sistema educacional, **quero** ser informado sobre os horários e locais de monitoria **para** organizar minha agenda, meus estudos e seu planejamento (no) geral. |
| **Critérios de Aceitação** | - **Dado** que o aluno acesse a plataforma e navegue para a seção de Monitorias Disponíveis,<br>- **Quando** ele visualizar a lista de monitorias,<br>- **Então** deverá ver claramente o nome da disciplina, o monitor responsável, os horários disponíveis e os locais (online ou presencial) de cada monitoria.<br><br>- **Dado** que o aluno tenha acesso à sua agenda pessoal dentro do sistema, <br>- **Quando** ele selecionar uma monitoria (que tenha/venha a ter participação/presença marcável, a exemplo de uma tutoria valendo bonificação na nota do aluno em alguma disciplina com a presença confirmada) e confirmar sua participação, <br>- **Então** o sistema deverá adicionar automaticamente essa monitoria à sua agenda e, opcionalmente – conforme (as) configurações do próprio usuário –, enviar um lembrete antes do horário agendado.
| **Rastreabilidade** | [RF47](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) | |
| **Épico Relacionado** | [EP26](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep26-facilitar-comunicacao-via-chat-e-monitoria) – Facilitar Comunicação via Chat e Monitoria |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

## US49 – Análise Cognitiva e Apoio à Aprendizagem

<div align="center"><strong>Tabela 51: US49</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US49 |
| **Título**          | Análise Cognitiva e Apoio à Aprendizagem |
| **História**        | Como um aluno,<br>eu quero que o assistente virtual compreenda minha situação cognitiva, para que ele possa me ajudar de forma personalizada na aprendizagem. |
| **Critérios de Aceitação** | - Dado que o aluno interage com o assistente virtual,<br>- Quando o sistema identifica dificuldades cognitivas,<br>- Então ele deve oferecer suporte adaptado às necessidades do aluno. |
| **Rastreabilidade** | [RF49](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP10](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep10-analisar-dificuldades-cognitivas-e-sugerir-conteudos) – Analisar Dificuldades Cognitivas e Sugerir Conteúdos |

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
| **Rastreabilidade** | [RF50](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP27](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep27-fornecer-dados-ao-professor-sobre-dominio-e-comportamento) – Fornecer Dados ao Professor sobre Domínio e Comportamento |

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
| **Rastreabilidade** | [RF51](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP27](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep27-fornecer-dados-ao-professor-sobre-dominio-e-comportamento) – Fornecer Dados ao Professor sobre Domínio e Comportamento |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## Gravação da validação do documento

## Agradecimentos
O Grupo 03 agradece o apoio das ferramentas de Inteligência Artificial Generativa — **ChatGPT, GitHub Copilot, Google Gemini e DeepSeek** — na revisão gramatical e de estilo deste artigo. As tecnologias foram utilizadas para tornar o texto mais claro, objetivo e fácil de ler. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Referências

## Históricos de versão

| Versão | Data       | Descrição  | Autor(es)        | Revisor    |
|--------|------------|---------------------------------------------|----|---------------|
| 1.0    | 16/10/2025 | Criação do documento de Histórias de Usuário  | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)| [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.1    | 16/10/2025 | Criação das historias de usuario 7, 8, 9, 10, 12 e 17 | [Felipe Guimaraes](https://github.com/felipegf1)| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.2    | 18/10/2025 | Criação das historias de usuario 43, 44, 46, 49, 50 e 51 | [Arthur Guilherme](https://github.com/ArthurGuilher62)| [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.3    | 19/10/2025 | Correção dos hiperlinks das histórias de usuário, inclusão das etapas de participação e atualização do histórico de versões | [João Victor Pires](https://github.com/joaovpires) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.3    | 19/10/2025 | Correção por adição de *hiperlinks* das histórias de usuário, inclusão das etapas de participação e atualização do histórico de versões e dos agradecimentos | [João Felipe](https://github.com/MrBolt2005) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) <rb> [Vilmar José](https://github.com/VilmarFagundes) |
| 1.4    | 20/10/2025 | Criação e adição das histórias de usuário [US01 - Identificação e Autenticação de Usuários](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us01-identificacao-e-autenticacao-de-usuarios), [US02 - Visualizar e Gerenciar Perfil Individual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us02-visualizar-e-gerenciar-perfil-individual), [US11 - Exibir média geral da turma](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us11-exibir-media-geral-da-turma), [US13 - Configurar Alertas de Atividades Atrasadas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us13-configurar-alertas-de-atividades-atrasadas), [US28 - Gerenciar Banco de Questões do Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us28-gerenciar-banco-de-questoes-do-professor) e [US38 - Visualizar Personagem do Assistente Virtual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us38-visualizar-personagem-do-assistente-virtual) | [Vilmar José](https://github.com/VilmarFagundes) | [João Sapiência](https://github.com/JoaoSapiencia) |
| 1.5    | 18/10/2025 | Criação das historias de usuario 03, 04, 05, 16, 20, 25 e 26 | [Arthur Henrique](https://github.com/arthurhvieira1)| [Felipe Guimaraes](https://github.com/felipegf1) |
