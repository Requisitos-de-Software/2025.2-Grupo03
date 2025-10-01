# Requisitos Elicitados

## Introdução

Esta página consolida os requisitos identificados para o projeto, eliciados por meio das técnicas Análise de documento,Entrevista e Brainstorming. O processo de levantamento priorizou a compreensão das necessidades dos usuários e a conformidade com normas técnicas, garantindo clareza e alinhamento aos objetivos propostos.

## Requisitos

Os requisitos foram organizados em duas tabelas: a Tabela 1 apresenta os Requisitos Funcionais, enquanto a Tabela 2 lista os Requisitos Não Funcionais.

Legenda das Tabelas:

- RFx: Requisito Funcional número x;
- RNFx: Requisito Não Funcional número x;

### Funcionais

Tabela 1: Requisitos Funcionais

| ID   | Descrição | Técnicas | Implementado |
|------|-----------|----------|--------------|
| RF01 | O sistema deve identificar cada indivíduo (aluno, monitor, professor, coordenador, diretor, administrador)                 | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF02 | O sistema deve ter perfil individual                   | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF03 | Deve mapear conceitos relacionados ao conteúdo, respeitando a hierarquia da Teoria da Aprendizagem Significativa (TAS).                                                     | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF04 | O sistema deve agregar o processo formal de avaliação (Plano de Ensino) com o ambiente virtual.                                                | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF05 | Deve integrar a avaliação docente com as inferências do SAE.                                                                     | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF06 | O assistente virtual deve combinar resultados formais com inferências Fuzzy.                                                | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF07 | A interface deve conter o progresso do aluno na disciplina toda                                                      | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados)| Sim          |
| RF08 | A interface deve exibir um progresso em porcentagem do andamento da disciplina    | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF09 | A interface deve exibir como está a porcentagem de acertos das atividades de cada conteúdo    | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF10 | A interface deve exibir como está a porcentagem de erros das atividades de cada conteúdo | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF11 | A interface deve exibir a média geral da turma em cada atividade                        | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados)| Sim          |
| RF12 | A interface deve exibir a média do usuário após a atividade                                    | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF13 | O usuário deve escolher o tempo em que deseja receber alertas sobre atividades atrasadas                                                           | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF14 | O usuário deve marcar os tópicos da disciplina no qual ele sente mais facilidade              | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF15 | O sistema deve enviar notificações para lembrar o usuário de revisar conteúdos passados                            | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF16 | O sistema deve ter um índice de conteúdos ordenado pela porcentagem de erros em cada conteúdo                                                                | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF17 | O sistema deve enviar lembretes para o usuário sobre datas de entregas de atividades                                               | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados)| Sim          |
| RF18 | O sistema deve possuir vídeo aula                                                          | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Não          |
| RF19 | O sistema deve pedir ao usuário a melhor forma de caminho de notificação                | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF20 | O sistema deve enviar uma notificação quando está chegando perto da data de entrega de uma atividade            | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF21 | O usuário escolhe quando ele recebe a notificação de proximidade da data de entrega de atividade                             | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF22 | O sistema deve fornecer dados e informações analíticas em diferentes níveis (individual, turma, entre turmas)                                                                     | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF23 | As análises devem ser em tempo real e apresentadas em gráficos (barra, coluna, linha, pizza).                        | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF24 | Deve mostrar como o desempenho está sendo calculado.                        | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF25 | O sistema deve permitir a criação e organização de questões interativas para apoiar o ensino-aprendizagem.         | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF26 | Deve promover a interação dos alunos com as questões, avaliando seu conhecimento informativo e formativo.    | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF27 | O SAE deve fornecer assistência para professores neste módulo | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF28 | O SAE deve fornecer assistência para alunos neste módulo.                    | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF29 | O sistema deve conter um banco de questões geradas pelo professor         | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF30 | O banco de questões do sistema deve conter questões de outras origens | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Não          |
| RF31 | O sistema deve direcionar cada aluno a materiais adequados à sua situação cognitiva e preferências. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim          |
| RF32 | Os materiais devem estar postados em tópicos de conteúdos separados na disciplina         | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Não          |
| RF33 | O banco de questões deve estar separado por conteúdo            | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF34 | O sistema deve integrar outros softwares educacionais (como AVAs). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Não         |
| RF35 | A integração deve reduzir o esforço de professores e monitores, centralizando informações sobre atividades e desempenho. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Não         |
| RF36 | O sistema deve criar um personagem antropomórfico para interação direta com o estudante. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Não         |
| RF37 | A interação deve visar a compreensão da situação de aprendizagem. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Não         |
| RF38 | A inferência deve envolver Lógica Fuzzy, permitindo avaliações graduais (ex.: "bom", "razoável", "fraco"). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Não         |
| RF39 | O assistente virtual deve ser visível na interface | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Não         |
| RF40 | O assistente virtual deve ser customizável pelo usuário                                    | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF41 | O assistente virtual deve sugerir questões com o conteúdo da vídeo aula                      | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF42 | O assistente virtual deve notificar qual conteúdo o aluno está tendo mais dificuldade              | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Não         |
| RF43 | O assistente virtual deve notificar o professor da disciplina com que parte do conteúdo os alunos estão tendo mais dificuldade   | [Brainstorming](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/brainstorming/#requisitos-elicitados) | Sim          |
| RF44 | O sistema deve facilitar a interação entre monitores, professores e alunos. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim        |
| RF45 | Deve fornecer chat síncrono para interação a distância. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim        |
| RF46 | O assistente virtual deve acompanhar interações                                        | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Não |
| RF47 | O assistente virtual deve fornecer dados relevantes ao usuário (progresso do aluno)                                | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Não |
| RF48 | Deve disponibilizar informações sobre horários e locais de monitoria.           | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim |
| RF49 | O assistente virtual deve fornecer orientação pedagógica individualizada, baseada na TAS e no desejo didático dos docentes.             | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Sim |
| RF50 | O assistente virtual deve analisar a situação cognitiva de cada aluno e atuar como agente colaborativo na aprendizagem.                              | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-funcionais) | Não |
| RF51 | O sistema deve apresentar ao professor qual aluno sabe sobre o conteúdo                               | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RF52 | O sistema deve apresentar ao professor qual aluno possui um comportamento adequado (entrega de atividades, presença na aula)                             | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |

<div align="center">
  <strong>Fonte: <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> , <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a> , <a href="https://github.com/felipegf1">Felipe Guimaraes</a> e <a href="https://github.com/VilmarFagundes">Vilmar José</a> </strong>
</div>

### Requisitos Não Funcionais 

Tabela 2: Requisitos Não Funcionais

| ID    | Descrição | Técnicas | Implementado |
|-------|-----------|----------|--------------|
| RNF01 | A interface deve se adaptar automaticamente ao perfil de cada indivíduo (aluno, monitor, professor, etc.). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim |
| RNF02 | O sistema deve ser acessível pela internet, presencial ou a distância. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim |
| RNF03 | O ambiente deve ter tempo de resposta de até 1 segundo para todos os perfis de usuários. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim |
| RNF04 | Deve se basear na extensão de um Sistema Tutor Inteligente (STI) para um Assistente Virtual de Ensino Inteligente (ITA). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim |
| RNF05 | Deve empregar recursos tecnológicos alinhados à Teoria da Aprendizagem Significativa (TAS). | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim |
| RNF06 | Projeto multidisciplinar envolvendo Educação, Psicologia e Informática. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim |
| RNF07 | As análises do módulo MAD devem ser realizadas em tempo real. | [Análise de Documento](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/analise_de_documentos/#requisitos-nao-funcionais) | Sim |
| RNF08 | O sistema deve garantir que os dados dos estudantes sejam armazenados de forma segura e criptografada. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RNF09 | O sistema deve estar disponível 24 horas por dia, 7 dias por semana, com tempo de indisponibilidade máximo de 1% ao mês. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RNF10 | O tempo de resposta para carregamento de dashboards e gráficos deve ser inferior a 3 segundos.   | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RNF11 | O sistema deve ser compatível com dispositivos móveis (responsividade).                          | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RNF12 | O sistema deve seguir padrões de acessibilidade para garantir usabilidade a todos os usuários. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RNF13 | O sistema deve possibilitar integração com outros AVAs e sistemas educacionais externos. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Não |
| RNF14 | O sistema deve permitir escalabilidade para atender um número crescente de alunos e módulos sem perda de desempenho. | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim |
| RNF15 | O sistema deve garantir a privacidade dos dados dos estudantes em conformidade com a LGPD.       | [Entrevista](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/entrevista/) | Sim|

<div align="center">
  <strong>Fonte: <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>


| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 27/09/2025 | Criação da pagina | [Felipe Guimaraes](https://github.com/felipegf1)  |  [Vilmar José](https://github.com/VilmarFagundes) |
