# Backward-From

## Introdução

A rastreabilidade **Backward-From (ou rastreabilidade para trás)** é uma abordagem que permite identificar a origem de cada requisito dentro de um projeto. Ela busca responder à pergunta **“por que este requisito existe?”**, estabelecendo uma ligação entre os requisitos atuais e suas fontes de elicitação, como entrevistas, documentos, ou necessidades dos usuários.

Em outras palavras, ela garante que nenhum requisito seja implementado sem uma justificativa clara, permitindo compreender o contexto e o motivo de sua criação. Essa prática é fundamental para manter a consistência, a transparência e o controle sobre as decisões tomadas durante o desenvolvimento do sistema.

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
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Forward-From e adição dos Forward-From: [BF06](#BF06), [BF15](#BF15), [BF18](#BF18), [BF19](#BF19), [BF21](#BF21), [BF22](#BF22), [BF34](#BF34), [BF35](#BF35), [BF52](#BF52) e [BF56](#BF56). Além da criação dos elos do mesmo intervalo [ELOBF06](#ELOBF06), [ELOBF15](#ELOBF15), [ELOBF18](#ELOBF18), [ELOBF19](#ELOBF19), [ELOBF21](#ELOBF21), [ELOBF22](#ELOBF22), [ELOBF34](#ELOBF34), [ELOBF35](#ELOBF35), [ELOBF52](#ELOBF52) e [ELOBF56](#ELOBF56)|
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

No contexto da **rastreabilidade Backward-From**, o objetivo é **conectar cada requisito à sua origem**, permitindo rastrear **de onde ele veio e qual necessidade ou decisão o motivou**.  
Essa abordagem ajuda a compreender o **propósito de cada requisito** e a **garantir a consistência entre as fontes de elicitação e os requisitos documentados**.

### Elos de Rastreabilidade

Para modelar as conexões entre os requisitos e suas origens, foram utilizados os **elos de rastreabilidade** definidos no modelo de Toranzo, conforme apresentado na Figura 2:  

- **Satisfação:** Conecta um requisito (artefato de origem) a qualquer outro artefato de destino (como outro requisito, história de usuário, componente ou módulo) que seja necessário para cumprir, implementar ou atender a esse requisito. 
- **Recurso:** Conecta um requisito a um dado, serviço ou funcionalidade da qual ele depende para funcionar corretamente.  
- **Responsabilidade:** Conecta um requisito ao ator, componente ou módulo responsável por sua criação ou definição.  
- **Representação:** Conecta um requisito à sua origem ou forma de especificação em outro artefato.  
- **Alocado:** Conecta um requisito a um artefato de planejamento que indica de onde ele foi derivado ou relacionado.  
- **Agregação:** Conecta um requisito a outro do qual ele faz parte ou que o complementa, formando uma funcionalidade mais ampla.

<div align="center"><strong>Figura 2: Tipos de Elos de Rastreabilidade</strong></div>

![Figura 2: Tipos de Elos de Rastreabilidade](../imagens/matriz_rastreabilidade/tipos_elos_rastreabilidade.png)

<div align="center"><strong>Fonte: SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26</strong></div>

Cada elo é aplicado conforme a **natureza da relação** entre os requisitos e os elementos que lhes dão origem.  

A aplicação prática dessa metodologia é apresentada em uma **tabela de mapeamento**, que relaciona os requisitos às suas respectivas fontes e artefatos de elicitação, indicando o tipo de elo utilizado em cada caso.  
Essa abordagem permite **verificar se todos os requisitos têm origem bem definida**, **mantendo a coerência entre as etapas de elicitação e documentação** e **facilitando o controle da rastreabilidade** ao longo do projeto.

## Legenda

## Backward-From

### Requisitos Funcionais

Na tabela 2 encontra-se a rastreabilidade Backward-From dos Requisitos Funcionais.

<div align="center"><strong>Tabela 2: Requisitos Funcionais</strong></div>

| ID   | Requisito | Descrição | Rastreabilidade | Implementado | Elo Relacionado |
|------|------------|-----------|------------------|--------------|-----------------|
| <a id="BF06"></a>BF06 | [RF06](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF06) | O assistente virtual deve combinar resultados formais com inferências Fuzzy. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim | [ELOBF06](#ELOBF06) |
| <a id="BF15"></a>BF15 | [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF15) | O sistema deve enviar notificações para lembrar o usuário de revisar conteúdos passados. | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Não | [ELOBF15](#ELOBF15) |
| <a id="BF18"></a>BF18 | [RF18](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF18) | O sistema deve pedir ao usuário a melhor forma de caminho de notificação. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não | [ELOBF18](#ELOBF18) |
| <a id="BF19"></a>BF19 | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF19) | O sistema deve enviar uma notificação quando está chegando perto da data de entrega de uma atividade. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não | [ELOBF19](#ELOBF19) |
| <a id="BF21"></a>BF21 | [RF21](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF21) | O sistema deve fornecer dados e informações analíticas em diferentes níveis (individual, turma, entre turmas). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim | [ELOBF21](#ELOBF21) |
| <a id="BF22"></a>BF22 | [RF22](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF22) | As análises devem ser em tempo real e apresentadas em gráficos (barra, coluna, linha, pizza). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim | [ELOBF22](#ELOBF22) |
| <a id="BF34"></a>BF34 | [RF34](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF34) | A integração deve reduzir o esforço de professores e monitores, centralizando informações sobre atividades e desempenho. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim | [ELOBF34](#ELOBF34) |
| <a id="BF35"></a>BF35 | [RF35](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF35) | O sistema deve criar um personagem antropomórfico para interação direta com o estudante. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim | [ELOBF35](#ELOBF35) |


<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

### Requisitos Não-Funcionais

Na tabela 3 encontra-se a rastreabilidade Backward-From dos Requisitos Não-Funcionais.

<div align="center"><strong>Tabela 3: Requisitos Não-Funcionais</strong></div>

| ID   | Requisito | Descrição | Rastreabilidade | Implementado | Elo Relacionado |
|------|------------|-----------|------------------|--------------|-----------------|
| <a id="BF52"></a>BF52 | [RNF01](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RNF01) | A interface deve se adaptar automaticamente ao perfil de cada indivíduo (aluno, monitor, professor, etc.). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim | [ELOBF52](#ELOBF52) |
| <a id="BF56"></a>BF56 | [RNF05](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RNF05) | Deve empregar recursos tecnológicos alinhados à Teoria da Aprendizagem Significativa (TAS). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim | [ELOBF56](#ELOBF56) |



<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

### Elos de Rastreabilidade (Backward-From)

A tabela 4 apresenta os **elos de rastreabilidade Backward-From** para os requisitos selecionados.  
Cada elo descreve como o requisito é **rastreado para trás**, conectando-o à sua **origem na elicitação** — como entrevistas, documentos ou necessidades dos usuários — e demonstrando o **motivo de sua existência** no sistema.

<div align="center"><strong>Tabela 4: Elos de Rastreabilidade Backward-From</strong></div>

| ID - Elo   | ID - Backward-From | Tipo de Vínculo | Descrição do Elo |
|------------|--------------------|-----------------|------------------|
| <a id="ELOBF06"></a>ELOBF06 | [BF06](#BF06) | **Representação** | Este elo formaliza que o requisito [RF06](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF06), que define a combinação de resultados formais com inferências Fuzzy, é representado pela funcionalidade de análise inteligente de dados educacionais. |
| <a id="ELOBF15"></a>ELOBF15 | [BF15](#BF15) | **Recurso** | Este elo estabelece que o requisito [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF15), responsável pelo envio de notificações de revisão de conteúdos, depende do recurso de notificação compartilhado com os requisitos [RF18](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF18) e [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF19). |
| <a id="ELOBF18"></a>ELOBF18 | [BF18](#BF18) | **Recurso** | Este elo define que o requisito [RF18](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF18), que solicita a escolha do caminho de notificação preferido pelo usuário, depende do módulo de configuração de notificações, recurso essencial ao funcionamento de [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF15). |
| <a id="ELOBF19"></a>ELOBF19 | [BF19](#BF19) | **Recurso** | Este elo estabelece que o requisito [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF19), que envia notificações sobre prazos de entrega de atividades, utiliza o mesmo recurso de notificação definido por [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF15). |
| <a id="ELOBF21"></a>ELOBF21 | [BF21](#BF21) | **Agregação** | Este elo define que o requisito [RF21](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF21), responsável pela disponibilização de dados analíticos em diferentes níveis, agrega as funcionalidades de análise e visualização definidas em [RF22](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF22). |
| <a id="ELOBF22"></a>ELOBF22 | [BF22](#BF22) | **Representação** | Este elo representa o requisito [RF22](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF22), que detalha a forma de exibição dos dados analíticos em gráficos, como uma manifestação visual da análise descrita em [RF21](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF21). |
| <a id="ELOBF34"></a>ELOBF34 | [BF34](#BF34) | **Agregação** | Este elo formaliza que o requisito [RF34](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF34), que visa reduzir o esforço de professores e monitores por meio da centralização de informações, agrega funcionalidades relacionadas ao **desempenho** ([RF07](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF07), [RF08](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF08), [RF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF09), [RF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF10), [RF11](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF11), [RF12](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF12), [RF21](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF21), [RF22](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF22), [RF23](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF23), [RF46](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF46), [RF50](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF50), [RF51](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF51)) e às **atividades** ([RF04](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF04), [RF24](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF24), [RF25](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF25), [RF26](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF26), [RF27](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF27), [RF28](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF28), [RF29](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF29), [RF30](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF30), [RF32](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF32), [RF43](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF43), [RF44](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF44)). |
| <a id="ELOBF35"></a>ELOBF35 | [BF35](#BF35) | **Representação** | Este elo representa que o requisito [RF35](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RF35), que define a criação de um personagem antropomórfico, é a materialização visual e interativa do assistente virtual, agregando valor à interface e à experiência do usuário. |
| <a id="ELOBF52"></a>ELOBF52 | [BF52](#BF52) | **Representação** | Este elo formaliza que o requisito [RNF01](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RNF01), que determina a adaptação automática da interface ao perfil do usuário (aluno, monitor, professor, etc.), é representado pela funcionalidade de personalização dinâmica da interface do sistema. |
| <a id="ELOBF56"></a>ELOBF56 | [BF56](#BF56) | **Recurso** | Este elo estabelece que o requisito [RNF05](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#RNF05), que exige o uso de recursos tecnológicos alinhados à Teoria da Aprendizagem Significativa (TAS), está vinculado ao recurso de integração pedagógica e metodológica do sistema, assegurando a coerência com os princípios da TAS. |


<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

---

## Agradecimentos
O Grupo 03 agradece o apoio das ferramentas de Inteligência Artificial Generativa — **ChatGPT, GitHub Copilot, Google Gemini e DeepSeek** — na revisão gramatical e de estilo deste artigo. As tecnologias foram utilizadas para tornar o texto mais claro, objetivo e fácil de ler. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Referências

SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 26. Disponível em: [Requisitos_Aula 26](../arquivos/Requisitos%20-%20aula26-milene-modelagem.pdf). Acesso em: 24 outubro 2025.


## Históricos de versão

| Versão | Data       | Descrição  | Autor(es)        | Revisor    |
|--------|------------|---------------------------------------------|----|---------------|
| 1.0    | 23/10/2025 | Criação do documento de Backward-From | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)| [Arthur Guilherme](https://github.com/ArthurGuilher62) |
| 1.1    | 25/10/2025 | Adição dos Forward-From: [BF06](#BF06), [BF15](#BF15), [BF18](#BF18), [BF19](#BF19), [BF21](#BF21), [BF22](#BF22), [BF34](#BF34), [BF35](#BF35), [BF52](#BF52) e [BF56](#BF56). Além da criação dos elos do mesmo intervalo [ELOBF06](#ELOBF06), [ELOBF15](#ELOBF15), [ELOBF18](#ELOBF18), [ELOBF19](#ELOBF19), [ELOBF21](#ELOBF21), [ELOBF22](#ELOBF22), [ELOBF34](#ELOBF34), [ELOBF35](#ELOBF35), [ELOBF52](#ELOBF52) e [ELOBF56](#ELOBF56) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)| [Arthur Guilherme](https://github.com/ArthurGuilher62) |
