# Forward-From

## Introdução

A rastreabilidade **Forward-From (ou rastreabilidade para frente)** é uma abordagem que permite acompanhar o destino de cada requisito ao longo do desenvolvimento do projeto. Ela responde à pergunta **“o que acontece com este requisito?”**, mostrando como ele é transformado em artefatos de design, código, testes e documentação.

Em outras palavras, a rastreabilidade Forward-From garante que cada requisito seja devidamente implementado e testado, permitindo verificar se todas as necessidades levantadas foram atendidas e facilitando o controle de progresso e validação do sistema.

## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da etapa da Histórias de Usuário, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) |  |
| [Arthur Henrique](https://github.com/arthurhvieira1) |  |
| [Felipe Guimaraes](https://github.com/felipegf1) |  |
| [João Felipe](https://github.com/MrBolt2005) |  |
| [João Sapiência](https://github.com/JoaoSapiencia) |  |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Forward-From e adição dos Forward-From: [FF06](#FF06), [FF15](#FF15), [FF18](#FF18), [FF19](#FF19), [FF21](#FF21), [FF22](#FF22), [FF34](#FF34), [FF35](#FF35), [FF52](#FF52) e [FF56](#FF56) |
| [Vilmar José](https://github.com/VilmarFagundes) |  |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Metodologia

A metodologia adotada para esta análise baseia-se no **Meta-modelo de Toranzo**, conforme apresentado nos slides da aula *“Requisitos – Aula 26”*, de Milene Serrano e Maurício Serrano, disponíveis [clicando aqui](../arquivos/Requisitos%20-%20aula26-milene-modelagem.pdf).  

Esse modelo organiza as informações rastreáveis em **níveis hierárquicos** e define **elos** que representam as relações entre os artefatos envolvidos no desenvolvimento de sistemas.

### Níveis de Informação

Nesta análise, o foco está no **nível de Desenvolvimento**, um dos quatro níveis principais do modelo, conforme apresentado na Figura 1:  

- **Ambiental**  
- **Organizacional**  
- **Gerencial**  
- **Desenvolvimento**  

<div align="center"><strong>Figura 1: Níveis de Desenvolvimento</strong></div>

![Figura 1: Níveis de Desenvolvimento](../imagens/matriz_rastreabilidade/niveis_rastreabilidade.png)

<div align="center"><strong>Fonte: SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26</strong></div>

No contexto da **rastreabilidade Forward-From**, o objetivo é **conectar os requisitos documentados aos artefatos de design e implementação**, permitindo rastrear **como os requisitos são transformados em componentes técnicos**.

### Elos de Rastreabilidade

Para modelar as conexões entre os requisitos e os artefatos técnicos, foram utilizados os **elos de rastreabilidade** definidos no modelo de Toranzo, conforme apresentado na Figura 2:  

- **Satisfação:** Conecta um requisito funcional a um requisito não funcional que define uma condição ou qualidade que deve ser atendida.  
- **Recurso:** Conecta um requisito a um dado, serviço ou funcionalidade da qual ele precisa para funcionar corretamente.  
- **Responsabilidade:** Conecta um requisito ao ator, componente ou módulo que será responsável por realizá-lo.  
- **Representação:** Conecta um requisito à sua forma de modelagem ou descrição em outro artefato.  
- **Alocado:** Conecta um requisito a um artefato de planejamento que indica onde e como ele será desenvolvido.  
- **Agregação:** Conecta um requisito a outro com o qual se combina para formar uma funcionalidade maior.


<div align="center"><strong>Figura 2: Tipos de Elos de Rastreabilidade</strong></div>

![Figura 2: Tipos de Elos de Rastreabilidade](../imagens/matriz_rastreabilidade/tipos_elos_rastreabilidade.png)

<div align="center"><strong>Fonte: SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26</strong></div>

Cada elo é aplicado conforme a **natureza da relação** entre os requisitos e os elementos de implementação.  

A aplicação prática dessa metodologia é apresentada em uma **tabela de mapeamento**, que relaciona os requisitos aos artefatos de design e implementação correspondentes, indicando o tipo de elo utilizado em cada caso.  
Essa abordagem permite **verificar se os requisitos estão sendo corretamente contemplados** nas etapas subsequentes do desenvolvimento e **facilita a gestão da conformidade** ao longo de todo o ciclo de vida do sistema.



## Legenda

## Forward-From

### Requisitos Funcionais

Na tabela 2 encontra-se a rastreabilidade Forward-From dos Requisitos Funcionais.

<div align="center"><strong>Tabela 2: Requisitos Funcionais</strong></div>

| ID   | Requisito | Descrição | Implementado | Elo Relacionado | Casos de Uso | Cenários | Léxicos | Histórias de Usuário | Backlog | Protótipo |
|------|-----------|-----------|--------------|-----------------|--------------|----------|---------|--------------------|---------|-----------|
| <a id="FF06"></a>FF06 | [RF06](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF06) | O assistente virtual deve combinar resultados formais com inferências Fuzzy. | Sim |  |  |  | [Assistente Virtual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-27-assistente-virtual), [Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-28-desempenho), [Fornecer Estatísticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-13-fornecer-estatisticas) | [US06 - Combinar Resultados Formais com Inferências Fuzzy](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us06-combinar-resultados-formais-com-inferencias-fuzzy) | [EP06 – Utilizar Lógica Fuzzy para Apoiar Decisões Pedagógicas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep06-utilizar-logica-fuzzy-para-apoiar-decisoes-pedagogicas) e [TM04 - Assistente Virtual Inteligente](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#tm04-assistente-virtual-inteligente) |  |
| <a id="FF15"></a>FF15 | [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF15) | O sistema deve enviar notificações para lembrar o usuário de revisar conteúdos passados. | Não |  | [UC04 - Lembretes de Revisão de Conteúdos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/casos_de_uso/#uc04-lembretes-de-revisao-de-conteudos) | [CE04 - Lembretes de Revisão de Conteúdos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/cenario/#cenario-04-lembretes-de-revisao-de-conteudos) | [Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-1-aluno), [Receber Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-8-receber-notificacao), [Consultar Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-10-consultar-conteudo), [Conteúdo Dominado](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-18-conteudo-dominado), [Conteúdo em Dificuldade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-19-conteudo-em-dificuldade) | [US15 - Enviar Notificações para Revisão de Conteúdos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us15-enviar-notificacoes-para-revisao-de-conteudos) | [EP19 – Enviar Alertas sobre Prazos e Revisões de Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep19-enviar-alertas-sobre-prazos-e-revisoes-de-conteudo) e [TM07 - Alertas e Notificações Inteligentes](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#tm07-alertas-e-notificacoes-inteligentes) |  |
| <a id="FF18"></a>FF18 | [RF18](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF18) | O sistema deve pedir ao usuário a melhor forma de caminho de notificação. | Não |  | [UC05 - Configuração da Forma de Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/casos_de_uso/#uc05-configuracao-da-forma-de-notificacao) | [CE05 - Configuração da Forma de Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/cenario/#cenario-05-configuracao-da-forma-de-notificacao) | [Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-1-aluno), [Receber Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-8-receber-notificacao), [Configurar Aviso](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-29-configurar-aviso) | [US18 - Definir Forma Preferida de Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us18-definir-forma-preferida-de-notificacao) | [EP18 – Configurar Preferências de Tempo e Forma de Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep18-configurar-preferencias-de-tempo-e-forma-de-notificacao) e [TM07 - Alertas e Notificações Inteligentes](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#tm07-alertas-e-notificacoes-inteligentes) |  |
| <a id="FF19"></a>FF19 | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF19) | O sistema deve enviar uma notificação quando está chegando perto da data de entrega de uma atividade. | Não |  | [UC06 - Notificação de Prazo de Entrega](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/casos_de_uso/#uc06-notificacao-de-prazo-de-entrega) | [CE06 - Notificação de Prazo de Entrega](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/cenario/#cenario-06-notificacao-de-prazo-de-entrega)  | [Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-1-aluno), [Receber Notificação](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-8-receber-notificacao), [Atividade Concluída](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-14-atividade-concluida), [Atividade Pendente](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-15-atividade-pendente), [Atividade em Andamento](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-16-atividade-em-andamento), [Atividade Atrasada](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-17-atividade-atrasada), [Configurar Aviso](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-29-configurar-aviso) | [US19 - Enviar Notificação sobre Prazo de Entrega de Atividade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us19-enviar-notificacao-sobre-prazo-de-entrega-de-atividade) | [EP19 – Enviar Alertas sobre Prazos e Revisões de Conteúdo](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep19-enviar-alertas-sobre-prazos-e-revisoes-de-conteudo) e [TM07 - Alertas e Notificações Inteligentes](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#tm07-alertas-e-notificacoes-inteligentes) |  |
| <a id="FF21"></a>FF21 | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF21) | O sistema deve fornecer dados e informações analíticas em diferentes níveis (individual, turma, entre turmas). | Sim |  |  |  | [Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-2-professor), [Monitor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-3-monitor), [Consultar Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-12-consultar-desempenho), [Fornecer Estatísticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-13-fornecer-estatisticas), [Analisar Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-24-analisar-desempenho) | [US21 - Exibir Dados e Informações Analíticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us21-exibir-dados-e-informacoes-analiticas) | [EP13 – Gerar Análises em Tempo Real com Gráficos e Indicadores](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep13-gerar-analises-em-tempo-real-com-graficos-e-indicadores) e [TM05 - Análise e Visualização de Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#tm05-analise-e-visualizacao-de-desempenho) |  |
| <a id="FF22"></a>FF22 | [RF22](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF22) | As análises devem ser em tempo real e apresentadas em gráficos (barra, coluna, linha, pizza). | Sim |  |  |  | [Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-2-professor), [Monitor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-3-monitor), [Consultar Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-12-consultar-desempenho), [Fornecer Estatísticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-13-fornecer-estatisticas), [Estatísticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-26-estatisticas), [Analisar Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-24-analisar-desempenho) | [US22 - Gerar Análises em Tempo Real com Gráficos](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us22-gerar-analises-em-tempo-real-com-graficos) | [EP13 – Gerar Análises em Tempo Real com Gráficos e Indicadores](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep13-gerar-analises-em-tempo-real-com-graficos-e-indicadores) e [TM05 - Análise e Visualização de Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#tm05-analise-e-visualizacao-de-desempenho) |  |
| <a id="FF34"></a>FF34 | [RF34](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF34) | A integração deve reduzir o esforço de professores e monitores, centralizando informações sobre atividades e desempenho. | Sim |  |  |  | [Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-2-professor), [Monitor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-3-monitor), [Consultar Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-12-consultar-desempenho), [Analisar Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-24-analisar-desempenho), [Estatísticas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-26-estatisticas) | [US34 - Centralizar Informações de Atividades e Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us34-centralizar-informacoes-de-atividades-e-desempenho) | [EP25 – Centralizar Informações Educacionais](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep25-centralizar-informacoes-educacionais) e [TM10 - Integração e Centralização de Sistemas](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#tm10-integracao-e-centralizacao-de-sistemas) |  |
| <a id="FF35"></a>FF35 | [RF35](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF35) | O sistema deve criar um personagem antropomórfico para interação direta com o estudante. | Sim |  |  |  | [Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-1-aluno), [Assistente Virtual](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-27-assistente-virtual), [Perfil](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-23-perfil) | [US35 - Criar Personagem Antropomórfico para Interação Direta](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/historias_de_usuario/#us35-criar-personagem-antropomorfico-para-interacao-direta) | [EP09 – Criar Personagem Interativo Customizável](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#ep09-criar-personagem-interativo-customizavel) e [TM04 - Assistente Virtual Inteligente](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/backlog_do_produto/#tm04-assistente-virtual-inteligente) |  |


<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

### Requisitos Não-Funcionais

Na tabela 3 encontra-se a rastreabilidade Forward-From dos Requisitos Não-Funcionais.

<div align="center"><strong>Tabela 3: Requisitos Não-Funcionais</strong></div>

| ID   | Requisito | Descrição | Implementado | Elo Relacionado | Léxicos | Especificação Suplementar | NFR Framework |
|------|-----------|-----------|--------------|-----------------|---------|---------------------------|---------------|
| <a id="FF52"></a>FF52  | [RNF01](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RNF01) | A interface deve se adaptar automaticamente ao perfil de cada indivíduo (aluno, monitor, professor, etc.). | Sim |  | [Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-1-aluno), [Monitor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-3-monitor), [Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-2-professor), [Perfil](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-23-perfil) | [Usabilidade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/especificacao_suplementar/#2-usabilidade) | [NFR 01 - Usabilidade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/nfr_framework/#nfr-01-usabilidade) |
| <a id="FF56"></a>FF56  | [RNF05](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RNF05) | Deve empregar recursos tecnológicos alinhados à Teoria da Aprendizagem Significativa (TAS). | Sim |  | [Aluno](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-1-aluno), [Professor](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-2-professor), [Analisar Desempenho](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/lexico/#lexico-24-analisar-desempenho) | [Suportabilidade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/especificacao_suplementar/#4-suportabilidade) | [NFR 03 - Suportabilidade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/nfr_framework/#nfr-03-suportabilidade) |


<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>


---

### Elos de Rastreabilidade (Forward-From)

A tabela 4 detalha os **elos de rastreabilidade Forward-From** para os requisitos selecionados.  
A descrição de cada elo mostra como o requisito é **rastreado para frente**, conectando-se aos **artefatos de modelagem e planejamento** que orientam sua implementação.

<div align="center"><strong>Tabela 4: Elos de Rastreabilidade Forward-From</strong></div>

| ID - Elo   | ID - Backward-From | Tipo de Vínculo | Descrição do Elo |
|------------|--------------------|-----------------|------------------|

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## Agradecimentos
O Grupo 03 agradece o apoio das ferramentas de Inteligência Artificial Generativa — **ChatGPT, GitHub Copilot, Google Gemini e DeepSeek** — na revisão gramatical e de estilo deste artigo. As tecnologias foram utilizadas para tornar o texto mais claro, objetivo e fácil de ler. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Referências

SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. Disponível em: [Requisitos_Aula 26](../arquivos/Requisitos%20-%20aula26-milene-modelagem.pdf). Acesso em: 24 outubro 2025.

## Históricos de versão

| Versão | Data       | Descrição  | Autor(es)        | Revisor    |
|--------|------------|---------------------------------------------|----|---------------|
| 1.0    | 23/10/2025 | Criação do documento de Forward-From | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)| [Vilmar José](https://github.com/VilmarFagundes) |
| 1.1    | 24/10/2025 | Adição dos Forward-From: [FF06](#FF06), [FF15](#FF15), [FF18](#FF18), [FF19](#FF19), [FF21](#FF21), [FF22](#FF22), [FF34](#FF34), [FF35](#FF35), [FF52](#FF52) e [FF56](#FF56) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)| [João Felipe](https://github.com/MrBolt2005) |