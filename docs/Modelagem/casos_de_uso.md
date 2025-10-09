# Diagrama e Especificação de Casos de Uso

## Introdução
Um caso de uso é uma descrição detalhada de como os usuários de um sistema, neste trabalho o **SAE (Sistema de Apoio Educacional)**, interagem com ele em situações específicas. Ele apresenta passo a passo as ações realizadas pelo usuário e as respostas do sistema a essas interações.
O principal objetivo dos casos de uso é apoiar o desenvolvimento do aplicativo, oferecendo uma visão clara e prática dos requisitos funcionais. Eles ajudam a definir o comportamento esperado do sistema diante das ações dos usuários, garantindo que as funcionalidades realmente atendam às necessidades dos usuários.
No âmbito da disciplina, estão sendo levadas em conta as funcionalidades ainda não-implementadas para a realização do diagrama de caso de uso, assim como de suas especificações.


## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da construção dos Casos de Uso, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) | Criou as especificações de casos de uso 07, 08 e 09, que são referentes, respectivamente, aos requisitos [RF50](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF51](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF52](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)|
| [Arthur Henrique](https://github.com/arthurhvieira1) |                                       |
| [Felipe Guimaraes](https://github.com/felipegf1) |                                       |
| [João Felipe](https://github.com/MrBolt2005) |                                       |
| [João Sapiência](https://github.com/JoaoSapiencia) |                                       |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Casos de Uso e criação das especificações de casos de uso 04, 05 e 06, que são referentes, respectivamente, aos requisitos [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais), [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) e [RF20](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais).                                      |
| [Vilmar José](https://github.com/VilmarFagundes) |                                       |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Metodologia
Foi utilizado o diagrama de caso de uso, que representa, por meio de atores (como alunos e docentes) e casos de uso (como escolher o melhor modo de receber notificações), as funcionalidades ainda não implementadas e os comportamentos esperados do sistema em uma hipótese de implementação.
Com base nesses conceitos, a Tabela 2 apresenta os principais elementos que compõem o diagrama de caso de uso, oferecendo uma visão organizada da estrutura de interações entre os atores e o sistema.

## Diagramas de Caso de Uso

## Especificação dos Casos de Uso

### **UC01 – Exibição do Progresso na Disciplina**
**Requisito Associado:** [RF08](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – A interface deve exibir um progresso em porcentagem do andamento da disciplina

<div align="center"><strong>Tabela 2: Caso de Uso UC01</strong></div>

| Campo   | Descrição  |
| --------------------- | -------------- |
| **UC06**              | Exibição do Progresso na Disciplina   |
| **Descrição**         | O sistema calcula e exibe, em formato percentual, o progresso do aluno em cada disciplina com base nos conteúdos concluídos.   |
| **Ator**          | - Aluno <br> - Sistema de acompanhamento de progresso  |
| **Pré-condições**     | 1. O aluno está logado na plataforma. <br>2. O aluno possui disciplinas cadastradas com conteúdos disponíveis.   |
| **Ação**          | O sistema coleta os dados de conteúdos concluídos e calcula a porcentagem de progresso para exibição na interface.|
| **Fluxo principal**   | - O aluno acessa a página da disciplina. <br>- O sistema verifica o número total de conteúdos e os já concluídos. <br>- O sistema calcula o percentual de progresso. <br>- A interface exibe o progresso do aluno em formato percentual (ex.: “Progresso: 75%”). |
| **Fluxo alternativo** | - O aluno ainda não iniciou nenhum conteúdo. <br>- O sistema exibe “Progresso: 0%”. |
| **Fluxo de exceção**  | - Erro na recuperação dos dados do aluno ou das disciplinas. <br>- O sistema exibe uma mensagem de erro (“Não foi possível carregar o progresso no momento”).  |
| **Pós-condições**     | O aluno visualiza corretamente seu progresso percentual em cada disciplina. |
| **Rastreabilidade**   | [RF08](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)|
| **Data de criação**   | 08/10/2025       |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

### **UC02 – Exibição da Porcentagem de Acertos por Conteúdo**
**Requisito Associado:** [RF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – A interface deve exibir como está a porcentagem de acertos das atividades de cada conteúdo

<div align="center"><strong>Tabela 3: Caso de Uso UC02</strong></div>

| Campo                 | Descrição     |
| --------------------- | ----------------------------------------------- |
| **UC07**              | Exibição da Porcentagem de Acertos por Conteúdo |
| **Descrição**         | O sistema calcula e exibe, em formato percentual, o desempenho do aluno nas atividades de cada conteúdo da disciplina. |
| **Ator**          | - Aluno <br> - Sistema de avaliação de desempenho  |
| **Pré-condições**     | 1. O aluno está logado na plataforma. <br>2. Existem atividades concluídas associadas aos conteúdos da disciplina.   |
| **Ação**  | O sistema coleta os resultados das atividades de cada conteúdo e calcula a porcentagem de acertos, exibindo o valor correspondente na interface. |
| **Fluxo principal**   | - O aluno acessa a página de um conteúdo. <br>- O sistema busca os resultados das atividades realizadas. <br>- O sistema calcula a porcentagem de acertos do aluno naquele conteúdo. <br>- A interface exibe o valor percentual (ex.: “Acertos: 85%”). |
| **Fluxo alternativo** | - O aluno ainda não realizou nenhuma atividade do conteúdo. <br>- O sistema exibe “Acertos: 0%” ou “Sem atividades concluídas”.  |
| **Fluxo de exceção**  | - Falha ao carregar os dados de desempenho. <br>- O sistema exibe uma mensagem de erro (“Não foi possível carregar os resultados”).  |
| **Pós-condições**     | O aluno visualiza o percentual de acertos das atividades cada conteúdo estudado. |
| **Rastreabilidade**   | [RF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Data de criação**   | 08/10/2025  |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

### **UC03 – Exibição da Porcentagem de Erros por Conteúdo**
**Requisito Associado:** [RF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – A interface deve exibir como está a porcentagem de erros das atividades de cada conteúdo

<div align="center"><strong>Tabela 4: Caso de Uso UC03</strong></div>

| Campo                 | Descrição |
| --------------------- | ---------------------------------|
| **UC08**              | Exibição da Porcentagem de Erros por Conteúdo     |
| **Descrição**         | O sistema calcula e exibe, em formato percentual, o índice de erros do aluno nas atividades de cada conteúdo da disciplina.   |
| **Ator**         | - Aluno <br> - Sistema de avaliação de desempenho   |
| **Pré-condições**     | 1. O aluno está logado na plataforma. <br>2. Existem atividades concluídas associadas aos conteúdos da disciplina.  |
| **Ação**              | O sistema coleta os resultados das atividades e calcula a porcentagem de erros de cada conteúdo, exibindo o valor correspondente na interface. |
| **Fluxo principal**   | - O aluno acessa a página de um conteúdo. <br>- O sistema busca os resultados das atividades realizadas. <br>- O sistema calcula a porcentagem de erros com base nas respostas incorretas. <br>- A interface exibe o valor percentual (ex.: “Erros: 15%”). |
| **Fluxo alternativo** | - O aluno ainda não realizou nenhuma atividade do conteúdo. <br>- O sistema exibe “Erros: 0%” ou “Sem atividades concluídas”.  |
| **Fluxo de exceção**  | - Falha ao carregar os dados de desempenho. <br>- O sistema exibe uma mensagem de erro (“Não foi possível carregar os resultados”). |
| **Pós-condições**     | O aluno visualiza o percentual de erros das atividades de cada conteúdo estudado.  |
| **Rastreabilidade**   | [RF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais)|
| **Data de criação**   | 08/10/2025 |

<div align="center"><strong>Autoria de <a href="https://github.com/felipegf1">Felipe Guimaraes</a></strong></div>

---

### **UC04 – Lembretes de Revisão de Conteúdos**
**Requisito Associado:** [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O sistema deve enviar notificações para lembrar o usuário de revisar conteúdos passados.

<div align="center"><strong>Tabela 5: Caso de Uso UC04</strong></div>

| Campo | Descrição |
|-------|------------|
| **UC04** | Lembretes de Revisão de Conteúdos |
| **Descrição** | O sistema identifica conteúdos já estudados e envia lembretes automáticos para revisão. |
| **Ator** | Aluno, Sistema de notificações |
| **Pré-condições** | 1. O aluno possui conteúdos concluídos no banco de dados. <br>2. Está logado no sistema. |
| **Ação** | O sistema agenda e envia lembretes de revisão com base na data do último acesso ao conteúdo. |
| **Fluxo principal** | - O aluno acessa a plataforma.<br>- O sistema verifica conteúdos já estudados.<br>- O sistema envia notificação lembrando o aluno de revisar o conteúdo. |
| **Fluxo alternativo** | - O aluno revisa o conteúdo antes do envio do lembrete.<br>- O sistema cancela o lembrete agendado. |
| **Fluxo de exceção** | - Falha no envio da notificação.<br>- Conteúdo revisado recentemente não gera novo lembrete. |
| **Pós-condições** | O aluno é lembrado de revisar conteúdos anteriores conforme sua configuração de notificações. |
| **Rastreabilidade** | [RF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Data de criação** | 08/10/2025 |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>


---

### **UC05 – Configuração da Forma de Notificação**
**Requisito Associado:** [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O sistema deve pedir ao usuário a melhor forma de caminho de notificação.

<div align="center"><strong>Tabela 6: Caso de Uso UC05</strong></div>

| Campo | Descrição |
|-------|------------|
| **UC05** | Configuração da Forma de Notificação |
| **Descrição** | O usuário acessa as configurações de notificação e escolhe como deseja ser notificado. |
| **Ator(es)** | - Aluno<br> - Docente<br> - Monitor<br> - Coordenador<br> - Administrador<br> - Sistema de configuração de notificações |
| **Pré-condições** | 1. O usuário está logado. <br>2. O sistema possui diferentes canais de envio disponíveis. |
| **Ação** | O usuário seleciona o canal preferido de notificação e salva suas preferências. |
| **Fluxo principal** | - O usuário acessa “Preferências de Notificação”.<br>- Escolhe o canal preferido (push, WhatsApp, e-mail, alerta no sistema).<br>- O sistema salva a configuração. |
| **Fluxo alternativo** | - O usuário não escolhe nenhuma opção.<br>- O sistema mantém o canal padrão. |
| **Fluxo de exceção** | - O canal selecionado está temporariamente indisponível.<br>- O sistema exibe mensagem de erro e mantém o padrão. |
| **Pós-condições** | As notificações passam a ser enviadas conforme a escolha do usuário. |
| **Rastreabilidade** | [RF19](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Data de criação** | 08/10/2025 |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>


---

### **UC06 – Notificação de Prazo de Entrega**
**Requisito Associado:** [RF20](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O sistema deve enviar uma notificação quando está chegando perto da data de entrega de uma atividade.

<div align="center"><strong>Tabela 7: Caso de Uso UC06</strong></div>

| Campo | Descrição |
|-------|------------|
| **UC06** | Notificação de Prazo de Entrega |
| **Descrição** | O sistema envia alertas automáticos ao aluno quando uma atividade está próxima do prazo final. |
| **Ator** | Aluno, Sistema de notificações |
| **Pré-condições** | 1. O aluno possui atividades cadastradas com prazo de entrega. <br>2. Está logado no sistema. |
| **Ação** | O sistema verifica prazos e envia alertas automáticos próximos da data limite. |
| **Fluxo principal** | - O sistema verifica atividades com prazo próximo.<br>- Gera alerta de prazo.<br>- Envia notificação ao aluno. |
| **Fluxo alternativo** | - O aluno já entregou a atividade.<br>- O sistema não envia mais alertas. |
| **Fluxo de exceção** | - Falha no envio da notificação.<br>- O prazo da atividade é alterado após o envio do alerta. |
| **Pós-condições** | O aluno recebe lembrete sobre a entrega das atividades no tempo adequado. |
| **Rastreabilidade** | [RF20](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) |
| **Data de criação** | 08/10/2025 |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### UC07 – Análise Cognitiva e Apoio à Aprendizagem  
**Requisito Associado:** [RF50](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O sistema deve analisar documentos escolares (atividades e provas) para identificar dificuldades cognitivas e sugerir estratégias de reforço ao aluno.


| Campo      | Descrição |
|----------------|-----------|
|UC07 |Análise Cognitiva e Apoio à Aprendizagem|
| Descrição |O sistema analisa documentos escolares do aluno para identificar dificuldades cognitivas e sugere estratégias de reforço personalizadas.|
| Ator| - Aluno <br> - Professor  <br>- Assistente Virtual|
| Pré-condições| 1. O aluno possui documentos escolares disponíveis. <br> 2. O sistema está com acesso autorizado aos dados.|
| Ação| O sistema realiza análise cognitiva dos documentos e propõe estratégias de reforço.|
|Fluxo principal|- O sistema acessa os documentos escolares. <br> - Identifica padrões de dificuldade.  <br>- Sugere conteúdos adaptados.  <br>- Monitora evolução do aluno.|
|Fluxo alternativo|- Documentos insuficientes para análise.  <br> - Dados corrompidos ou inconsistentes.|
|Fluxo de exceção|- Falha na análise cognitiva.  <br> - Estratégias sugeridas não são compatíveis com o perfil do aluno.|
|*Pós-condições| O aluno recebe sugestões personalizadas para reforço de aprendizagem.|
|Rastreabilidade| RF50 |
|Data de criação| 08/10/2025 |
<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>


---

### UC08 – Identificação de Conhecimento sobre o Conteúdo  
**Requisito Associado:** [RF51](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O sistema deve apresentar ao professor qual aluno sabe sobre o conteúdo, com base em provas e atividades.


| Campo      | Descrição |
|----------------|-----------|
|UC08 |Identificação de Conhecimento sobre o Conteúdo|
| Descrição |O sistema analisa provas e atividades dos alunos e apresenta ao professor o nível de domínio por conteúdo.|
| Ator|- Professor  <br> - Sistema de Avaliação Inteligente|
| Pré-condições| 1. Os alunos realizaram provas e atividades.  <br>2. Os dados estão disponíveis e corrigidos.|
| Ação| O sistema aplica Lógica Fuzzy para avaliar o domínio de conteúdo e apresenta os resultados ao professor.|
|Fluxo principal|- O sistema processa os resultados.  <br>- Avalia o domínio por conteúdo.  <br>- Exibe painel de desempenho.  <br>- Destaca alunos com dificuldades.|
|Fluxo alternativo|- Provas não corrigidas ou com erros.  <br>- Dados insuficientes para análise.|
|Fluxo de exceção|- Falha na aplicação da Lógica Fuzzy.  <br>- Erro na geração do painel de desempenho.|
|*Pós-condições| O professor visualiza o nível de conhecimento dos alunos por conteúdo.|
|Rastreabilidade| RF51  |
|Data de criação| 08/10/2025 |
<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>

---

### UC09 – Avaliação de Comportamento Escolar  
**Requisito Associado:** [RF52](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#funcionais) – O sistema deve informar ao professor quais alunos mantêm comportamento adequado segundo critérios pedagógicos.

| Campo      | Descrição |
|----------------|-----------|
|UC08 |Avaliação de Comportamento Escolar|
| Descrição |O sistema monitora o comportamento dos alunos e gera relatórios para o professor com base em critérios pedagógicos.|
| Ator|- Aluno  <br>- Professor  <br>- Assistente Virtual|
| Pré-condições| 1. O aluno está registrado no sistema.  <br>2. Há dados de presença, atividades e monitorias disponíveis.|
| Ação| O sistema analisa os dados comportamentais e gera relatório para o professor.|
|Fluxo principal|- Registra presença nas aulas.  <br>- Monitora participação em monitorias.  <br>- Verifica entrega de atividades.  <br>- Acompanha estudo de conteúdos.  <br>- Gera relatório de comportamento.  <br>- Professor acessa o relatório.|
|Fluxo alternativo|- Dados incompletos ou não sincronizados.  <br>- Aluno ausente em todas as atividades.|
|Fluxo de exceção|- Falha na geração do relatório.  <br>- Dados corrompidos ou inconsistentes.|
|*Pós-condições| O professor recebe relatório com avaliação comportamental dos alunos.|
|Rastreabilidade| RF52  |
|Data de criação| 08/10/2025 |
<div align="center"><strong>Autoria de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong></div>
## Referências

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 05/10/2025 | Criação do documento dos Cados de Uso | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [Vilmar José](https://github.com/VilmarFagundes) |
| 1.1    | 08/10/2025 | Criação das especificações de casos de uso 04, 05 e 06 | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [João Felipe](https://github.com/MrBolt2005) |
| 1.2    | 08/10/2025 | Criação das especificações de casos de uso 07, 08 e 09 | [Arthur Guilherme](https://github.com/ArthurGuilher62) |  |# Diagrama e Especificação de Casos de Uso
| 1.3    | 08/10/2025 | Criação das especificações de casos de uso 01, 02 e 03 | [Felipe Guimaraes](https://github.com/felipegf1) |  [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |
