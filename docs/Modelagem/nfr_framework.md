## Introdução
Diferente dos requisitos funcionais, que dizem o que o sistema deve fazer, os **requisitos não funcionais (RNF)** explicam como o sistema deve se comportar em certas situações.

Como esses requisitos costumam ser mais complexos e subjetivos, o NFR Framework ajuda a organizá-los de forma clara e estruturada. Ele permite representar, analisar e decidir sobre os RNFs usando **softgoals**, que são objetivos sem critérios de satisfação totalmente definidos.
Neste trabalho, o NFR Framework foi usado para representar os Requisitos Não Funcionais, mostrando suas relações e possíveis conflitos por meio de um gráfico de interdependência de softgoals (SIG).


## Integrantes do Grupo
A Tabela 1 apresenta todos os integrantes da equipe que participaram da etapa de NFR, juntamente com a descrição das atividades que cada um desenvolveu durante o projeto.

<div align="center"><strong>Tabela 1: Integrantes do Grupo Envolvidos</strong></div>

| Nome | Quais etapas participou |
|---------------------------|---------------------------------------|
| [Arthur Guilherme](https://github.com/ArthurGuilher62) |   |
| [Arthur Henrique](https://github.com/arthurhvieira1) |   |
| [Felipe Guimaraes](https://github.com/felipegf1) |   |
| [João Felipe](https://github.com/MrBolt2005) |   |
| [João Sapiência](https://github.com/JoaoSapiencia) |   |
| [Tiago Lemes](https://github.com/TiagoTeixeira-2005) | Criação da documentação e auxílio na criação do [NFR 01 - Usabilidade](https://requisitos-de-software.github.io/2025.2-Grupo03/Modelagem/nfr_framework/#nfr-01-usabilidade) |
| [Vilmar José](https://github.com/VilmarFagundes) |   |

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

## Gráfico de Interdependência de Softgoals (SIG)
O Gráfico de Interdependência de Softgoals **(Softgoal Interdependency Graph — SIG)** é uma ferramenta do NFR Framework usada para mostrar de forma visual os **Requisitos Não Funcionais (NFR)** e como eles se relacionam entre si.

Esse gráfico apresenta, de maneira clara e resumida, as decisões de desenvolvimento, as alternativas consideradas e as justificativas de cada escolha. Sendo possível entender como diferentes softgoals se influenciam e verificar se os objetivos de nível mais alto foram alcançados.

### Tipos de Softgoals
Os softgoals no NFR Framework são divididos em três tipos principais:

- **Softgoals NFR:** representam os próprios Requisitos Não Funcionais, podendo ser organizados de forma hierárquica e relacionados entre si.

- **Softgoals de Operacionalização:** indicam as soluções práticas ou técnicas usadas para atender aos softgoals NFR, como processos, estruturas de dados ou restrições do sistema.

- **Softgoals de Afirmação:** descrevem características do domínio, como prioridades, carga de trabalho e critérios de decisão, ajudando a justificar escolhas e a rastrear as decisões tomadas durante o desenvolvimento.

<div align="center"><strong>Figura 1: Tipos de Softgoals</strong></div>

![Figura 1: Tipos de Softgoals](../imagens/NFR/tipos_Softgoals.png)


<div align="center"><strong>Fonte: CHUNG et al., 2000</strong></div>

## Refinamentos no NFR Framework

Os refinamentos mostram uma relação de **dependência hierárquica**, que acontece de cima para baixo. Nela, um **softgoal principal (pai)** dá origem a outros **softgoals mais específicos (filhos)**, que se relacionam diretamente com ele.  

O objetivo dos refinamentos é **detalhar e especializar os softgoals**, tornando-os mais claros e aplicáveis ao projeto.  
Os principais tipos de refinamento no **NFR Framework** podem ser observados na Figura 2 e são:

- **Decomposição de Softgoal NFR:** Divide um *softgoal* NFR em outros mais específicos, ajudando a esclarecer e priorizar requisitos complexos.  
- **Decomposição de Operacionalização:** Subdivide um *softgoal* de operacionalização em outros *softgoals* de operacionalização mais específicos. Transforma uma solução geral em soluções mais detalhadas e práticas.  
- **Decomposição de Afirmação (Claims):** Refina um *softgoal* de afirmação em outros *softgoals* do mesmo tipo . Serve para apoiar ou questionar justificativas de projeto.  
- **Priorização:** Refina um *softgoal* em outro do mesmo tipo, mas com diferentes níveis de importância.  

<div align="center"><strong>Figura 2: Refinamentos no NFR Framework</strong></div>

![Figura 2: Refinamentos no NFR Framework](../imagens/NFR/refinamentos_NFR.png)

<div align="center"><strong>Fonte: CHUNG et al., 2000</strong></div>


## Contribuições no NFR Framework

No **NFR Framework**, existem diferentes tipos de **contribuições** que mostram como a satisfação (ou não) de um softgoal descendente influencia a satisfação do *softgoal* ascendente.  
A seguir, são apresentados os principais tipos de contribuição definidos por **Chung et al. (2000)**:

- **AND:** todos os *softgoals* descendentes precisam ser satisfeitos para que o *softgoal* ascendente também seja satisfeito.  
- **OR:** basta que um dos *softgoals* descendentes seja satisfeito para que o *softgoal* ascendente também seja satisfeito.  
- **MAKE (++)**: contribuição totalmente positiva — se o descendente for satisfeito, o ascendente também será satisfeito no nível máximo.  
- **BREAK (--)**: contribuição totalmente negativa — se o descendente for satisfeito, o ascendente será negado.  
- **HELP (+)**: contribuição parcialmente positiva — se o descendente for parcialmente satisfeito, o ascendente também será parcialmente satisfeito.  
- **HURT (-)**: contribuição parcialmente negativa — se o descendente for satisfeito, o ascendente será parcialmente negado.  
- **UNKNOWN (?)**: contribuição desconhecida, podendo ser positiva ou negativa, dependendo do contexto.  
- **EQUALS:** o descendente só será satisfeito se o ascendente for satisfeito; da mesma forma, será negado se o ascendente for negado.  
- **SOME:** usada quando se conhece o tipo da contribuição (positiva ou negativa), mas não sua intensidade (parcial ou total).  
- **SOME+:** indica certeza de que a contribuição é positiva, mas incerteza quanto ao grau.  
- **SOME-:** indica certeza de que a contribuição é negativa, mas incerteza quanto ao grau.

## Procedimento de Avaliação no NFR Framework

O **procedimento de avaliação** define o grau em que os requisitos não funcionais são atendidos por um conjunto de decisões do projeto. Ele verifica se cada *softgoal* ou interdependência do SIG foi suficientemente satisfeito.  Para isso, são atribuídos **rótulos** aos *softgoals*, indicando seu nível de satisfação, que podem ser observados na Figura 3.  

- **(✓) Satisfeito**
- **(𝒲+) Fracamente Satisfeito**
- **( X) Negado**
- **(𝒲-) Fracamente Negado**
- **(🗲) Conflitante**
- **(u) Indeterminado**

<div align="center"><strong>Figura 3: Avaliação no NFR Framework</strong></div>

![Figura 3: Avaliação no NFR Framework](../imagens/NFR/avaliacao_NFR.jpeg)

<div align="center"><strong>Fonte: CHUNG et al., 2000</strong></div>

A avaliação começa pelos *softgoals* de nível mais baixo na hierarquia, onde são tomadas decisões sobre aceitar ou rejeitar alternativas de projeto. Essas decisões geram os primeiros rótulos, que são então usados para calcular o impacto nos *softgoals* de níveis superiores.  

Esse processo continua de forma hierárquica até chegar aos *softgoals* de nível mais alto do **SIG**, permitindo entender como as decisões locais afetam os objetivos globais do sistema.  



## Metodologia

## Gráfico de Interdependência de Softgoals (SIG)
A Figura 4 apresenta o Gráfico de Interdependência de Softgoals (SIG) dos Requisitos Não Funcionais do projeto.
Esse gráfico mostra como os softgoals se relacionam entre si e de que forma cada requisito contribui para atingir os objetivos gerais do sistema.

<div align="center"><strong>Figura 4: Gráfico de Interdependência de Softgoals (SIG) - Requisitos Não-Funcionais</strong></div>

![Figura 4: Gráfico de Interdependência de Softgoals (SIG) - Requisitos Não-Funcionais](../imagens/NFR/RNF.jpeg)

<div align="center"><strong>Autoria de <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a></strong></div>

### NFR 01 - Usabilidade

Os requisitos utilizados para o **NFR 01 (Usabilidade)** estão apresentados na página de [Requisitos Elicitados](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/) e são os seguintes:  

- [RNF01](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais): A interface deve se adaptar automaticamente ao perfil de cada usuário (aluno, monitor, professor etc.).  
- [RNF02](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais): O sistema deve ser acessível pela internet, permitindo o uso tanto presencial quanto a distância.  
- [RNF11](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) O sistema deve ser totalmente compatível com dispositivos móveis, garantindo responsividade e adaptação automática a diferentes tamanhos e orientações de tela (smartphones, tablets e notebooks).  
- [RNF12](https://requisitos-de-software.github.io/2025.2-Grupo03/Elicitacao/requisitos_elicitados/#requisitos-nao-funcionais) O sistema deve seguir padrões de acessibilidade para garantir a usabilidade a todos os usuários, incluindo pessoas com deficiência.  

A **Figura 5** apresenta o **Gráfico de Interdependência de Softgoals (SIG)** referente ao NFR 01, destacando as relações de contribuição entre os requisitos de Usabilidade.  


<div align="center"><strong>Figura 5: Gráfico de Interdependência de Softgoals (SIG) - Usabilidade</strong></div>

![Figura 5: Gráfico de Interdependência de Softgoals (SIG) - Usabilidade](../imagens/NFR/Usabilidade.jpeg)

<div align="center">
    <strong>
        Autoria de 
        <a href="https://github.com/felipegf1">Felipe Guimaraes</a>,
        <a href="https://github.com/MrBolt2005">João Felipe</a>,
        <a href="https://github.com/JoaoSapiencia">João Sapiência</a> e
        <a href="https://github.com/TiagoTeixeira-2005">Tiago Lemes</a> 
    </strong>
</div>

### NFR 02 - Confiabilidade

### NFR 03 - Suportabilidade

### NFR 04 - Performance

## Gravação da validação do documento

## Agradecimentos
O Grupo 03 agradece o apoio das ferramentas de Inteligência Artificial Generativa — **ChatGPT, Google Gemini e DeepSeek** — na revisão gramatical e de estilo deste artigo. As tecnologias foram utilizadas para tornar o texto mais claro, objetivo e fácil de ler. Todo o conteúdo, assim como a precisão técnica e as ideias apresentadas, permanecem de responsabilidade dos autores.

## Referências

## Históricos de versão

| Versão | Data       | Descrição                                   | Autor(es)                                                   | Revisor       |
|--------|------------|---------------------------------------------|------------------------------------------------------------|---------------|
| 1.0    | 16/10/2025 | Criação do documento de NFR           | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)       | [Vilmar José](https://github.com/VilmarFagundes) |
| 1.1    | 18/10/2025 | Auxílio na criação do NFR 01 - Usabilidade           | [Tiago Lemes](https://github.com/TiagoTeixeira-2005)       | [Vilmar José](https://github.com/VilmarFagundes) |


