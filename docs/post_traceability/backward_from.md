# Backward From

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
Como a rastreabilidade Forward, existem dois tipos de rastreabilidade Backward. No entando, esse par de Backward possui pontos diferentes de partida. Este documento trata da rastreabilidade Backward From, a qual fornece informações sobre como um requisito surgiu, por meio da vinculação do requisito ao <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/usecase/">caso de uso</a> do cliente que ele aborda. Isso permite que as equipes melhorem a tomada de decisões, entendendo a origem de um requisito.
</p>

<p style="text-indent: 20px; text-align: justify">
Ademais, os elos de rastreabilidade são concebidos pelo relacionamento entre dois artefatos. São fortes aliados na criação de bibliotecas de componentes, pois deixam evidentes as correlações entre código e demais artefatos, sejam de desenho e/ou de requisitos. Dada a observância dos mesmos problemas ou das mesmas demandas, em um projeto similar, perceberá que é possível fazer uso das mesmas soluções, ou seja, dos mesmos componentes e isso proporciona maior produtividade. 
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
Para a realização desse artefato, primeiramente a baseline e o backlog do produto foi retificado. Em seguida, foi possível organizar os Requisitos Funcionais e Não Funcionais previamente elicitados, formando uma tabela com as suas origens (rastros), levando em consideração todas as suas aparições. Por fim, utilizando a tabela já pronta, elaborou-se os elos de rastreabilidade supracitados.
</p>

## 3. Pós-Rastreabilidade

### 3.1. Matriz

<html> 
    <div class="container"> 
        <div class="row">
            <div class="col-12 embed-responsive embed-responsive-16by9">
                <iframe class="embed-responsive-item" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vRwl0gvkeIMrN8Dq_iL0k9pPXZMk9vBInANPCrSc47qyx7hNbrlA9hq0ynWwCFA6PKZBAn8bXWxmSHr/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
            </div>
        </div>
    </div>
</html>

### 3.2. Elos

### EF01

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [R01](../elicitation/brainstorm.md) satisfaz [ST04](../elicitation/storytelling.md), [UC01](../modeling/usecase.md)
- Representação: [R01](../elicitation/brainstorm.md) representa [IR09](../elicitation/introspective.md), [C001](../modeling/scenarios.md)

### EF02

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [IR10](../elicitation/introspective.md) satisfaz [R02](../elicitation/brainstorm.md)
- Representa: [R02](../elicitation/brainstorm.md) representa [ST08](../elicitation/storytelling.md), [UC01](../modeling/usecase.md)
- Representa: [IR10](../elicitation/introspective.md) representa [UC03](../modeling/usecase.md)

### EF03

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C003](../modeling/scenarios.md) satisfaz [R03](../elicitation/brainstorm.md)
- Representa: [R03](../elicitation/brainstorm.md) representa [ST14](../elicitation/storytelling.md), [UC01](../modeling/usecase.md)
- Representa: [C003](../modeling/scenarios.md) representa [US05](../modeling/userstory.md)

### EF04

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C004](../modeling/scenarios.md) satisfaz [R04](../elicitation/brainstorm.md)
- Representa: [C004](../modeling/scenarios.md) representa [US08](../modeling/userstory.md)

### EF05

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C005](../modeling/scenarios.md) satisfaz [R05](../elicitation/brainstorm.md)
- Representa: [C005](../modeling/scenarios.md) representa [US09](../modeling/userstory.md)

### EF06

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C006](../modeling/scenarios.md) satisfaz [R06](../elicitation/brainstorm.md)
- Representa: [C006](../modeling/scenarios.md) representa [US10](../modeling/userstory.md)

### EF07

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C007](../modeling/scenarios.md) satisfaz [R07](../elicitation/brainstorm.md)
- Representa: [C007](../modeling/scenarios.md) representa [US11](../modeling/userstory.md)

### EF08

**Categoria**: Ambiental
**Elo**:

- Agregação: [R08](../elicitation/brainstorm.md) é composto por [IR1](../elicitation/introspective.md)
- Representa: [R08](../elicitation/brainstorm.md) representa [C008](../modeling/scenarios.md)

### EF09

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [ST17](../elicitation/storytelling.md) é composto por [R09](../elicitation/brainstorm.md)
- Representa: [C009](../modeling/scenarios.md) representa [US12](../modeling/userstory.md)

### EF10

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [ST17](../elicitation/storytelling.md) é composto por [R10](../elicitation/brainstorm.md)
- Representa: [C010](../modeling/scenarios.md) representa [US13](../modeling/userstory.md)

### EF11

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [ST17](../elicitation/storytelling.md) é composto por [R11](../elicitation/brainstorm.md)
- Representa: [C011](../modeling/scenarios.md) representa [US14](../modeling/userstory.md)

### EF12

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C012](../modeling/scenarios.md) satisfaz [R12](../elicitation/brainstorm.md)
- Representa: [C012](../modeling/scenarios.md) representa [US07](../modeling/userstory.md)

### EF13

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [ST10](../elicitation/storytelling.md) satisfaz [R13](../elicitation/brainstorm.md)
- Representa: [R13](../elicitation/brainstorm.md) representa [IR3](../elicitation/introspective.md)
- Representa: [ST10](../elicitation/storytelling.md) representa [US03](../modeling/userstory.md)

### EF14

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C014](../modeling/scenarios.md) satisfaz [R14](../elicitation/brainstorm.md)

### EF15

**Categoria**: Ambiental
**Elo**:

- Satisfação: [C015](../modeling/scenarios.md) satisfaz [R15](../elicitation/brainstorm.md)
- Representa: [C015](../elicitation/storytelling.md) representa [US02](../modeling/userstory.md)

### EF16

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C016](../modeling/scenarios.md) satisfaz [R16](../elicitation/brainstorm.md)

### EF17

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [C017](../modeling/scenarios.md) satisfaz [R17](../elicitation/brainstorm.md)
- Representa: [R17](../elicitation/brainstorm.md) representa [ST02](../elicitation/storytelling.md)

### EF18

**Categoria**: Organizacional
**Elo**:

- Representa: [US04](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) representa [R18](../elicitation/brainstorm.md)
- Satisfação: [ST19](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) satisfaz [R18](../elicitation/brainstorm.md)
- Satisfação: [ES05](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/supplementary_specification/#usabilidade) satisfaz [R18](../elicitation/brainstorm.md)

### EF19

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [US01](../modeling/userstory.md) é composto por [ST01](../elicitation/storytelling.md)

### EF20

**Categoria**: Desenvolvimento
**Elo**:

- Representa: [R17](../elicitation/brainstorm.md) representa [ST02](../elicitation/storytelling.md)

### EF21

**Categoria**: Desenvolvimento
**Elo**:

- Representa: [ES06](../modeling/supplementary_specification.md) representa [ST03](../elicitation/storytelling.md)

### EF22

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [ES03](../modeling/supplementary_specification.md) é composto por [ST06](../elicitation/storytelling.md)

### EF23

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [ES09](../modeling/supplementary_specification.md) satisfaz [ST07](../elicitation/storytelling.md)

### EF24

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [ST09](../elicitation/storytelling.md) é composto por [IR10](../elicitation/introspective.md)

### EF25

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [US01](../modeling/userstory.md) é composto por [ST11](../elicitation/storytelling.md)

### EF26

**Categoria**: Desenvolvimento
**Elo**:

- Representa: [US01](../modeling/userstory.md) representa [ST12](../elicitation/storytelling.md)

### EF27

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [US04](../modeling/userstory.md) é composto por [ST13](../elicitation/storytelling.md)

### EF28

**Categoria**: Desenvolvimento
**Elo**:

- Representa: [ST15](../elicitation/storytelling.md) representa [IR05](../elicitation/introspective.md)

### EF29

**Categoria**: Desenvolvimento
**Elo**:

- Recurso: [ES18](../modeling/supplementary_specification.md) depende de um recurso provido pelo representado em [ST16](../elicitation/storytelling.md)

### EF30

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [ES11](../modeling/supplementary_specification.md) satisfaz [ST18](../elicitation/storytelling.md)

### EF31

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [UC01](../modeling/usecase.md) é composto por [IR02](../elicitation/introspective.md)

### EF32

**Categoria**: Desenvolvimento
**Elo**:

- Representa : [US07](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) representa [IR04](https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/introspective/#requisitos-introsp)

### EF33

**Categoria**: Desenvolvimento
**Elo**:

- Representa: [IR06](../elicitation/introspective.md) representa [ES02](../modeling/supplementary_specification.md)

### EF34

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [ES01](../modeling/supplementary_specification.md) satisfaz [IR07](../elicitation/introspective.md)

### EF35

**Categoria**: Desenvolvimento
**Elo**:

- Agregação : [IR8](https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/introspective/#requisitos-introsp) é composto por [ST02](https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/storytelling#requisitos-storytelling)
- Recurso: [IR8](https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/introspective/#requisitos-introsp) depende de [ES10](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/supplementary_specification/#desempenho)

### EF36

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [ES04](../modeling/supplementary_specification.md) satisfaz [IR11](../elicitation/introspective.md)

### EF37

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [ST03](../elicitation/storytelling.md) é composto por [ES07](../modeling/supplementary_specification.md)

### EF38

**Categoria**: Ambiental
**Elo**:

- Agregação: [ES08](../modeling/supplementary_specification.md) é composto por [ES08](../modeling/supplementary_specification.md)

### EF39

**Categoria**: Ambiental
**Elo**:

- Agregação: [ST02](../elicitation/storytelling.md) é composto por [ES09](../modeling/supplementary_specification.md)

### EF40

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [ES10](../modeling/supplementary_specification.md) satisfaz [ST07](../elicitation/storytelling.md)

### EF41

**Categoria**: Desenvolvimento
**Elo**:

- Agregação : [ST07](https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/storytelling#requisitos-storytelling) é composto por [ES10](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/supplementary_specification/#desempenho)

### EF42

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [IR08](../elicitation/introspective.md) é composto por [ES13](../modeling/supplementary_specification.md)

### EF43

**Categoria**: Desenvolvimento
**Elo**:

- Satisfação: [ES14](../modeling/supplementary_specification.md) satisfaz [IR06](../elicitation/introspective.md)

### EF44

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [IR07](../elicitation/introspective.md) é composto por [ES15](../modeling/supplementary_specification.md)

### EF45

**Categoria**: Desenvolvimento
**Elo**:

- Agregação : [ES17](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/supplementary_specification/#implementacao) é composto por [ES19](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/supplementary_specification/#implementacao)

### EF46

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [IR07](../elicitation/introspective.md) é composto por [ES18](../modeling/supplementary_specification.md)

### EF47

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [ST02](../elicitation/storytelling.md) é composto por [ES19](../modeling/supplementary_specification.md)

### EF48

**Categoria**: Desenvolvimento
**Elo**:

- Agregação: [ST02](../elicitation/storytelling.md) é composto por [ES20](../modeling/supplementary_specification.md)

<!-- |
## 4. Conclusão

<p style="text-indent: 20px; text-align: justify">
Com esse artefato poderá servir como o ponto de referência para entender todos os requisitos. Esse documento serve como a referência inicial dos requisitos para novas pessoas do projeto. Elas saberão as origens das decisões de requisitos tomadas. Com isso, qualquer desenvolvimento ou alteração nos requisitos será facilitado, melhorando a capacidade de pesquisa dos requisitos. 
</p>
 -->
 
## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 44 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668237/mod_resource/content/1/Requisitos%20-%20Aula%20026.pdf. Acesso em: 03 abr. 2022.

> POHL, Klaus; RUPP, Chris. Requirements Engeneering Fundamentals: A Study Guide for the Certified Professional for Requirements Engineering Exam Foundation Level / IREB compliant. 1. ed. [S. l.]: O'Reilly Media, Inc., 2011. 183 p.

## Histórico de versões

| Versão |   Data   |                    Alteração                    |    Responsável     | Revisão  |
| :----: | :------: | :---------------------------------------------: | :----------------: | :------: |
| 0.0.1  | 02/04/22 |                     Criação                     | Adrian, João Durso | Fernando |
| 0.0.2  | 02/04/22 | Adição da Introdução, Metodologia e Referências | Adrian, João Durso | Fernando |
| 0.0.3  | 19/04/22 |                Correção textual                 |     João Durso     | Fernando |
