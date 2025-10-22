## Introdução
Este documento detalha o processo de levantamento e especificação das Histórias de Usuário para o projeto **SAE (Sistema de Apoio Educacional)**, uma etapa essencial no **desenvolvimento ágil** do sistema. As histórias de usuário representam descrições breves e objetivas das funcionalidades do SAE sob a perspectiva do usuário final, destacando o valor que cada funcionalidade proporciona no contexto educacional, especialmente no apoio ao processo de aprendizagem por meio de um tutor inteligente.
Esse tutor inteligente é responsável por acompanhar individualmente os estudantes, monitorando seu desempenho, identificando dificuldades e oferecendo suporte personalizado para aprimorar o aprendizado e tornar a experiência educacional mais eficaz.

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da etapa da Histórias de Usuário, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) | Criação das historias de usuario [US43 – Facilitar Interação entre Monitores, Professores e Alunos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us43-facilitar-interacao-entre-monitores-professores-e-alunos), [US44 – Chat Síncrono para Interação a Distância](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us44-chat-sincrono-para-interacao-a-distancia), [US45 – Acompanhar Interações do Usuário com o Assistente Virtual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us45-acompanhar-interacoes-do-usuario-com-o-assistente-virtual), [US46 – Exibir Progresso do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us46-exibir-progresso-do-aluno), [US49 – Análise Cognitiva e Apoio à Aprendizagem](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us49-analise-cognitiva-e-apoio-a-aprendizagem), [US50 – Identificar Conhecimento do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us50-identificar-conhecimento-do-aluno) e [US51 – Identificar Comportamento Adequado do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us51-identificar-comportamento-adequado-do-aluno). Além da participação na validação na [Gravação 1](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#gravacao-1) |
| [Arthur Henrique](https://github.com/arthurhvieira1) | Criação das histórias de usuário [US03 - Mapeamento de Conceitos segundo a Teoria da Aprendizagem Significativa (TAS)](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us03-mapeamento-de-conceitos-segundo-a-teoria-da-aprendizagem-significativa-tas), [US04 - Alinhamento do Plano de Ensino ao AVA](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us04-alinhamento-do-plano-de-ensino-ao-ava), [US05 - Integração de Avaliações ao AVA](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us05-integracao-de-avaliacoes-ao-ava), [US16 - Índice de Conteúdos Ordenado por Porcentagem de Erros](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us16-indice-de-conteudos-ordenado-por-porcentagem-de-erros), [US20 - Configuração de Notificação de Prazos pelo Usuário](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us20-configuracao-de-notificacao-de-prazos-pelo-usuario), [US25 - Interação com Questões (Avaliação Informativa e Formativa)](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us25-interacao-com-questoes-avaliacao-informativa-e-formativa), [US26 - Assistência ao Professor no Módulo de Interação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us26-assistencia-ao-professor-no-modulo-de-interacao) e [US29 - Banco de Questões com Fontes Externas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us29-banco-de-questoes-com-fontes-externas). Além da participação na validação na [Gravação 2](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#gravacao-2) |
| [Felipe Guimaraes](https://github.com/felipegf1) | Criação das historias de usuario [US07 Visualizar Progresso do Aluno na Disciplina](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us07-visualizar-progresso-do-aluno-na-disciplina), [US08 - Exibir Progresso da Disciplina em Porcentagem](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us08-exibir-progresso-da-disciplina-em-porcentagem), [US09 - Visualizar Porcentagem de Acertos por Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us09-visualizar-porcentagem-de-acertos-por-conteudo), [US10 - Visualizar Porcentagem de Erros por Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us10-visualizar-porcentagem-de-erros-por-conteudo), [US12 - Exibir Média do Usuário Após Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us12-exibir-media-do-usuario-apos-atividade), [US17 - Assistir a uma Videoaula do Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us17-assistir-a-uma-videoaula-do-conteudo). Além da participação na validação na [Gravação 2](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#gravacao-2) |
| [João Felipe](https://github.com/MrBolt2005) | Criação das histórias de usuário [US14 - Seleção de Disciplinas Mais Fáceis](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us14-selecao-de-disciplinas-mais-faceis), [US23 – Cálculo do Desempenho do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us24-calculo-do-desempenho-do-aluno), [US30 – Direcionamento Sob Medida de Materiais aos Alunos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us30-direcionamento-sob-medida-de-materiais-aos-alunos), [US37 – Inferências com Lógica Fuzzy](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us37-inferencias-com-logica-fuzzy), [US41 – Notificação de Conteúdos Mais Difíceis ao Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us41-notificacao-de-conteudos-mais-dificeis-ao-aluno), [US42 - Notificação de Conteúdos Mais Difíceis ao Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us42-notificacao-de-conteudos-mais-dificeis-ao-professor) e [US47 – Informações sobre Horários e Locais de Monitoria](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us47-informacoes-sobre-horarios-e-locais-de-monitoria). Além da participação na validação na [Gravação 3](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#gravacao-3) |
| [João Sapiência](https://github.com/JoaoSapiencia) |  . Além da participação na validação na [Gravação 2](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#gravacao-2) e na [Gravação 3](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#gravacao-3) |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Histórias de Usuário e criação das histórias de usuário [US06 - Combinar Resultados Formais com Inferências Fuzzy](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us06-combinar-resultados-formais-com-inferencias-fuzzy), [US15 - Enviar Notificações para Revisão de Conteúdos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us15-enviar-notificacoes-para-revisao-de-conteudos), [US18 - Definir Forma Preferida de Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us18-definir-forma-preferida-de-notificacao), [US19 - Enviar Notificação sobre Prazo de Entrega de Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us19-enviar-notificacao-sobre-prazo-de-entrega-de-atividade), [US21 - Exibir Dados e Informações Analíticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us21-exibir-dados-e-informacoes-analiticas), [US22 - Gerar Análises em Tempo Real com Gráficos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us22-gerar-analises-em-tempo-real-com-graficos), [US34 - Centralizar Informações de Atividades e Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us34-centralizar-informacoes-de-atividades-e-desempenho) e [US35 - Criar Personagem Antropomórfico para Interação Direta](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us35-criar-personagem-antropomorfico-para-interacao-direta). Além da participação na validação na [Gravação 1](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#gravacao-1) |
| [Vilmar José](https://github.com/VilmarFagundes) | Criação das histórias de usuário [US01 - Identificação e Autenticação de Usuários](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us01-identificacao-e-autenticacao-de-usuarios), [US02 - Visualizar e Gerenciar Perfil Individual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us02-visualizar-e-gerenciar-perfil-individual), [US11 - Exibir média geral da turma](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us11-exibir-media-geral-da-turma), [US13 - Configurar Alertas de Atividades Atrasadas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us13-configurar-alertas-de-atividades-atrasadas), [US28 - Gerenciar Banco de Questões do Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us28-gerenciar-banco-de-questoes-do-professor), [US38 - Visualizar Personagem do Assistente Virtual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us38-visualizar-personagem-do-assistente-virtual) e [US40 – Sugerir Questões Pós-Videoaula](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us40-sugerir-questoes-pos-videoaula). Além da participação na validação na [Gravação 1](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#gravacao-1) |

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

---

## [US03](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us03-mapeamento-de-conceitos-segundo-a-teoria-da-aprendizagem-significativa-tas) - Mapeamento de Conceitos segundo a Teoria da Aprendizagem Significativa (TAS)

<div align="center"><strong>Tabela 5: US03</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US03 |
| **Título** | Mapeamento de Conceitos segundo a TAS |
| **História** | Como um coordenador pedagógico,<br>eu quero mapear conceitos do conteúdo respeitando a hierarquia da Teoria da Aprendizagem Significativa (TAS),<br>para que pré-requisitos e relações entre tópicos orientem atividades e recomendações. |
| **Critérios de Aceitação** | - Dado que defino conceitos e pré-requisitos,<br>- Quando salvo o mapa conceitual,<br>- Então o sistema deve representar a hierarquia (do mais inclusivo ao menos inclusivo) e validar ciclos inconsistentes.<br><br>- Dado que o aluno possui lacunas em pré-requisitos,<br>- Quando ele acessa um tópico avançado,<br>- Então o sistema deve recomendar estudo dos conceitos base antes de prosseguir.<br><br>- Dado o mapa conceitual publicado,<br>- Quando o professor cria atividades,<br>- Então o sistema deve sugerir questões alinhadas aos conceitos e níveis hierárquicos. |
| **Rastreabilidade** | [RF03](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

## [US04](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us04-alinhamento-do-plano-de-ensino-ao-ava) - Alinhamento do Plano de Ensino ao AVA

<div align="center"><strong>Tabela 6: US04</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US04 |
| **Título** | Alinhamento do Plano de Ensino ao AVA |
| **História** | Como um professor,<br>eu quero agregar o processo formal de avaliação do Plano de Ensino ao ambiente virtual,<br>para que prazos, pesos e critérios avaliativos fiquem sincronizados com as atividades online. |
| **Critérios de Aceitação** | - Dado que importo o Plano de Ensino (prazos, pesos, critérios),<br>- Quando confirmo o alinhamento,<br>- Então o sistema deve criar/exigir as avaliações no AVA com as configurações correspondentes.<br><br>- Dado que há alterações no Plano de Ensino,<br>- Quando publico uma nova versão,<br>- Então o calendário, pesos e rubricas do AVA devem ser atualizados mantendo histórico de versões.<br><br>- Dado o Plano de Ensino em vigor,<br>- Quando os alunos acessam a disciplina,<br>- Então devem ver cronograma, pesos e critérios consolidados em uma única visão. |
| **Rastreabilidade** | [RF04](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

## [US05](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us05-integracao-de-avaliacoes-ao-ava) - Integração de Avaliações ao AVA

<div align="center"><strong>Tabela 7: US05</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US05 |
| **Título** | Integração de Avaliações ao AVA |
| **História** | Como um professor,<br>eu quero integrar as avaliações (provas, atividades, rubricas) diretamente ao AVA,<br>para que a criação, aplicação, correção e lançamento de notas ocorram em um fluxo único. |
| **Critérios de Aceitação** | - Dado que crio uma avaliação no módulo de avaliações,<br>- Quando eu a publico,<br>- Então ela deve aparecer automaticamente no AVA com prazos, tentativas e rubricas configuradas.<br><br>- Dado que os alunos submetem respostas,<br>- Quando a avaliação encerra,<br>- Então o sistema deve disponibilizar correção (automática ou por rubrica), feedback e lançar notas no boletim da disciplina.<br><br>- Dado que há ajustes após a publicação,<br>- Quando atualizo instruções, rubrica ou prazo,<br>- Então o AVA deve refletir as mudanças e notificar os alunos. |
| **Rastreabilidade** | [RF05](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
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
| **Critérios de Aceitação** | - **Dado que** o usuário acessa seu painel de "Configurações de Notificação",<br>- **Quando** ele seleciona a opção "Atividades Atrasadas",<br>- **Então** o sistema deve exibir opções de tempo (ex: "1 dia após o prazo", "A cada 3 dias", "Não notificar").<br><br>- **Dado que** o usuário salvou sua preferência de tempo,<br>- **Quando** uma atividade ficar atrasada pelo período configurado,<br>- **Então** o sistema deve enviar um alerta pelo canal preferido (definido na US18). |
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

## [US16](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us16-indice-de-conteudos-ordenado-por-porcentagem-de-erros) - Índice de Conteúdos Ordenado por Porcentagem de Erros

<div align="center"><strong>Tabela 18: US16</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US16 |
| **Título** | Índice de Conteúdos Ordenado por Porcentagem de Erros |
| **História** | Como um aluno,<br>eu quero visualizar um índice de conteúdos ordenado pela porcentagem de erros,<br>para que eu identifique facilmente quais tópicos tenho mais dificuldade e priorize meus estudos nesses assuntos. |
| **Critérios de Aceitação** | - Dado que o aluno acessa a página de desempenho,<br>- Quando o sistema carrega o índice de conteúdos,<br>- Então os conteúdos devem ser listados em ordem decrescente de porcentagem de erros (do maior para o menor).<br><br>- Dado que dois conteúdos tenham a mesma porcentagem de erros,<br>- Quando o sistema exibe o índice,<br>- Então deve aplicar ordenação secundária alfabética pelo nome do conteúdo.<br><br>- Dado que o aluno clique em um conteúdo no índice,<br>- Quando ele acessa os detalhes,<br>- Então o sistema deve exibir gráficos e atividades relacionadas a esse conteúdo específico. |
| **Rastreabilidade** | [RF16](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
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

## [US20](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us20-configuracao-de-notificacao-de-prazos-pelo-usuario) - Configuração de Notificação de Prazos pelo Usuário

<div align="center"><strong>Tabela 22: US20</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US20 |
| **Título** | Configuração de Notificação de Prazos pelo Usuário |
| **História** | Como um aluno,<br>eu quero escolher quando quero receber notificações sobre a proximidade da data de entrega de uma atividade,<br>para que eu possa me organizar conforme minha rotina e evitar atrasos. |
| **Critérios de Aceitação** | - Dado que o aluno acessa as configurações de notificações,<br>- Quando ele seleciona o tempo de antecedência (ex: 1 dia, 3 dias, 1 semana),<br>- Então o sistema deve salvar a preferência e exibir uma confirmação visual de que a configuração foi atualizada.<br><br>- Dado que uma atividade está próxima do prazo configurado,<br>- Quando a antecedência definida é atingida,<br>- Então o sistema deve enviar uma notificação via canal escolhido (e-mail, push, ou WhatsApp).<br><br>- Dado que o aluno desative as notificações,<br>- Quando salvar a configuração,<br>- Então o sistema deve deixar de enviar alertas até que o recurso seja reativado. |
| **Rastreabilidade** | [RF20](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
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

## [US23](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us23-calculo-do-desempenho-do-aluno) – Cálculo do Desempenho do Aluno

<div align="center"><strong>Tabela 25: US23</strong></div>

| Campo                | Descrição |
|----------------------|-----------|
| **ID**              | US23 |
| **Título**          | Cálculo do Desempenho do Aluno |
| **História**        | **Como** um usuário do sistema educacional, **quero** visualizar tanto o quão bem minha turma no geral ou alunos individuais – eu mesmo, se for um aluno, ou qualquer aluno, se eu for o professor –, está se saindo numa disciplina, como também como se chegou a esse resultado, **para** saber mais especificamente os pontos fortes e fracos em particular no exercício na disciplina, e quais deles estão sendo mais influentes no próprio desempenho geral finalmente obtido. |
| **Critérios de Aceitação** | - **Dado** que o usuário acesse a página de uma turma em que esteja matriculado ou lecione, <br>- **Quando** abrir as informações de desempenho individual e geral dessa turma, <br>- **Então** deve visualizar esses desempenhos, mais as suas métricas de computação e os métodos usados para os próprios cálculos. <br><br>- **Dado** que o usuário tenha configurado para ser notificado sobre tal, <br>- **Quando** houver atualizações significantes sobre métricas de computação de desempenho que ele for escolher, <br>- **Então** deverá ser notificado sobre isto pelo sistema nos canais desejados. |
| **Rastreabilidade** | [RF23](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) | |
| **Épico Relacionado** | [EP15](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep15-calcular-desempenho-do-aluno-com-base-em-metricas-definidas) – Calcular Desempenho do Aluno com Base em Métricas Definidas |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

## US24 – Criar e Organizar Questões Interativas

<div align="center"><strong>Tabela 26: US52</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US24 |
| **Título** | Criar e Organizar Questões Interativas |
| **História** | Como um professor,<br>eu quero criar e organizar questões interativas no sistema,<br>para que eu possa montar atividades e avaliações que apoiem o ensino-aprendizagem dos alunos. |
| **Critérios de Aceitação** | - **Dado que** o professor está na área do "Banco de Questões".<br>- **Quando** ele seleciona a opção "Criar Nova Questão Interativa".<br>- **Então** o sistema deve apresentar um formulário para ele definir o tipo de questão (ex: múltipla escolha, V/F, preencher lacuna), o enunciado, as opções e a resposta correta.<br><br>- **Dado que** o professor está criando uma questão.<br>- **Quando** ele preenche os campos da questão.<br>- **Então** o sistema deve exigir que ele associe a questão a um conteúdo/tópico da disciplina para fins de organização.<br><br>- **Dado que** o professor está no seu "Banco de Questões".<br>- **Quando** ele filtra por um conteúdo específico.<br>- **Então** o sistema deve exibir apenas as questões interativas organizadas sob aquele conteúdo. |
| **Rastreabilidade** | [RF24](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP22](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep22-gerenciar-banco-de-questoes-de-professores-e-outras-fontes) – Gerenciar Banco de Questões de Professores e Outras Fontes |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

## [US25](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us25-interacao-com-questoes-avaliacao-informativa-e-formativa) - Interação com Questões (Avaliação Informativa e Formativa)

<div align="center"><strong>Tabela 27: US25</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US25 |
| **Título** | Interação com Questões (Avaliação Informativa e Formativa) |
| **História** | Como um aluno,<br>eu quero interagir com questões que avaliem meu conhecimento informativo e formativo,<br>para aprender com feedback imediato e acompanhar minha evolução. |
| **Critérios de Aceitação** | - Dado que o aluno responde a uma questão,<br>- Quando submete a resposta,<br>- Então deve receber feedback imediato com explicação, referência de estudo e sugestão de próximo passo (formativa).<br><br>- Dado um conjunto de questões de um tópico,<br>- Quando o aluno conclui o bloco,<br>- Então o sistema deve mostrar resumo com acertos, erros e recomendações de reforço (informativa + formativa).<br><br>- Dado que o aluno revisite uma questão,<br>- Quando visualizar o histórico,<br>- Então deve ver suas tentativas, feedbacks e progresso ao longo do tempo. |
| **Rastreabilidade** | [RF25](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

## [US26](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us26-assistencia-ao-professor-no-modulo-de-interacao) - Assistência ao Professor no Módulo de Interação

<div align="center"><strong>Tabela 28: US26</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US26 |
| **Título** | Assistência ao Professor no Módulo de Interação |
| **História** | Como um professor,<br>eu quero receber assistência do SAE para planejar, aplicar e revisar atividades no módulo de interação,<br>para otimizar o tempo e melhorar a qualidade pedagógica. |
| **Critérios de Aceitação** | - Dado que informo objetivos de aprendizagem e o conteúdo,<br>- Quando solicito sugestões,<br>- Então o sistema deve recomendar tipos de questões, níveis de dificuldade e materiais de apoio coerentes.<br><br>- Dado que a turma concluiu uma atividade,<br>- Quando abro o relatório do módulo,<br>- Então devo ver estatísticas por questão/tópico, principais erros, padrões de confusão e sugestões de intervenção.<br><br>- Dado que tenho pouco tempo para preparar uma aula,<br>- Quando aciono o assistente do SAE,<br>- Então ele deve gerar um roteiro com sequência de atividades e checkpoints avaliativos. |
| **Rastreabilidade** | [RF26](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
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

## [US29](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us29-banco-de-questoes-com-fontes-externas) - Banco de Questões com Fontes Externas

<div align="center"><strong>Tabela 31: US29</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US29 |
| **Título** | Banco de Questões com Fontes Externas |
| **História** | Como um professor,<br>eu quero que o banco de questões do sistema contenha também questões de outras origens (como bancos públicos, APIs externas ou importação via arquivo),<br>para que eu tenha acesso a uma base de questões mais ampla e diversificada para compor minhas avaliações. |
| **Critérios de Aceitação** | - Dado que o professor acesse o módulo de banco de questões,<br>- Quando ele selecionar a opção “Importar Questões”,<br>- Então o sistema deve permitir importar arquivos em formato compatível (CSV, XML, JSON, entre outros) contendo questões externas.<br><br>- Dado que o sistema esteja integrado a uma API pública de questões,<br>- Quando o professor realizar uma busca por tema,<br>- Então o sistema deve exibir resultados vindos tanto do banco interno quanto das fontes externas configuradas.<br><br>- Dado que uma questão externa seja importada,<br>- Quando o professor a editar ou utilizar,<br>- Então o sistema deve registrar a origem e permitir personalização completa do conteúdo (enunciado, alternativas, tags). |
| **Rastreabilidade** | [RF29](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP23 – Gerenciar Banco de Questões de Professores e Outras Fontes](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep23-gerenciar-banco-de-questoes-de-professores-e-outras-fontes) |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

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

## US31 – Organização de Materiais por Tópicos de Conteúdo

<div align="center"><strong>Tabela 33: US31</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US31 |
| **Título** | Organização de Materiais por Tópicos de Conteúdo |
| **História** | Como um aluno,<br>eu quero visualizar os materiais de estudo (vídeos, textos, links) agrupados por tópicos de conteúdo da disciplina,<br>para que eu possa acessar facilmente os recursos relevantes para o que estou estudando no momento. |
| **Critérios de Aceitação** | - **Dado que** o professor postou materiais e os associou a tópicos específicos (ex: "Vídeo A" ao "Tópico 1", "Texto B" ao "Tópico 2").<br>- **Quando** o aluno acessa a página do "Tópico 1" da disciplina.<br>- **Então** o sistema deve exibir o "Vídeo A" e não deve exibir o "Texto B".<br><br>- **Dado que** o aluno está na página principal da disciplina.<br>- **Quando** ele visualiza a estrutura de conteúdos.<br>- **Então** ele deve ver os materiais de estudo (links, arquivos) listados dentro de seus respectivos tópicos. |
| **Rastreabilidade** | [RF31](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP23](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep23-gerenciar-banco-de-questoes-de-professores-e-outras-fontes) – Gerenciar Banco de Questões de Professores e Outras Fontes |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

## US32 – Filtrar Banco de Questões por Conteúdo

<div align="center"><strong>Tabela 34: US32</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US32 |
| **Título** | Filtrar Banco de Questões por Conteúdo |
| **História** | Como um professor,<br>eu quero que o banco de questões esteja separado por conteúdo,<br>para que eu possa encontrar e selecionar rapidamente as questões de um tópico específico ao montar uma atividade. |
| **Critérios de Aceitação** | - **Dado que** o professor acessa o "Banco de Questões" para criar uma atividade.<br>- **Quando** ele visualiza a interface de seleção de questões.<br>- **Então** o sistema deve apresentar opções para filtrar as questões por conteúdo ou tópico (ex: por disciplina, depois por capítulo).<br><br>- **Dado que** o professor selecionou um filtro de conteúdo (ex: "Tópico 3").<br>- **Quando** a lista de questões é exibida.<br>- **Então** o sistema deve mostrar apenas as questões previamente associadas ao "Tópico 3". |
| **Rastreabilidade** | [RF32](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP23](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep23-gerenciar-banco-de-questoes-de-professores-e-outras-fontes) – Gerenciar Banco de Questões de Professores e Outras Fontes |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

## US33 – Integração com Softwares Educacionais Externos

<div align="center"><strong>Tabela 35: US33</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US33 |
| **Título** | Integração com Softwares Educacionais Externos (AVAs) |
| **História** | Como um administrador do sistema,<br>eu quero que o SAE se integre a outros softwares educacionais, como AVAs (Ambientes Virtuais de Aprendizagem) existentes,<br>para que haja uma sincronização de dados (listas de alunos, notas) e se evite a duplicação de trabalho manual. |
| **Critérios de Aceitação** | - **Dado que** o administrador está na área de "Configurações" do SAE.<br>- **Quando** ele acessa a seção "Integrações" e seleciona um AVA (ex: Moodle).<br>- **Então** o sistema deve permitir a inserção de credenciais de API para estabelecer a conexão.<br><br>- **Dado que** uma integração com um AVA está ativa.<br>- **Quando** um novo aluno é matriculado no AVA.<br>- **Então** o sistema SAE deve ser capaz de sincronizar e criar automaticamente o perfil desse aluno.<br><br>- **Dado que** uma nota final é gerada no SAE.<br>- **Quando** a sincronização de notas está habilitada.<br>- **Então** o sistema deve ser capaz de enviar essa nota para o quadro de notas do AVA correspondente. |
| **Rastreabilidade** | [RF33](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | |
<br>

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

## [US34](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us34-centralizar-informacoes-de-atividades-e-desempenho) - Centralizar Informações de Atividades e Desempenho

<div align="center"><strong>Tabela 36: US34</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US34 |
| **Título** | Centralizar Informações de Atividades e Desempenho |
| **História** | Como um **professor ou monitor**,<br>eu quero **acessar em um único local as informações sobre as atividades e o desempenho dos alunos**,<br>para que eu possa **reduzir o esforço de acompanhamento e análise de resultados**. |
| **Critérios de Aceitação** | - **Dado que** o professor ou monitor está autenticado no sistema,<br>- **Quando** ele acessa o painel de desempenho,<br>- **Então** o sistema deve exibir em uma única interface as informações de atividades, notas e progresso dos alunos.<br><br>- **Dado que** o sistema recebe atualizações sobre o desempenho dos alunos,<br>- **Quando** novas informações são registradas,<br>- **Então** o painel deve atualizar automaticamente os dados centralizados. |
| **Rastreabilidade** | [RF34](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP25](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep25-centralizar-informacoes-educacionais) – Centralizar Informações Educacionais |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---


## [US35](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us35-criar-personagem-antropomorfico-para-interacao-direta) - Criar Personagem Antropomórfico para Interação Direta

<div align="center"><strong>Tabela 37: US35</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US35 |
| **Título** | Criar Personagem Antropomórfico para Interação Direta |
| **História** | Como um estudante,<br>eu quero interagir com um personagem antropomórfico dentro do sistema educacional,<br>para que a comunicação com o assistente seja mais natural, envolvente e amigável. |
| **Critérios de Aceitação** | - **Dado que** o estudante acessa o assistente educacional,<br>- **Quando** ele inicia uma interação,<br>- **Então** o sistema deve exibir um personagem antropomórfico que represente visualmente o assistente.<br><br>- **Dado que** o estudante realiza perguntas ou solicitações,<br>- **Quando** o personagem responde,<br>- **Então** ele deve utilizar expressões e comportamentos condizentes com o contexto da interação (ex: animações faciais, gestos ou mudanças de tom).<br><br>- **Dado que** o estudante continua utilizando o sistema,<br>- **Quando** há troca de contexto (ex: mudança de disciplina ou modo de estudo),<br>- **Então** o personagem deve adaptar seu comportamento ou aparência conforme a situação. |
| **Rastreabilidade** | [RF35](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP09](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep09-criar-personagem-interativo-customizavel) – Criar Personagem Interativo Customizável |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## US36 – Analisar Situação de Aprendizagem na Interação

<div align="center"><strong>Tabela 38: US36</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US36 |
| **Título** | Analisar Situação de Aprendizagem na Interação |
| **História** | Como um aluno,<br>eu quero que a minha interação com o assistente virtual (ITA) ajude o sistema a entender minha real situação de aprendizagem (o que eu sei e o que eu não sei),<br>para que ele possa me oferecer ajuda e sugestões que sejam realmente úteis e personalizadas para minha dificuldade. |
| **Critérios de Aceitação** | - **Dado que** o aluno faz uma pergunta vaga ao assistente virtual (ex: "Me explique 'TAS'").<br>- **Quando** o assistente não tem certeza do nível de conhecimento do aluno sobre o tema.<br>- **Então** o assistente deve fazer perguntas de sondagem para compreender a situação (ex: "Você já entendeu o que são 'subsunssores' ou quer começar pelo básico?").<br><br>- **Dado que** o aluno erra uma questão sugerida pelo assistente durante o chat.<br>- **Quando** o assistente analisa essa interação.<br>- **Então** o sistema deve usar essa informação para (compreender a situação) e reajustar a próxima sugestão, focando no ponto de dificuldade. |
| **Rastreabilidade** | [RF36](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP10](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep10-analisar-dificuldades-cognitivas-e-sugerir-conteudos) – Analisar Dificuldades Cognitivas e Sugerir Conteúdos |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

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

## US39 – Customizar o Assistente Virtual

<div align="center"><strong>Tabela 41: US39</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US39 |
| **Título** | Customizar o Assistente Virtual |
| **História** | Como um usuário do sistema,<br>eu quero poder customizar a aparência ou o comportamento do assistente virtual (ITA),<br>para que minha experiência de interação seja mais pessoal e agradável. |
| **Critérios de Aceitação** | - **Dado que** o usuário está logado no sistema.<br>- **Quando** ele acessa a área de "Configurações" ou "Preferências" do assistente virtual.<br>- **Então** o sistema deve exibir as opções de customização disponíveis (ex: mudar cor, avatar, nome de exibição).<br><br>- **Dado que** o usuário escolheu uma nova aparência (ex: um novo avatar).<br>- **Quando** ele salva a alteração.<br>- **Então** o assistente virtual deve aparecer imediatamente com a aparência selecionada em toda a interface. |
| **Rastreabilidade** | [RF39](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP09](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep09-criar-personagem-interativo-customizavel) – Criar Personagem Interativo Customizável |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

## [US40](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us40-sugerir-questoes-pos-videoaula) – Sugerir Questões Pós-Videoaula

<div align="center"><strong>Tabela 42: US40</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US40 |
| **Título** | Sugerir Questões Pós-Videoaula |
| **História** | Como um aluno, eu quero que o assistente virtual me sugira questões sobre o conteúdo logo após eu assistir a uma videoaula, para que eu possa testar meu entendimento e reforçar o que acabei de aprender. |
| **Critérios de Aceitação** | - **Dado que** oo aluno terminou de assistir a uma videoaula (marcada como 'concluída').<br>- **Quando** ele interage com o assistente virtual ou retorna à página principal do conteúdo.<br>- **Então** o assistente deve proativamente oferecer a opção de responder a questões de reforço sobre aquele tópico.<br><br>- **Dado que** o aluno aceita a sugestão.<br>- **Quando** ele responde às questões.<br>- **Então** o sistema deve fornecer feedback imediato sobre seus acertos e erros. |
| **Rastreabilidade** | [RF40](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP21](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep21-gerar-questoes-baseadas-em-video-aulas) – Gerar Questões Baseadas em Vídeo Aulas |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar Fagundes</a></strong></div>

---

## [US41](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us41-notificacao-de-conteudos-mais-dificeis-ao-aluno) – Notificação de Conteúdos Mais Difíceis ao Aluno

<div align="center"><strong>Tabela 43: US41</strong></div>

| Campo                | Descrição |
|----------------------|-----------|
| **ID**              | US41 |
| **Título**          | Notificação de Conteúdos Mais Difíceis ao Aluno |
| **História**        | **Como** um aluno no sistema educacional, **quero** saber em que conteúdo(s) eu ando tendo mais dificuldade de assimilamento e desempenho acadêmico(s), **para** focar melhor meus esforços de melhoria e minhas requisições de ajuda para tal onde for mais necessário num dado momento. |
| **Critérios de Aceitação** | - **Dado** que o aluno tenha desempenho significativamente abaixo da média pessoal em quaisquer conteúdos, <br>- **Quando** o sistema de análise de desempenho estiver analisando periodicamente as métricas de desempenho do aluno em suas disciplinas e o assistente virtual receber desse sistema que se encontrou esse tipo de valores de desempenho, <br>- **Então** o aluno deverá ser notificado sobre isto conforme as suas configurações de canais, frequência, tipo(s) de notificação etc. |
| **Rastreabilidade** | [RF41](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) | |
| **Épico Relacionado** | [EP27](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep27-notificar-aluno-sobre-dificuldades-em-conteudos) – Notificar Aluno sobre Dificuldades em Conteúdos |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

## [US42](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us42-notificacao-de-conteudos-mais-dificeis-ao-professor) - Notificação de Conteúdos Mais Difíceis ao Professor

<div align="center"><strong>Tabela 44: US42</strong></div>

| Campo                | Descrição |
|----------------------|-----------|
| **ID**              | US42 |
| **Título**          | Notificação de Conteúdos Mais Difíceis ao Professor |
| **História**        | **Como** um professor no sistema educacional, **quero** saber em quais conteúdos e/ou suas partes os alunos estão tendo mais dificuldade de assimilamento e desempenho acadêmico(s), **para** que eu possa planejar melhor minhas aulas, intervenções pedagógicas e apoio direcionado onde for mais necessário num dado momento. |
| **Critérios de Aceitação** | - **Dado** que os alunos tenham desempenho significativamente abaixo da média geral da turma em quaisquer conteúdos, <br>- **Quando** o sistema de análise de desempenho estiver analisando periodicamente as métricas de desempenho dos alunos em suas disciplinas e o assistente virtual receber desse sistema que se encontrou esse tipo de valores de desempenho, <br>- **Então** o professor deverá ser notificado sobre isto conforme as suas configurações de canais, frequência, tipo(s) de notificação etc. |
| **Rastreabilidade** | [RF42](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) | |
| **Épico Relacionado** | [EP28](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep28-notificar-professor-sobre-dificuldades-em-conteudos) – Notificar Professor sobre Dificuldades em Conteúdos |

<div align="center"><strong>Autoria de <a href="https://github.com/MrBolt2005">João Felipe</a></strong></div>

---

## [US43](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us43-facilitar-interacao-entre-monitores-professores-e-alunos) – Facilitar Interação entre Monitores, Professores e Alunos

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

## [US44](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us44-chat-sincrono-para-interacao-a-distancia) – Chat Síncrono para Interação a Distância

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

## [US45](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us45-acompanhar-interacoes-do-usuario-com-o-assistente-virtual) – Acompanhar Interações do Usuário com o Assistente Virtual

<div align="center"><strong>Tabela 47: US45</strong></div>

| Campo                | Descrição |
|---------------------|-----------|
| **ID**              | US45 |
| **Título**          | Acompanhar Interações do Usuário com o Assistente Virtual |
| **História**        | Como um usuário do sistema educacional,<br>eu quero que o assistente virtual acompanhe e registre minhas interações,<br>para que ele possa oferecer respostas mais personalizadas e melhorar a experiência de aprendizagem. |
| **Critérios de Aceitação** | - Dado que o usuário interage com o assistente virtual,<br> - Quando o usuário realiza uma ação ou faz uma pergunta,<br> - Então o sistema deve registrar e acompanhar essas interações.<br> - E o assistente deve utilizar essas informações para adaptar as respostas e melhorar as futuras interações. |
| **Rastreabilidade** | [RF45](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP11](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep11-acompanhar-interacoes-e-progresso-do-usuario) – Acompanhar Interações e Progresso do Usuário |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

## [US46](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us46-exibir-progresso-do-aluno) – Exibir Progresso do Aluno

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

## US48 – Orientação Pedagógica Individualizada pelo Assistente Virtual

<div align="center"><strong>Tabela 50: US48</strong></div>

| Campo | Descrição |
|-------|------------|
| **ID** | US48 |
| **Título** | Orientação Pedagógica Individualizada pelo Assistente Virtual |
| **História** | Como um aluno,<br>eu quero que o assistente virtual (ITA) me forneça orientações de estudo personalizadas,<br>para que a ajuda seja baseada no meu conhecimento atual (TAS) e também alinhada com a metodologia definida pelo meu professor. |
| **Critérios de Aceitação** | - **Dado que** o professor configurou uma abordagem didática específica para um tópico (ex: "ensinar 'Frações' usando exemplos visuais").<br>- **Quando** o aluno pedir ajuda ao assistente virtual sobre "Frações".<br>- **Então** o assistente deve priorizar a orientação usando exemplos visuais, respeitando o "desejo didático" do docente.<br><br>- **Dado que** o aluno demonstrou não dominar um conceito pré-requisito (TAS).<br>- **Quando** ele pede ajuda sobre um tópico avançado que depende desse pré-requisito.<br>- **Então** o assistente deve primeiro fornecer orientação para reforçar o conceito-base antes de avançar, garantindo a aprendizagem significativa.<br><br>- **Dado que** o aluno está com dificuldades específicas (ex: alto índice de erro em "Tipo X").<br>- **Quando** ele solicita orientação sobre o conteúdo geral.<br>- **Então** o assistente deve individualizar a ajuda, focando nos pontos onde o aluno apresenta maior dificuldade. |
| **Rastreabilidade** | [RF48](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Épico Relacionado** | [EP08](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep08-oferecer-assistencia-personalizada-a-alunos-e-professores) – Oferecer Assistência Personalizada a Alunos e Professores |

<div align="center"><strong>Autoria de <a href="https://github.com/JoaoSapiencia">João Sapiência</a></strong></div>

---

## [US49](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us49-analise-cognitiva-e-apoio-a-aprendizagem) – Análise Cognitiva e Apoio à Aprendizagem

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

## [US50](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us50-identificar-conhecimento-do-aluno) – Identificar Conhecimento do Aluno

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

## [US51](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us51-identificar-comportamento-adequado-do-aluno) – Identificar Comportamento Adequado do Aluno

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

## Gravações da Validação do Documento

### Gravação 1
A Tabela 54 mostra os participantes do grupo envolvidos na validação.

<div align="center"><strong>Tabela 54: Participantes envolvidos</strong></div>

| Nome |
|------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005)   |
| [Vilmar José](https://github.com/VilmarFagundes)       |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

A Tabela 55 apresenta as informações do usuário que participou da etapa de validação, incluindo seu nome e dados sobre a gravação, como data, hora e local.

<div align="center"><strong>Tabela 55: Usuário Real e Informações da Gravação</strong></div>

| Nome | Data | Hora | Local|
|-------------------------|-----------------|-----------------|------------------|
| Yzabella Miranda | 21/10/2025 | 11:00 | Faculdade de Ciências e Tecnologias em Engenharia – FCTE/UnB |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

Além disso, a gravação da validação conferida em: [https://youtu.be/G6XRiBhnWI8?si=zb9n7M_hhYv8x2UO](https://youtu.be/G6XRiBhnWI8?si=zb9n7M_hhYv8x2UO).

---

### Gravação 2
A Tabela 56 mostra os participantes do grupo envolvidos na validação.

<div align="center"><strong>Tabela 56: Participantes envolvidos</strong></div>

| Nome |
|------|
| [Arthur Henrique](https://github.com/arthurhvieira1) |
| [Felipe Guimaraes](https://github.com/felipegf1)   |
| [João Sapiência](https://github.com/JoaoSapiencia)       |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

A Tabela 57 apresenta as informações do usuário que participou da etapa de validação, incluindo seu nome e dados sobre a gravação, como data, hora e local.

<div align="center"><strong>Tabela 57: Usuário Real e Informações da Gravação</strong></div>

| Nome | Data | Hora | Local|
|-------------------------|-----------------|-----------------|------------------|
| João Igor | 21/10/2025 | 11:00 | Faculdade de Ciências e Tecnologias em Engenharia – FCTE/UnB |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

Além disso, a gravação da validação conferida em: [Link no Youtube](https://www.youtube.com/watch?v=tFK8LEWU538&t)

---

### Gravação 3
A Tabela 58 mostra os participantes do grupo envolvidos na validação.

<div align="center"><strong>Tabela 58: Participantes envolvidos</strong></div>

| Nome |
|------|
| [João Felipe](https://github.com/MrBolt2005)   |
| [João Sapiência](https://github.com/JoaoSapiencia)       |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

A Tabela 59 apresenta as informações do usuário que participou da etapa de validação, incluindo seu nome e dados sobre a gravação, como data, hora e local.

<div align="center"><strong>Tabela 59: Usuário Real e Informações da Gravação</strong></div>

| Nome | Data | Hora | Local|
|-------------------------|-----------------|-----------------|------------------|
| Cibelly Lourenço | 21/10/2025 | 17:00 | Faculdade de Ciências e Tecnologias em Engenharia – FCTE/UnB |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

Além disso, a gravação da validação conferida em: [https://youtu.be/LPax-bLDhYw?si=uShTjdpKJhNuvm45](https://youtu.be/LPax-bLDhYw?si=uShTjdpKJhNuvm45). Sendo que até o minuto 9:41 corresponde à validação da História de Usuário.

## Agradecimentos
O Grupo 03 agradece o apoio das ferramentas de Inteligência Artificial Generativa — **ChatGPT, GitHub Copilot, Google Gemini e DeepSeek** — na revisão gramatical e de estilo deste artigo. As tecnologias foram utilizadas para tornar o texto mais claro, objetivo e fácil de ler. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Referências

SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 15. Disponível em: [Requisitos_Aula 15](../arquivos/backlog_aula.pdf). Acesso em: 21 outubro 2025.

Roger S. Pressman – Engenharia de Software Uma Abordagem Profissional - Cap. 3. Disponível em: [Engenharia de Software Uma Abordagem Profissional](../arquivos/desenvolvimento_Agil.pdf). Acesso em: 21 outubro 2025.



## Históricos de versão

| Versão | Data       | Descrição  | Autor(es)        | Revisor    |
|--------|------------|---------------------------------------------|----|---------------|
| 1.0    | 16/10/2025 | Criação do documento de Histórias de Usuário  | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)| [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.1    | 16/10/2025 | Criação das historias de usuario [US06 - Combinar Resultados Formais com Inferências Fuzzy](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us06-combinar-resultados-formais-com-inferencias-fuzzy), [US15 - Enviar Notificações para Revisão de Conteúdos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us15-enviar-notificacoes-para-revisao-de-conteudos), [US18 - Definir Forma Preferida de Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us18-definir-forma-preferida-de-notificacao), [US19 - Enviar Notificação sobre Prazo de Entrega de Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us19-enviar-notificacao-sobre-prazo-de-entrega-de-atividade), [US21 - Exibir Dados e Informações Analíticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us21-exibir-dados-e-informacoes-analiticas), [US22 - Gerar Análises em Tempo Real com Gráficos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us22-gerar-analises-em-tempo-real-com-graficos), [US34 - Centralizar Informações de Atividades e Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us34-centralizar-informacoes-de-atividades-e-desempenho) e [US35 - Criar Personagem Antropomórfico para Interação Direta](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us35-criar-personagem-antropomorfico-para-interacao-direta) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)| [Arthur Guilherme](https://github.com/ArthurGuilher62) |
| 1.2    | 16/10/2025 | Criação das historias de usuario 7, 8, 9, 10, 12 e 17 | [Felipe Guimaraes](https://github.com/felipegf1)| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.3    | 18/10/2025 | Criação das historias de usuario [US43 – Facilitar Interação entre Monitores, Professores e Alunos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us43-facilitar-interacao-entre-monitores-professores-e-alunos), [US44 – Chat Síncrono para Interação a Distância](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us44-chat-sincrono-para-interacao-a-distancia), [US45 – Acompanhar Interações do Usuário com o Assistente Virtual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us45-acompanhar-interacoes-do-usuario-com-o-assistente-virtual), [US46 – Exibir Progresso do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us46-exibir-progresso-do-aluno), [US49 – Análise Cognitiva e Apoio à Aprendizagem](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us49-analise-cognitiva-e-apoio-a-aprendizagem), [US50 – Identificar Conhecimento do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us50-identificar-conhecimento-do-aluno) e [US51 – Identificar Comportamento Adequado do Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us51-identificar-comportamento-adequado-do-aluno) | [Arthur Guilherme](https://github.com/ArthurGuilher62)| [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.4    | 19/10/2025 | Correção por adição de *hiperlinks* das histórias de usuário, inclusão das etapas de participação e atualização do histórico de versões e dos agradecimentos | [João Felipe](https://github.com/MrBolt2005) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) <rb> [Vilmar José](https://github.com/VilmarFagundes) |
| 1.5    | 20/10/2025 | Criação e adição das histórias de usuário [US01 - Identificação e Autenticação de Usuários](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us01-identificacao-e-autenticacao-de-usuarios), [US02 - Visualizar e Gerenciar Perfil Individual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us02-visualizar-e-gerenciar-perfil-individual), [US11 - Exibir média geral da turma](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us11-exibir-media-geral-da-turma), [US13 - Configurar Alertas de Atividades Atrasadas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us13-configurar-alertas-de-atividades-atrasadas), [US28 - Gerenciar Banco de Questões do Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us28-gerenciar-banco-de-questoes-do-professor), [US38 - Visualizar Personagem do Assistente Virtual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us38-visualizar-personagem-do-assistente-virtual) e e [US40 – Sugerir Questões Pós-Videoaula](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us40-sugerir-questoes-pos-videoaula) | [Vilmar José](https://github.com/VilmarFagundes) | [João Sapiência](https://github.com/JoaoSapiencia) |
| 1.6    | 18/10/2025 | Criação das historias de usuario 03, 04, 05, 16, 20, 25 e 26 | [Arthur Henrique](https://github.com/arthurhvieira1)| [Felipe Guimaraes](https://github.com/felipegf1) |
| 1.7    | 21/10/2025 | Adição das histórias de usuário US14, US24, US31, US32, US33, US36 e US39 | [João Sapiência](https://github.com/JoaoSapiencia) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.8    | 21/10/2025 | Adição da Gravação 1 de validação  | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | [João Sapiência](https://github.com/JoaoSapiencia) |
| 1.9    | 21/10/2025 | Adição da Gravação 1 de validação  | [João Felipe](https://github.com/MrBolt2005) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
| 1.10   | 21/10/2025 | Criação da história de usuário [US42 – Notificação de Conteúdos Mais Difíceis ao Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us42-notificacao-de-conteudos-mais-dificeis-ao-professor)  | [João Felipe](https://github.com/MrBolt2005) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) <br> [Vilmar José](https://github.com/VilmarFagundes) |

