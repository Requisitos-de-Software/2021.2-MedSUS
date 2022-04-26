# NFR - Framework

## 1. Introdução

<p>
Os Requisitos não Funcionais são um aspecto muito sensível do planejamento e desenvolvimento de Software. Muitas vezes não são triviais de serem percebidos e levantados, pois costumam ter aspecto subjetivo e abstrato, não sendo percebidos da mesma maneira por todos os envolvidos. Eles também tem relações entre si, conflituosas ou harmônicas. Por todas essas dificuldades, geralmente, os requisitos não funcionais são os piores elicitados, com um baixo nível de detalhamento.
</p>

<p>
O framework NFR (<em>Non Functional Requirements</em>) foi proposto por CHUNG et al (2000), para criar uma abordagem estruturada e com visualização rica e compreensível. Permite uma visualização ampla, auxiliando os desenvolvedores.
</p>

<p>
O Framework costuma utilizar a representação via grafo SIG, um diagrama com símbolos específicos.
</p>

## 2. Metodologia

<p>
A partir dos requisitos já levantados no <a href="../priorization/moscow">Moscow</a>, através das técnicas de <a href="../elicitacion/"> elicitação </a>, de boas práticas e da experiência dos usuários e dos envolvidos no projeto, conseguimos analisar esses requisitos não funcionais e atribuir correlações e interdependências através do grafo.
</p>

### 2.1. Funcionamento do Framework

#### 2.1.1. Legenda

| Símbolo                                                                                                                             | Legenda                                                                                                                                                                 |
| ----------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/softgoal.png">                | Softgoal (Requisito Levantado)                                                                                                                                          |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/operacional.png">             | Operacional (Forma de cumprimento do requisito)                                                                                                                         |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/afirmacao.png">               | Afirmação (Informações sobre as decisões ou recomendações)                                                                                                              |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs\assets\nfr\and.png">                     | Caso os softgoals descendentes forem satisfeitos os ascendentes também serão                                                                                            |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/or.png">                      | Caso algum softgoal descendente for satisfeito, o ascendente também será                                                                                                |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/make.png">                    | Contribuição suficientemente positiva entre um softgoal descendente e um ascendente que é concebida no nível mais alto de satisfação                                    |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/break.png">                   | Contribuição suficientemente negativa entre um softgoal descendente e um ascendente que é concebida no nível mais alto de negação                                       |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/help.png">                    | Contribuição parcialmente positiva entre um softgoal descendente e um ascendente                                                                                        |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/hurt.png">                    | Contribuição parcialmente negativa entre um softgoal descendente e um ascendente                                                                                        |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/unknow.png">                  | Contribuição desconhecida entre um softgoal descendente e um ascendente                                                                                                 |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/equals.png">                  | O softgoal descendente será satisfeito, apenas se o softgoal ascendente for satisfeito ou o softgoal descendente será negado apenas se o softgoal ascendente for negado |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/satisfeito.png">              | O softgoal foi cumprido                                                                                                                                                 |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/negado.png">                  | O softgoal foi negado/rejeitado                                                                                                                                         |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/parcialmente_satisfeito.png"> | O softgoal foi parcialmente satisfeito                                                                                                                                  |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/parcialmente_negado.png">     | O softgoal foi parcialmente negado/rejeitado                                                                                                                            |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/conflitante.png">             | O softgoal é conflitante com outros, em sua resolução                                                                                                                   |
| <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/desconhecido.png">            | O estado do softgoal é desconhecido                                                                                                                                     |

## 3. NFR

<!--
<div class="container">
    <div class="row">
        <div class="col">
            <img>
        </div>
    </div>
</div>
-->

### 3.1. [NFR01] NFR-Geral

<div class="container">
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/NFR01.svg">
            <figcaption>Figura 1: Versão 1.0 - NFR para visão geral do sistema. </figcaption>
            <figcaption>Fonte: Autor</figcaption>
        </div>
    </div>
</div>

### 3.2. [NFR02] NFR-Usabilidade

<div class="container">
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/NFR02.svg">
            <figcaption>Figura 2: Versão 1.0 - NFR para a <a href="../supplementary_specification/">Usabilidade</a> do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/ANFR02.svg">
            <figcaption>Figura 2: Versão 1.0 - ANFR para a <a href="../supplementary_specification/">Usabilidade</a> do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
</div>

### 3.3. [NFR03] NFR-Desempenho

<div class="container">
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/NFR03.svg">
            <figcaption>Figura 3: Versão 1.0 - NFR para a análise de <a href="../supplementary_specification/">Desempenho</a> do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/ANFR03.svg">
            <figcaption>Figura 3: Versão 1.0 - ANFR para a análise de <a href="../supplementary_specification/">Desempenho</a> do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
</div>

### 3.4. [NFR04] NFR-Disponibilidade

<div class="container">
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/NFR04.svg">
            <figcaption>Figura 4: Versão 1.0 - NFR para a análise de <a href="../supplementary_specification/">Disponibilidade</a> do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/ANFR04.svg">
            <figcaption>Figura 4: Versão 1.0 - ANFR para a análise de <a href="../supplementary_specification/">Disponibilidade</a> do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
</div>

### 3.5. [NFR05] NFR-Confiabilidade

<div class="container">
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/NFR05.svg">
            <figcaption>Figura 5: Versão 1.0 - NFR para a análise de Confiabilidade do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/ANFR05.svg">
            <figcaption>Figura 5: Versão 1.0 - ANFR para a análise de Confiabilidade do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
</div>

### 3.6. [NFR06] NFR-Manutenibilidade

<div class="container">
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/NFR06.svg">
            <figcaption>Figura 6: Versão 1.0 - NFR para a análise de Manutenibilidade do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/ANFR06.svg">
            <figcaption>Figura 6: Versão 1.0 - ANFR para a análise de Manutenibilidade do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
</div>

### 3.7. [NFR07] NFR-Segurança

<div class="container">
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/NFR07.svg">
            <figcaption>Figura 7: Versão 1.0 - NFR para a análise de Segurança do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/ANFR07.svg">
            <figcaption>Figura 7: Versão 1.0 - ANFR para a análise de Segurança do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
</div>

### 3.8. [NFR08] NFR-Portabilidade

<div class="container">
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/NFR08.svg">
            <figcaption>Figura 8: Versão 1.0 - NFR para a análise de Portabilidade do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/ANFR08.svg">
            <figcaption>Figura 8: Versão 1.0 - ANFR para a análise de Portabilidade do sistema. </figcaption>
            <figcaption>Fonte: Autor.</figcaption>
        </div>
    </div>
</div>

## Referências bibliográficas

> NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados, SILVA, Antônio Reinaldo, Universidade Federal de Pernambuco , Brazil, 2019. CD-ROM.

## Histórico de versões

| Versão |   Data   |        Alteração        |    Responsável     | Revisão  |
| :----: | :------: | :---------------------: | :----------------: | :------: |
| 0.0.1  | 07/03/22 |         Criação         |       Adrian       | Fernando |
| 0.0.2  | 08/03/22 |     NFR 1, 2, 3, 4      |       Adrian       | Fernando |
| 0.0.3  | 08/03/22 |     NFR 5, 6, 7, 8      |       Adrian       | Fernando |
| 0.0.4  | 09/03/22 | Inserção da Metodologia |       Adrian       | Fernando |
| 0.0.5  | 09/03/22 |  Adição dos links ANFR  | Adrian e Thalisson | Fernando |
| 0.0.6  | 09/03/22 |     Adição legenda      | Adrian e Thalisson | Fernando |
| 0.0.7  | 19/04/22 |    Correção textual     |     João Durso     |  Adrian  |

<style>
    p {
        text-indent: 20px; 
        text-align: justify;
    }
    figcaption {
        text-align: center;
    }
</style>
