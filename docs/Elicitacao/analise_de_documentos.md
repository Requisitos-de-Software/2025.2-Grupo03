# Análise de Documentos 

Os requisitos a seguir foram **elicitados por meio da técnica de Análise de Documentos**.  
O vídeo no qual foi realizada a análise de documentos pode ser conferido em: [https://www.youtube.com/watch?v=ks_NzAzg-g4](https://www.youtube.com/watch?v=ks_NzAzg-g4).  

A elicitação utilizou como base as seguintes páginas do SAE:  
- [Conheça o SAE](https://sae.unb.br/ajudasae/conhecasae/conteudos/projeto.html), para os **requisitos funcionais e não-funcionais**;  
- [Trabalhos Futuros](https://sae.unb.br/ajudasae/conhecasae/conteudos/trabalhosFuturos.html), para os **requisitos não implementados**.  

> Observação: Como a parte de requisitos não implementados foi retirada da página *Trabalhos Futuros* do próprio SAE, alguns dos requisitos listados como "não implementados" já foram implementados ou parcialmente adicionados ao decorrer do tempo.  

Eles estão organizados em três categorias: **Requisitos Funcionais**, **Requisitos Não-Funcionais** e **Requisitos Não Implementados**.  
Além disso, são apresentados os diferentes **perfis de usuários** do sistema e sua forma de interação com os módulos.

## Integrantes do Grupo

A Tabela 1 apresenta todos os integrantes da equipe que participaram da etapa de Análise de Documentos, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes envolvidos</strong></div>

| **Nome** | **Quais etapas participou** |
|------|-------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) | Criação do documento e realização da Análise de Documentos |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento e realização da Análise de Documentos |

<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong>
</div>


---
## Requisitos Funcionais

<div align="center"><strong>Tabela 2: Requisitos Funcionais</strong></div>

| ID   | Módulo | Descrição |
|------|--------|-----------|
| RF01 | **Banco de Questões (BDQ)** | O sistema deve permitir a criação e organização de questões interativas para apoiar o ensino-aprendizagem. |
| RF02 | **Banco de Questões (BDQ)** | Deve promover a interação dos alunos com as questões, avaliando seu conhecimento informativo e formativo. |
| RF03 | **Banco de Questões (BDQ)** | O SAE deve fornecer assistência para professores e alunos neste módulo. |
| RF04 | **Projeto de Monitoria Estudantil (PMon)** | O sistema deve facilitar a interação entre monitores, professores e alunos. |
| RF05 | **Projeto de Monitoria Estudantil (PMon)** | Deve fornecer chat síncrono para interação a distância. |
| RF06 | **Projeto de Monitoria Estudantil (PMon)** | O assistente virtual deve acompanhar interações e fornecer dados relevantes. |
| RF07 | **Projeto de Monitoria Estudantil (PMon)** | Deve disponibilizar informações sobre horários e locais de monitoria. |
| RF08 | **Acadêmico (Maior)** | O sistema deve identificar cada indivíduo (aluno, monitor, professor, coordenador, diretor, administrador) e seu perfil. |
| RF09 | **Acadêmico (Maior)** | Deve mapear conceitos relacionados ao conteúdo, respeitando a hierarquia da Teoria da Aprendizagem Significativa (TAS). |
| RF10 | **Sistema Tutor Inteligente (STI)** | O assistente virtual deve fornecer orientação pedagógica individualizada, baseada na TAS e no desejo didático dos docentes. |
| RF11 | **Sistema Tutor Inteligente (STI)** | Deve analisar a situação cognitiva de cada aluno e atuar como agente colaborativo na aprendizagem. |
| RF12 | **Interface Animado (MInA)** | O sistema deve criar um personagem antropomórfico para interação direta com o estudante. |
| RF13 | **Interface Animado (MInA)** | A interação deve visar a compreensão da situação de aprendizagem. |
| RF14 | **Interface Animado (MInA)** | A inferência deve envolver **Lógica Fuzzy**, permitindo avaliações graduais (ex.: "bom", "razoável", "fraco"). |
| RF15 | **Acompanhamento Real (Real)** | O sistema deve agregar o processo formal de avaliação (Plano de Ensino) com o ambiente virtual. |
| RF16 | **Acompanhamento Real (Real)** | Deve integrar a avaliação docente com as inferências do SAE. |
| RF17 | **Acompanhamento Real (Real)** | O assistente virtual deve combinar resultados formais com inferências Fuzzy. |
| RF18 | **Cooperação (Integra)** | O sistema deve integrar outros softwares educacionais (como AVAs). |
| RF19 | **Cooperação (Integra)** | Deve reduzir o esforço de professores e monitores, centralizando informações sobre atividades e desempenho. |
| RF20 | **Apoio a Decisão (MAD)** | O sistema deve fornecer dados e informações analíticas em diferentes níveis (individual, turma, entre turmas). |
| RF21 | **Apoio a Decisão (MAD)** | As análises devem ser em tempo real e apresentadas em gráficos (barra, coluna, linha, pizza). |
| RF22 | **Apoio a Decisão (MAD)** | Deve mostrar como o desempenho está sendo calculado. |
| RF23 | **Conteúdo (SRC)** | O sistema deve direcionar cada aluno a materiais adequados à sua situação cognitiva e preferências. |
| RF24 | **Conteúdo (SRC)** | Deve manter coerência com o estado cognitivo e permitir que professores adicionem/mudem conteúdos. |



<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>


---

## Requisitos Não-Funcionais

<div align="center"><strong>Tabela 3: Requisitos Não-Funcionais</strong></div>

| ID  | Categoria     | Descrição |
|-----|---------------|-----------|
| RNF01 | **Usabilidade** | - A interface deve se adaptar automaticamente ao perfil de cada indivíduo (aluno, monitor, professor, etc.). |
| RNF02 | **Acessibilidade** | - O sistema deve ser acessível pela internet, presencial ou a distância. |
| RNF03 | **Interação** | - O ambiente deve ter tempo de resposta de até 1 segundo para todos os perfis de usuários. |
| RNF04 | **Arquitetura** | - Deve se basear na extensão de um Sistema Tutor Inteligente (STI) para um Assistente Virtual de Ensino Inteligente (ITA). |
| RNF05 | **Metodologia** | - Deve empregar recursos tecnológicos alinhados à Teoria da Aprendizagem Significativa (TAS). |
| RNF06 | **Manutenção** | - Projeto multidisciplinar envolvendo Educação, Psicologia e Informática. |
| RNF07 | **Desempenho** | - As análises do módulo MAD devem ser realizadas em tempo real. |


<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>


---

## Requisitos Não Implementados

<div align="center"><strong>Tabela 4: Requisitos Não Implementados</strong></div>

| Categoria | Descrição |
|-----------|-----------|
| **Novos Módulos e Integrações** | - Sistema de Recomendação de Conteúdo (já adicionado).<br>- Agente Inteligente (já adicionado).<br>- Interação com AVAs externos (ex.: Moodle). |
| **Expansão da Lógica Fuzzy** | - Incorporar novas variáveis linguísticas.<br>- Acompanhar avaliações formais (provas, trabalhos).<br>- Usar dados históricos de orientação (parcialmente adicionado).<br>- Acompanhar postura didático-pedagógica dos docentes. |
| **Melhorias Técnicas e de Interface** | - Novos relatórios estratégicos.<br>- Melhorar interface para exercícios.<br>- Criar interface para dados históricos.<br>- Melhorar gerenciamento de conexões com bases de dados. |

<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>



---

## Perfis de Usuários

### 1. Perfil do Aluno

<div align="center"><strong>Tabela 5: Perfil do Aluno</strong></div>

| Campo | Descrição |
|-------|-----------|
| **Identificação** | Reconhecido pelo sistema, com perfil adaptado. |
| **Interação** | - BDQ: Resolve questões interativas.<br>- PMon: Busca auxílio pedagógico via chat ou presencialmente.<br>- STI: Recebe orientação pedagógica individualizada.<br>- MInA: Interage com personagem antropomórfico.<br>- SRC: Acessa materiais de estudo personalizados. |
| **Finalidade** | Melhorar aprendizagem, obter apoio pedagógico, acompanhar progresso. |

<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>

---

### 2. Perfil do Professor/Docente

<div align="center"><strong>Tabela 6: Perfil do Professor/Docente</strong></div>

| Campo | Descrição |
|-------|-----------|
| **Identificação** | Reconhecido pelo sistema. |
| **Interação** | - BDQ: Define e organiza questões.<br>- PMon: Colabora com alunos e monitores.<br>- STI: Orienta o assistente virtual.<br>- Real: Integra avaliações formais com análises do SAE.<br>- Integra: Centraliza atividades e resultados.<br>- MAD: Usa análises para decisões estratégicas. |
| **Finalidade** | Apoiar ensino, avaliar alunos, tomar decisões baseadas em dados. |

<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>

---

### 3. Perfil do Monitor

<div align="center"><strong>Tabela 7: Perfil do Monitor</strong></div>

| Campo | Descrição |
|-------|-----------|
| **Identificação** | Reconhecido pelo sistema. |
| **Interação** | - PMon: Atende alunos presencialmente ou via chat. |
| **Finalidade** | Oferecer auxílio pedagógico. |

<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>

---

### 4. Perfil do Coordenador/Diretor

<div align="center"><strong>Tabela 8: Perfil do Coordenador/Diretor</strong></div>

| Campo | Descrição |
|-------|-----------|
| **Identificação** | Reconhecido pelo sistema. |
| **Interação** | - MAD: Acessa dados e análises para decisões estratégicas. |
| **Finalidade** | Gerenciar o processo educacional. |

<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>

---

### 5. Perfil do Administrador

<div align="center"><strong>Tabela 9: Perfil do Administrador</strong></div>

| Campo | Descrição |
|-------|-----------|
| **Identificação** | Reconhecido pelo sistema. |
| **Interação** | Controle e operação do SAE. |
| **Finalidade** | Garantir funcionamento do sistema. |

<div align="center">
  <strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e de <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a></strong>
</div>

---

## Referências

SAE, Sistema de Apoio Educacional. Disponível em: [https://sae.unb.br/ajudasae/conhecasae/conteudos/projeto.html](https://sae.unb.br/ajudasae/conhecasae/conteudos/projeto.html). Acesso em: 20 set. 2025.  

SAE, Trabalhos Futuros. Disponível em: [https://sae.unb.br/ajudasae/conhecasae/conteudos/trabalhosFuturos.html](https://sae.unb.br/ajudasae/conhecasae/conteudos/trabalhosFuturos.html). Acesso em: 20 set. 2025.  

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 20/09/2025 | Criação da página de Análise de Documentos | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) e [Arthur Guilherme](https://github.com/ArthurGuilher62) | [Vilmar José](https://github.com/VilmarFagundes) |
| 1.1    | 27/09/2025 | Alteração nas tabelas | [Felipe Guimaraes](https://github.com/felipegf1) | [Arthur Vieira](https://github.com/arthurhvieira1) |
| 1.2    | 07/11/2025 | Atualização da página | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | [Vilmar José](https://github.com/VilmarFagundes) |
