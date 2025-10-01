# Entrevista 

## Introdução 

Como parte do entendimento do sistema **SAE**, foi realizado uma entrevista com o desenvolvedor e usuário do sistema, com o objetivo de coletar expectativas, necessidades e desafios no uso de um sistema acadêmico com tutor inteligente.

## Integrantes 

Na Tabela 1 estão todos os integrantes da equipe que participaram desta etapa de entrevista e as atividades desenvolvidas por cada um.

<div align="center"><strong>Tabela 1: Integrantes envolvidos</strong></div>

| **Nome** | **Quais etapas participou** |
|------|-------------------------|
| Arthur Henrique | Ajudou no desenvolvimento das perguntas, Executou a gravação da entrevista |
| Tiago Lemes | Ajudou no desenvolvimento das perguntas, Participou da entrevista como secretário, transcreveu respostas, auxiliou na elicitação de requisitos |
| Vilmar José | Realizou a entrevista, publicou video no YouTube (não listado), auxiliou na elicitação de requisitos, estruturou a documentação final da entrevista|

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar José Fagundes</a></strong></div>

## Usuário real envolvido 

<div align="center"><strong>Tabela 2: Usuario envolvido</strong></div>

| **Nome** | **Data** | **Hora** | **Local** | **Duração** |
|----------|----------|----------|-----------|-------------|
| Vandor Roberto Vilardi Rissoli | 25/09 | 10:30 | Sala do professor no UED | 32:58 |

<div align="center"><strong>Autoria de <a href="https://github.com/VilmarFagundes">Vilmar José Fagundes</a></strong></div>

## Metodologia 

A elicitação de requisitos foi conduzida pelos integrantes [Vilmar José](https://github.com/VilmarFagundes) [Tiago Lemes](https://github.com/TiagoTeixeira-2005) em quatro fases: preparação, execução da entrevista, análise e documentação.

### Preparação

- Definição do roteiro: elaboramos  9 perguntas abertas, cobrindo aspectos de contexto de uso, funcionalidades essenciais, limitações, e dificuldades tanto do ponto de vista de usuário professor e de desenvolvedor. 
- Validação interna: o roteiro foi revisado pelos integrantes responsáveis, garantindo clareza, objetividade e adequação ao público-alvo.
- Consentimento informado: No inicio da gravação foi feito uma pergunta sobre o consentimento do entrevistado pedindo permissão a autorização do uso de sua imagem e áudio.

### Execução da entrevista 
- Ambiente: realizadas presencialmente em locais escolhidos pelos usuários (Sala do professor) para maior conforto e segurança.
- Registro audiovisual: cada sessão foi gravada em vídeo e áudio. Os arquivos foram enviados ao canal de um dos integrantes e publicado de forma não listada no Youtube.
- Roteiro flexível: embora o conjunto de perguntas tenha sido pré-estabelecido, a ordem pôde ser adaptada conforme o fluxo da conversa, permitindo exploração de respostas relevantes que surgissem espontaneamente.
- Escuta ativa: durante a entrevista, os analistas adotaram postura de escuta ativa, incentivando o participante a detalhar experiências e expor dor e ganhos percebidos.

### Organização dos requisitos 

- Classificação inicial: cada trecho relevante foi enquadrado como Requisito Funcional (RF) ou Requisito Não Funcional (RNF) cada requisito possui um indentificador único com o tipo do requisito e um numero em seguida (RF01, RNF01).

### Documentação final 
- Todos os artefatos (roteiro, transcrições, vídeos, tabela de requisitos) foram consolidados em um repositório GitHub e publicados via GitHub Pages.
- A metodologia, incluindo termo de consentimento e roteiro, está disponível para auditoria e replicação em futuras fases do projeto.

## Resultados

### Roteiro da entrevista 

O roteiro foi elaborado em conjunto por [Artur Henrique](https://github.com/arthurhvieira1) e [Tiago Lemes](https://github.com/TiagoTeixeira-2005) seguindo a ordem das questões elaboradas, o documento das questões está disponível em PDF [aqui](../arquivos/entrevistaVandor%20(1).pdf).

### Gravação 

A gravação da entrevista está contida no link a seguir: https://youtu.be/eK-qXv4SoGc

### Requisitos Elicitados

A tabela 3 apresenta os requistos funcionais extraidos e a tabela 4 apresenta os requisitos não funcionais extraidos, com indentificador descrição.

<div align="center"><strong>Tabela 3: Requisitos funcionais extraídos</strong></div>

| ID   | Descrição                                                                                                     | Técnicas | Implementado |
|------|---------------------------------------------------------------------------------------------------------------|----------|--------------|
| RF46 | O sistema deve identificar e registrar o comportamento do estudante.                                          | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RF47 | O sistema deve destacar padrões inadequados de comportamento dos estudantes.                                  | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RF48 | O sistema deve permitir a criação e visualização de dashboards com dados de desempenho dos alunos.            | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RF49 | O sistema deve permitir a criação e visualização de gráficos com dados de desempenho dos alunos.              | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RF50 | O sistema deve enviar notificações automáticas para acompanhamento acadêmico.                                 | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RF51 | O sistema deve enviar relatórios automáticos para acompanhamento acadêmico.                                   | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RF52 | O sistema deve permitir que o usuário escolha o canal de notificação desejado.                                | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RF53 | O sistema deve integrar módulos com outros AVAs.                                                              | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RF54 | O sistema deve oferecer relatórios sobre as aptidões dos estudantes.                                          | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RF55 | O sistema deve oferecer relatórios sobre as habilidades dos estudantes.                                       | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RF56 | O sistema deve oferecer relatórios sobre as competências dos estudantes.                                      | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RF57 | O sistema deve integrar chatbots para suporte imediato a dúvidas dos estudantes.                              | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RF58 | O sistema deve permitir a análise detalhada dos tipos de questões utilizadas para avaliação de perfil.         | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RF59 | O sistema deve fornecer relatórios específicos de progresso dos estudantes.                                   | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RF60 | O sistema deve comparar ensino e aprendizagem ao longo do curso.                                              | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RF61 | O sistema deve analisar a origem das dificuldades do aluno (ex.: matérias anteriores, defasagem nos estudos). | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

<div align="center"><strong>Tabela 4: Requisitos não funcionais extraídos</strong></div>

| ID    | Descrição                                                                                       | Técnicas | Implementado |
|-------|-------------------------------------------------------------------------------------------------|----------|--------------|
| RNF08 | O sistema deve garantir que os dados dos estudantes sejam armazenados de forma segura e criptografada. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RNF09 | O sistema deve estar disponível 24 horas por dia, 7 dias por semana, com tempo de indisponibilidade máximo de 1% ao mês. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RNF10 | O tempo de resposta para carregamento de dashboards e gráficos deve ser inferior a 3 segundos.   | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RNF11 | O sistema deve ser compatível com dispositivos móveis (responsividade).                          | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RNF12 | O sistema deve seguir padrões de acessibilidade para garantir usabilidade a todos os usuários. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RNF13 | O sistema deve possibilitar integração com outros AVAs e sistemas educacionais externos. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RNF14 | O sistema deve permitir escalabilidade para atender um número crescente de alunos e módulos sem perda de desempenho. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RNF15 | O sistema deve garantir a privacidade dos dados dos estudantes em conformidade com a LGPD.       | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim|

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Referencias 

Vazquez, Carlos Eduardo; Simões, Guilherme Siqueira. Engenharia de requisitos: software orientado ao negócio. Rio de Janeiro, 2016. Disponível em: https://www.kufunda.net/publicdocs/Engenharia%20de%20Requisitos%20software%20orientado%20ao%20negócio%20(Carlos%20Eduardo%20Vazquez%20etc.).pdf. Acesso em: 30 set. 2025.

Robby. Elicitation Interview Questions. Your Career Support. 24 out. 2022. Disponível em: https://yourcareersupport.com/elicitation-interview-questions/. Acesso em: 30 SET. 2025.

## Histórico de versões 
| Versão | Data | Descrição | Autor(es) | Revisor |
|------------|----------|---------------|---------------|-----------------|
| 1.0 | 30/09 | Criação da documentação da entrevista | [Vilmar José](https://github.com/VilmarFagundes) | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
