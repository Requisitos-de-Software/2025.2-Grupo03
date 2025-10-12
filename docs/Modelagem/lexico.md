# Léxico

## Introdução
Léxicos referem-se aos termos, vocabulário e símbolos específicos usados para descrever e documentar os requisitos de um sistema, com o objetivo de garantir que todos, desde clientes até desenvolvedores, utilizem e compreendam os mesmos conceitos de forma consistente e sem ambiguidades.

Este documento apresenta os principais léxicos identificados no projeto **SAE (Sistema de Apoio Educacional)**, considerando seus possíveis sinônimos, tipo, definição dentro do contexto do sistema e sua importância tanto para o funcionamento do sistema quanto para a experiência do usuário.

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da construção dos Léxicos, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) | Elaboração dos léxicos 3, 4, 10, 11, 16, 17 |
| [Arthur Henrique](https://github.com/arthurhvieira1) | Elaboração dos léxicos 23, 24 e 25 |
| [Felipe Guimaraes](https://github.com/felipegf1) |   Elaboração dos léxicos 20, 21 , 22 |
| [João Felipe](https://github.com/MrBolt2005) |                                       |
| [João Sapiência](https://github.com/JoaoSapiencia) |                                       |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Léxico e elaboração dos léxicos 5, 6, 7, 12, 13, 18, 19 |
| [Vilmar José](https://github.com/VilmarFagundes) | Elaboração dos léxicos 1, 2, 8, 9, 14, 15 |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Metodologia
A elaboração dos léxicos foi conduzida com base na técnica de modelagem de linguagem conhecida como **Léxico Ampliado da Linguagem (LAL)**, uma abordagem amplamente utilizada na Engenharia de Requisitos para descrever os termos relevantes do domínio de forma clara, consistente e contextualizada.

Cada léxico foi construído a partir da análise individual de um requisito funcional ou não funcional, com o objetivo de identificar os principais termos operacionais, objetos e atributos envolvidos no sistema. A técnica adotada segue a estrutura apresentada nos slides [Requisitos — Aula 10](../arquivos/Cenarios_Aula10.pdf), de Milene Serrano e Maurício Serrano, composta pelos seguintes elementos:

- **Termo:** Nome do conceito identificado.
- **Tipo:** Classificação do termo como **verbo**, **objeto** ou **estado**.  

    - **Verbo:** Representa **ações** realizadas no sistema. Descreve quem executa, quando ocorre e quais procedimentos estão envolvidos, além dos efeitos e novos estados resultantes dessas ações.  

    - **Objeto:** Representa **entidades** ou **elementos manipulados** no sistema. Define o que é o objeto, com quais outros ele se relaciona e quais ações podem ser aplicadas a ele.  

    - **Estado:** Representa **situações** ou **condições** do sistema. Indica o que o estado significa, como foi alcançado e quais outros estados podem surgir a partir dele.  

- **Sinônimos:** Outras palavras ou expressões que possuem o mesmo ou semelhante significado dentro do contexto do sistema.
- **Noção:** Definição do termo dentro do contexto do sistema, explicando seu significado e uso.
- **Impacto:** Importância do termo para o funcionamento do sistema e para o usuário.

---

A **padronização da tabela** se baseou nesses elementos apresentados acima e pode ser observada na **Tabela 2**.

<div align="center"><strong>Tabela 2: Padronização dos Léxicos</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Nome do conceito identificado. | Classificação do termo como **verbo**, **objeto** ou **estado**.  | Outras palavras ou expressões que possuem o mesmo ou semelhante significado dentro do contexto do sistema. | Definição do termo dentro do contexto do sistema, explicando seu significado e uso. | Importância do termo para o funcionamento do sistema e para o usuário. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Léxicos

### Léxico 1: Aluno
O termo "Aluno" define o ator principal e central do sistema. É a pessoa cuja experiência de aprendizado, desempenho e progresso são o foco de todas as funcionalidades de análise e interação do sistema.

<div align="center"><strong>Tabela 3: Léxico – Aluno</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Aluno | Objeto |- Discente<br> - Estudante | Pessoa que utiliza o sistema para acompanhar atividades, desempenho e aprendizado. | - Recebe notificações.<br>- Visualiza progresso e resultados.<br>- Interage com assistente virtual.<br> - Interage com materiais de estudo.<br> - Interage com atividades e questões. |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar José</a></strong></div>

### Léxico 2: Professor
O termo "Professor" define o ator supervisor e facilitador do processo de ensino. É o responsável por ministrar o conteúdo, acompanhar o desempenho coletivo e individual dos estudantes e utilizar os dados analíticos do sistema para tomar decisões pedagógicas.

<div align="center"><strong>Tabela 4: Léxico – Professor</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Professor | Objeto | Docente | Pessoa responsável por ministrar conteúdo e supervisionar atividades. | - Acompanha desempenho dos alunos.<br>- Recebe dados analíticos.<br>- Interage com assistente virtual.<br>- Fornece materiais e questões |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar José</a></strong></div>

### Léxico 3: Monitor
O termo "Monitor" representa o ator auxiliar no processo educacional. É responsável por apoiar os estudantes na realização das atividades, esclarecer dúvidas e facilitar a comunicação entre os envolvidos no ambiente de aprendizagem.

<div align="center"><strong>Tabela 5: Léxico – Monitor</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Monitor | Objeto | Tutor | Pessoa que auxilia alunos no acompanhamento das atividades. | - Auxilia alunos e professores.<br>- Acompanha desempenho.<br>- Facilita interações. |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

### Léxico 4: Coordenador
O termo "Coordenador" define o ator responsável pela supervisão pedagógica do sistema. É a pessoa que organiza processos, acompanha o desempenho dos envolvidos e garante o alinhamento entre os objetivos educacionais e as ações dos professores e monitores.

<div align="center"><strong>Tabela 6: Léxico – Coordenador</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Coordenador | Objeto | Supervisor Acadêmico | Responsável por supervisionar cursos ou disciplinas, organizando processos e atividades. | - Monitora desempenho e progresso de alunos e professores.<br>- Coordena informações de atividades e módulos.<br>- Garante o alinhamento pedagógico entre professores e monitores. |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

### Léxico 5: Administrador
O termo **Administrador** define o ator responsável pela gestão técnica e operacional do sistema. Ele gerencia perfis, permissões, configurações e assegura a integridade, segurança e disponibilidade dos dados, garantindo o funcionamento adequado da plataforma e o acesso controlado dos diferentes perfis de usuários.

<div align="center"><strong>Tabela 7: Léxico – Administrador</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Administrador | Objeto | Gestor do Sistema | Responsável pela gestão do sistema, usuários e configurações gerais. | - Mantém perfis de usuários.<br>- Gerencia permissões e dados do sistema.<br>- Garante segurança, backup e disponibilidade do sistema. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### Léxico 6: AVAs
O termo **AVAs** (Ambientes Virtuais de Aprendizagem) representa as plataformas digitais externas que podem ser integradas ao sistema principal. Elas concentram atividades, materiais e informações de desempenho dos estudantes.

<div align="center"><strong>Tabela 8: Léxico – AVAs</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| AVAs | Objeto | Ambientes Virtuais de Aprendizagem | Plataformas digitais externas integráveis ao sistema. | - Integração com outros sistemas educacionais.<br>- Centraliza informações sobre desempenho e atividades. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### Léxico 7: MinA
O termo **MinA** representa a personagem antropomórfica do Sistema Tutor Inteligente, projetada para interagir diretamente com o estudante de forma amigável e intuitiva. Seu papel é facilitar o engajamento, personalizar a comunicação e melhorar a experiência de aprendizado por meio de interações humanizadas e acessíveis.

<div align="center"><strong>Tabela 9: Léxico – MinA</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Personagem | Objeto | - Personagem antropomórfico | Representação antropomórfica do Sistema Tutor Inteligente para interação direta com o estudante. | - Facilita engajamento.<br>- Permite interação intuitiva. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### Léxico 8: Receber Notificação
O termo "Receber Notificação" é um verbo de ação do sistema que garante a comunicação proativa com o usuário. Refere-se ao ato de o ator ser alertado sobre eventos importantes, como prazos, atividades pendentes ou sugestões de conteúdo para revisão.

<div align="center"><strong>Tabela 10: Léxico – Receber Notificação</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Receber Notificação | Verbo | Alertar-se | Ator recebe alertas sobre atividades, prazos ou conteúdo. | - Mantém usuário informado. |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar José</a></strong></div>

### Léxico 9: Consultar Histórico
O termo "Consultar Histórico" é um verbo essencial para a função analítica do sistema. Permite que o ator visualize e recupere registros de suas atividades passadas, desempenho e o fluxo de notificações, sendo crucial para a autoavaliação do progresso e para o acompanhamento docente.

<div align="center"><strong>Tabela 11: Léxico – Consultar Histórico</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Consultar Histórico | Verbo | Visualizar Histórico | Ator verifica registros de atividades, desempenho e notificações. | - Permite análise do próprio progresso.<br>- Facilita acompanhamento docente. |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar José</a></strong></div>

### Léxico 10: Consultar Conteúdo
O termo "Consultar Conteúdo" é um verbo que representa a ação de acessar materiais didáticos. Permite ao ator visualizar tópicos da disciplina, servindo como base para o estudo.

<div align="center"><strong>Tabela 12: Léxico – Consultar Conteúdo</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Consultar Conteúdo | Verbo | Visualizar Conteúdo | Ator acessa material didático ou tópicos da disciplina. | - Base para realização de atividades.<br>- Orienta estudo individual. |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

### Léxico 11: Realizar Atividade
O termo "Realizar Atividade" é um verbo que expressa a execução de tarefas propostas pelo sistema. Refere-se ao momento em que o usuário interage com exercícios, avaliações ou atividades, gerando dados de desempenho.

<div align="center"><strong>Tabela 13: Léxico – Realizar Atividade</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Realizar Atividade | Verbo | Executar Tarefa | Usuário completa exercício, avaliação ou tarefa. | - Gera registros de desempenho.<br>- Contribui para histórico e progresso. |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

### Léxico 12: Consultar Desempenho
O termo **Consultar Desempenho** é um verbo que representa a ação de verificar resultados e métricas de aprendizado. Essa funcionalidade permite ao usuário acompanhar seus acertos, erros, médias e progresso ao longo da disciplina, servindo como base para autoavaliação e revisão de conteúdos.

<div align="center"><strong>Tabela 14: Léxico – Consultar Desempenho</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Consultar Desempenho | Verbo | Ver Resultados | Usuário verifica acertos, erros, médias e progresso. | - Permite acompanhamento do aprendizado.<br>- Auxilia na tomada de decisão sobre revisão de conteúdo. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### Léxico 13: Fornecer Estatísticas
O termo **Fornecer Estatísticas** é um verbo que descreve a ação do sistema ao disponibilizar dados analíticos sobre o desempenho dos estudantes e o andamento das atividades. Essa função é essencial para suporte à gestão pedagógica, monitoramento de turmas e avaliação de resultados por parte de professores e coordenadores.

<div align="center"><strong>Tabela 15: Léxico – Fornecer Estatísticas</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Fornecer Estatísticas| Verbo | Exibir Estatísticas | Sistema disponibiliza informações analíticas sobre desempenho e progresso. | - Suporte a decisões pedagógicas.<br>- Auxilia monitoramento de turmas e indivíduos. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### Léxico 14: Atividade Concluída

O termo “Atividade Concluída” refere-se ao estado em que o aluno finalizou uma atividade, tornando seus resultados disponíveis para análise e cálculo de desempenho.

<div align="center"><strong>Tabela 16: Léxico – Atividade Concluída</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|----------|-------|----------------|-----------|------------|
| Atividade Concluída  | Estado | Finalizada, Encerrada  | Condição em que a atividade foi totalmente realizada pelo aluno.       | - Permite o registro de notas e estatísticas.<br>- Atualiza o progresso geral da disciplina.<br>- Gera feedback automático ao usuário. |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar José</a></strong></div>

### Léxico 15: Atividade Pendente

O termo “Atividade Pendente” refere-se à condição em que uma atividade ainda não foi concluída e permanece aguardando ação do aluno.

<div align="center"><strong>Tabela 17: Léxico – Atividade Pendente</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|----------|-------|----------------|-----------|------------|
| Atividade Pendente  | Estado | Não Realizada, Incompleta | Condição em que o aluno ainda não enviou ou concluiu uma atividade.      | - Permite emissão de notificações automáticas.<br>- Ajuda no controle de prazos e alertas de atraso.<br>- Indica tarefas ainda em aberto no sistema. |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar José</a></strong></div>

### Léxico 16: Atividade em Andamento

O termo “Atividade em Andamento” refere-se ao estado em que o aluno iniciou uma atividade, mas ainda não a concluiu completamente.

<div align="center"><strong>Tabela 18: Léxico – Atividade em Andamento</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|----------|-------|----------------|-----------|------------|
| Atividade em Andamento   | Estado | Em Execução, Em Progresso | Condição em que o aluno está realizando uma atividade, mas o envio ainda não foi concluído. | - Permite acompanhamento em tempo real.<br>- Atualiza parcialmente o progresso.<br>- Garante continuidade entre sessões de uso. |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

### Léxico 17: Atividade Atrasada

O termo “Atividade Atrasada” refere-se à condição em que o prazo de entrega da atividade foi ultrapassado sem a sua conclusão.

<div align="center"><strong>Tabela 19: Léxico – Atividade Atrasada</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|----------|-------|----------------|-----------|------------|
| Atividade Atrasada | Estado | Vencida, Fora do Prazo | Condição em que o prazo da atividade expirou antes da entrega. | - Gera notificações automáticas ao aluno e ao professor.<br>- Afeta o cálculo de desempenho e pontuação.<br>- Pode influenciar alertas do assistente virtual. |

<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

### Léxico 18: Conteúdo Dominado

O termo “Conteúdo Dominado” refere-se ao estado em que o aluno demonstrou domínio sobre determinado tema ou módulo, atingindo o nível de acertos esperado.

<div align="center"><strong>Tabela 20: Léxico – Conteúdo Dominado</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|----------|-------|----------------|-----------|------------|
| Conteúdo Dominado  | Estado | Aprovado, Domínio Alcançado | Indica que o aluno atingiu o desempenho mínimo esperado em um conteúdo. | - Atualiza o progresso de aprendizagem.<br>- Reduz a priorização de revisões.<br>- Fornece base para recomendações personalizadas. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### Léxico 19: Conteúdo em Dificuldade

O termo “Conteúdo em Dificuldade” refere-se ao estado em que o sistema identifica baixo desempenho ou alto índice de erro em determinado tema.

<div align="center"><strong>Tabela 21: Léxico – Conteúdo em Dificuldade</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|----------|-------|----------------|-----------|------------|
| Conteúdo em Dificuldade  | Estado | Fraco, Necessidade de revisão   | Indica que o aluno apresenta baixo desempenho em um determinado conteúdo. | - Gera alertas ao assistente virtual.<br>- Direciona materiais de reforço.<br>- Auxilia professores na identificação de dificuldades coletivas. |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### Léxico 20: Banco de questoões

O termo “Banco de Questões” refere-se ao repositório central do sistema onde são armazenadas, organizadas e gerenciadas todas as questões utilizadas nas atividades e avaliações.

<div align="center"><strong>Tabela 22: Léxico – Banco de Questões</strong></div>

| Termo             | Tipo   | Sinônimos    | Noção  | Impacto   |
| ----------------- | ------ | -------- | ------------------------|-------------------------------|
| Banco de Questões | Objeto | Repositório de Questões, Base de Questões | Conjunto estruturado de questões criadas ou importadas pelos professores, classificadas por conteúdo, nível de dificuldade e tipo. | - Facilita a criação e reaproveitamento de avaliações.<br>- Permite organização eficiente por temas e disciplinas.<br>- Garante consistência e padronização das questões no sistema.<br>- Contribui para a geração automática de provas e exercícios. |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

### Léxico 21: Separar por conteudo

O termo “Separar por Conteúdo” refere-se à ação de organizar as questões do banco de acordo com os conteúdos temáticos definidos pelo professor.

<div align="center"><strong>Tabela 23: Léxico – Separar por Conteúdo</strong></div>

| Termo                | Tipo  | Sinônimos                         | Noção        | Impacto     |
| -------------------- | ----- |---------------------------------|------------------- |------- |
| Separar por Conteúdo | Verbo | Classificar por Tópico, Organizar por Assunto | Ação de agrupar ou associar cada questão a um conteúdo específico, garantindo a estruturação do banco de questões. | - Melhora a navegação e busca no banco.<br>- Permite geração de provas temáticas e filtragens personalizadas.<br>- Garante coerência entre questões e o plano de ensino.<br>- Pode ser realizada automaticamente ou manualmente pelo professor. |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

### Léxico 22: Aluno com Dificuldade

O termo “Aluno com Dificuldade” refere-se ao estado em que o desempenho do aluno apresenta indícios de baixo aproveitamento em uma ou mais disciplinas, conteúdos ou atividades avaliativas.

<div align="center"><strong>Tabela 24: Léxico – Aluno com Dificuldade</strong></div>

| Termo                 | Tipo   | Sinônimos                        | Noção  | Impacto |
| --------------------- | ------ | -------------------------------- | --------|--------- |
| Aluno com Dificuldade | Estado | Desempenho Baixo, Aluno em Risco | Condição em que o aluno apresenta resultados abaixo do esperado, seja por notas, frequência, ou tempo de conclusão das atividades. | - Permite geração de alertas automáticos ao professor.<br>- Pode acionar recomendações de estudo personalizadas.<br>- Contribui para relatórios de desempenho e acompanhamento pedagógico.<br>- Ajuda na tomada de decisão sobre intervenções e reforços. |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

### **Léxico 23: Progresso**
O termo "Progresso" representa o acompanhamento contínuo do aprendizado do aluno dentro das disciplinas e atividades. Indica visualmente o quanto o aluno já avançou em relação aos conteúdos estudados.

<div align="center"><strong>Tabela 23: Léxico – Progresso</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Progresso | Objeto | - Evolução<br>- Avanço<br>- Desenvolvimento | Percentual que indica o quanto do conteúdo ou atividade foi concluído pelo aluno. É calculado com base nos conteúdos finalizados e nas atividades respondidas. | - Permite ao aluno acompanhar sua evolução na disciplina.<br>- Alimenta análises gráficas e relatórios.<br>- É exibido na interface e utilizado pelo assistente virtual.<br>- Serve de base para notificações de desempenho. |

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

### **Léxico 24: Vídeo Aula**
O termo "Vídeo Aula" refere-se ao material audiovisual utilizado para o ensino dos conteúdos da disciplina, servindo como base para estudo, prática e recomendação de questões pelo assistente virtual.

<div align="center"><strong>Tabela 24: Léxico – Vídeo Aula</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Vídeo Aula | Objeto | - Aula Gravada<br>- Conteúdo Audiovisual<br>- Material de Ensino | Recurso que transmite o conteúdo teórico ou prático da disciplina, vinculado a tópicos específicos de aprendizagem. | - Serve como base para sugestões de questões.<br>- Pode ser analisada pelo assistente virtual.<br>- Estimula o aprendizado autônomo.<br>- Integra-se aos conteúdos e atividades avaliativas. |

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

### **Léxico 25: Inferência**
O termo "Inferência" representa o processo automatizado de análise cognitiva realizado pelo sistema, com base em dados e resultados do aluno, para interpretar o nível de aprendizagem e sugerir ações pedagógicas.

<div align="center"><strong>Tabela 25: Léxico – Inferência</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Inferência | Processo | - Análise Cognitiva<br>- Dedução | Processo conduzido pelo sistema ou assistente virtual para avaliar padrões de desempenho, acertos e erros, aplicando modelos como a Lógica Fuzzy e a Teoria da Aprendizagem Significativa. | - Permite avaliações graduais e mais humanas.<br>- Alimenta decisões do assistente virtual.<br>- Orienta recomendações personalizadas de conteúdo.<br>- Auxilia professores na identificação de dificuldades cognitivas. |

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>

---

### **Léxico 26: Estatísticas**
O termo "Estatísticas" define o conjunto de dados analíticos e métricas apresentadas pelo sistema, que representam o desempenho do aluno, da turma e de comparativos entre disciplinas.

<div align="center"><strong>Tabela 26: Léxico – Estatísticas</strong></div>

| Termo | Tipo | Sinônimos | Noção | Impacto |
|-------|------|-----------|-------|---------|
| Estatística | Objeto | - Análise de Dados<br>- Relatório de Desempenho<br>- Indicador | Representação numérica e gráfica dos resultados obtidos por alunos, turmas e disciplinas, geralmente exibida em formato de gráfico ou relatório. | - Facilita a análise de desempenho por parte dos docentes.<br>- Fornece feedback visual ao aluno.<br>- Alimenta o painel de controle do sistema.<br>- Suporta a tomada de decisão pedagógica. |

<div align="center"><strong>Autoria de <a href="https://github.com/arthurhvieira1">Arthur Henrique</a></strong></div>


## Referências
SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10. Disponível em: [Requisitos_Aula 10](../arquivos/Cenarios_Aula10.pdf). Acesso em: 10 outubro 2025.

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 05/10/2025 | Criação do documento dos Léxicos | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [Arthur Guilherme](https://github.com/ArthurGuilher62) |
| 1.1    | 09/10/2025 | Elaboração dos Léxicos 1, 2, 8, 9, 14, 15 | [Vilmar José](https://github.com/VilmarFagundes) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)  |
| 1.2    | 09/10/2025 | Elaboração dos léxicos 3, 4, 10, 11, 16, 17 | [Arthur Guilherme](https://github.com/ArthurGuilher62) | [Vilmar José](https://github.com/VilmarFagundes)  |
| 1.3    | 10/10/2025 | Elaboração dos léxicos 5, 6, 7, 12, 13, 18, 19 | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [Arthur Guilherme](https://github.com/ArthurGuilher62) |
| 1.4    | 12/10/2025 | Atualização do documento de Léxico | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [Arthur Guilherme](https://github.com/ArthurGuilher62) |
| 1.5    | 12/10/2025 | Atualização do documento de Léxico | [Arthur Henrique](https://github.com/arthurhvieira1) |  [Vilmar José](https://github.com/VilmarFagundes) |

