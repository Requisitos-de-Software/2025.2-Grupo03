# Especificação Suplementar

## Introdução
A Especificação Suplementar é um documento essencial no processo de engenharia de requisitos, pois tem o objetivo de detalhar aspectos que não são tratados diretamente nos casos de uso, com foco especial nos **requisitos não funcionais**.
Diferente dos **requisitos funcionais**, que descrevem as ações e comportamentos esperados do sistema, os **requisitos não funcionais** se referem a atributos de qualidade que afetam a experiência do usuário, a estabilidade do sistema e a facilidade de manutenção e evolução do software.  
Entre esses atributos estão: a usabilidade, confiabilidade, desempenho, segurança, portabilidade, entre outros.
Este documento segue o modelo **FURPS+**, que organiza os requisitos não funcionais em cinco categorias principais:

- **Functionality (Funcionalidade)** Representa todos os aspectos funcionais do software.
- **Usability (Usabilidade)** : Refere-se à facilidade de uso e interação do usuário com o sistema. Incluindo subcategorias como prevenção de erros, design e estética, ajuda e documentação,  consistência e padronização na interface e acessibilidade.
- **Reliability (Confiabilidade)** : Refere-se à integridade, conformidade e interoperabilidade do software. Os principais aspectos considerados são: frequência e tolerância a falhas, capacidade de recuperação, previsibilidade, exatidão e tempo médio entre falhas.
- **Performance (Desempenho)** : Avalia a eficiência do sistema em diferentes condições. Pode ser medida por fatores como tempo de resposta, uso de memória, utilização da CPU, capacidade de processamento e disponibilidade da aplicação.
- **Supportability (Manutenibilidade)** : Abrange características relacionadas à facilidade de manutenção e evolução do sistema, incluindo testabilidade, adaptabilidade,  entre outras.


## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da construção da Especificação Suplementar, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) |                                       |
| [Arthur Henrique](https://github.com/arthurhvieira1) |                                       |
| [Felipe Guimaraes](https://github.com/felipegf1) |                                       |
| [João Felipe](https://github.com/MrBolt2005) |                                       |
| [João Sapiência](https://github.com/JoaoSapiencia) |                                       |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação do documento de Especificação Suplementar e classificação dos requisitos não funcionais: [RNF01](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) e [RNF05](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais).                                      |
| [Vilmar José](https://github.com/VilmarFagundes) | Classificação dos requisitos não funcionais: [RNF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais), [RNF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) e [RNF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Metodologia
A Especificação Suplementar foi elaborada de forma colaborativa, seguindo o modelo FURPS+, com o objetivo de organizar os requisitos não funcionais do projeto de maneira clara e objetiva. Os requisitos foram distribuídos nos tópicos Usabilidade, Confiabilidade, Suportabilidade e Desempenho.

A estrutura foi adaptada às particularidades do projeto, utilizando uma linguagem clara e acessível, facilitando a compreensão tanto por leitores com conhecimento técnico quanto por aqueles sem conhecimento técnico.

## Especificação Suplementar Realizada

### 1. Funcionalidade
As funcionalidades foram identificadas durante o processo de elicitação de requisitos e estão detalhadas tanto na seção de [Requisitos Elicitados](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/) quanto nos [Casos de Uso](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/casos_de_uso/) desenvolvidos.

### 2. Usabilidade
Esta seção lista os requisitos que garantem que a interação do usuário com o sistema seja intuitiva, acessível e eficiente, incluindo aspectos como prevenção de erros, design e estética, ajuda e documentação, consistência e padronização na interface e acessibilidade.

<div align="center"><strong>Tabela 2: Requisitos de Usabilidade</strong></div>

| **Requsito** | **Descrição** |
| ------------------- | ---------------- |
| [RNF01](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) | A interface deve se adaptar automaticamente ao perfil de cada indivíduo (aluno, monitor, professor, etc.). |

<div align="center">
    <strong>
        Autoria de 
        <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a>, 
        <a href="https://github.com/arthurhvieira1">Arthur Henrique</a>,
        <a href="https://github.com/felipegf1">Felipe Guimaraes</a>,
        <a href="https://github.com/MrBolt2005">João Felipe</a>,
        <a href="https://github.com/JoaoSapiencia">João Sapiência</a>,
        <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e 
        <a href="https://github.com/VilmarFagundes">Vilmar José</a>
    </strong>
</div>

### 3. Confiabilidade
Esta seção trata da estabilidade, segurança e integridade do sistema, bem como sua capacidade de operar corretamente mesmo em situações inesperadas, considerando frequência e tolerância a falhas, capacidade de recuperação, previsibilidade, exatidão e tempo médio entre falhas.

<div align="center"><strong>Tabela 3: Requisitos de Confiabilidade</strong></div>

| **Requsito** | **Descrição** |
| ------------------- | ---------------- |
| [RNF09](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) | O sistema deve estar disponível 24 horas por dia, 7 dias por semana, com tempo de indisponibilidade máximo de 1% ao mês. Logo, o tempo máximo de inatividade permitido é de 1% ao mês, o que equivale a aproximadamente 7.2 horas de indisponibilidade mensal (considerando um mês de 30 dias). |
| [RNF15](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) | O sistema deve garantir a privacidade dos dados dos estudantes em conformidade com a LGPD. Ele impõe que o sistema seja desenvolvido e mantido em estrita conformidade com a [Lei Geral de Proteção de Dados (LGPD - Lei nº 13.709/2018) do Brasil](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/L13709compilado.htm) |

<div align="center">
    <strong>
        Autoria de 
        <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a>, 
        <a href="https://github.com/arthurhvieira1">Arthur Henrique</a>,
        <a href="https://github.com/felipegf1">Felipe Guimaraes</a>,
        <a href="https://github.com/MrBolt2005">João Felipe</a>,
        <a href="https://github.com/JoaoSapiencia">João Sapiência</a> e
        <a href="https://github.com/VilmarFagundes">Vilmar José</a>
    </strong>
</div>

### 4. Suportabilidade
Esta seção descreve os requisitos relacionados à facilidade de manutenção, evolução e adaptabilidade do sistema, incluindo aspectos como testabilidade, escalabilidade, internacionalização e extensibilidade.

<div align="center"><strong>Tabela 4: Requisitos de Suportabilidade</strong></div>

| **Requsito** | **Descrição** |
| ------------------- | ---------------- |
| [RNF05](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) | Deve empregar recursos tecnológicos alinhados à Teoria da Aprendizagem Significativa (TAS). Isso significa que o sistema deve utilizar ferramentas e tecnologias que facilitem a aprendizagem ativa, conectando novas informações aos conhecimentos prévios do usuário, promovendo compreensão profunda e retenção duradoura. |

<div align="center">
    <strong>
        Autoria de 
        <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a>, 
        <a href="https://github.com/arthurhvieira1">Arthur Henrique</a>,
        <a href="https://github.com/felipegf1">Felipe Guimaraes</a>,
        <a href="https://github.com/MrBolt2005">João Felipe</a>,
        <a href="https://github.com/JoaoSapiencia">João Sapiência</a>,
        <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> e 
        <a href="https://github.com/VilmarFagundes">Vilmar José</a>
    </strong>
</div>

### 5. Performance
Esta seção trata dos requisitos relacionados ao desempenho do sistema, incluindo eficiência sob diferentes condições, tempo de resposta, uso de memória, utilização da CPU, capacidade de processamento e disponibilidade da aplicação.

<div align="center"><strong>Tabela 5: Requisitos de Performance</strong></div>

| **Requsito** | **Descrição** |
| ------------------- | ---------------- |
| [RNF10](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) | O tempo de resposta para carregamento de dashboards e gráficos deve ser inferior a 3 segundos. Ele garante uma experiência de usuário ágil e satisfatória, evitando longas esperas que poderiam levar à frustração e ao abandono da ferramenta. |

<div align="center">
    <strong>
        Autoria de 
        <a href="https://github.com/ArthurGuilher62">Arthur Guilherme</a>, 
        <a href="https://github.com/arthurhvieira1">Arthur Henrique</a>,
        <a href="https://github.com/felipegf1">Felipe Guimaraes</a>,
        <a href="https://github.com/MrBolt2005">João Felipe</a>,
        <a href="https://github.com/JoaoSapiencia">João Sapiência</a> e
        <a href="https://github.com/VilmarFagundes">Vilmar José</a>
    </strong>
</div>

## Referências

## Histórico de versão

| Versão | Data | Descrição | Autor(es) | Revisor |
|--------|------|-----------|-----------|---------|
| 1.0    | 05/10/2025 | Criação do documento da Especificação Suplementar | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [João Sapiência](https://github.com/JoaoSapiencia) |
| 1.1    | 08/10/2025 | Edição do documento de Especificação Suplementar e classificação dos requisitos não funcionais: RNF01 e RNF05 | [Tiago Lemes](https://github.com/TiagoTeixeira-2005) |  [Arthur Guilherme](https://github.com/ArthurGuilher62) | 
| 1.2    | 08/10/2025 | Edição do documento de Especificação Suplementar e classificação dos requisitos não funcionais: RNF09, RNF10 e RNF15 | [Vilmar José](https://github.com/VilmarFagundes) |  |
