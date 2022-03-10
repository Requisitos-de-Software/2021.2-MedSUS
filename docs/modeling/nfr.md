# NFR - Framework

## 1. Introdução

<p>
Os Requisitos não Funcionais são um aspecto muito sensível do planejamento e desenvolvimento de Software. Muitos vezes não são triviais de serem percebidos e levantados, pois costumam ter aspecto subjetivo e abstrato, não sendo percebidos da mesma maneira por todos os envolvidos. Eles também tem relações entre si  , conflituosas ou harmônicas. Por todas essas dificuldades, geralmente, os requisitos não funcionais são os piores elicitados, com um baixo nível de detalhamento.
</p>

<p>
O framework NFR (<em>Non Functional Requirements</em>) foi proposto por CHUNG et al (2000), para criar uma abordagem estruturada e com visualização rica e compreensível. Permite uma visualização ampla, auxiliando os desenvolvedores.
</p>

<p>
O Framework costuma utilizar a representação via grafo SIG, um diagrama com símbolos específicos.
</p>

## 2. Metodologia

<p>
A partir dos <a href="../priorization/moscow">requisitos já levantados</a> através das técnicas de <a href="../elicitacion/"> elicitação </a> e de boas práticas e da experiência dos usuários e dos envolvidos no projeto, conseguimos analisar esses requisitos não funcionais e atribuir correlações e  interdependências através do grafo.
</p>

### 2.1. Funcionamento do Framework

#### 2.1.1. Legenda

| Símbolo  | Legenda  |
|   ---    |    ---   |
|||
<!-- |<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/and.svg">|Caso os softgoals descendentes forem satisfeitos os ascendentes também serão
|<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/or.svg">|Caso algum softgoal descendente for satisfeito, o ascendente também será|
|<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/make.svg">|Contribuição suficientemente positiva entre um softgoal descendente e um 
ascendente que é concebida no nível mais alto de satisfação|
|<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/break.svg">|Contribuição suficientemente negativa entre um softgoal descendente e um 
ascendente que é concebida no nível mais alto de negação|
|<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/help.svg">|Contribuição parcialmente positiva entre um softgoal descendente e um 
ascendente|
|<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/hurt.svg">|Contribuição parcialmente negativa entre um softgoal descendente e um 
ascendente|
|<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/unknow.svg">|Contribuição desconhecida entre um softgoal descendente e um 
ascendente|
|<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/equals.svg">|O softgoal descendente será satisfeito, apenas se o softgoal ascendente for 
satisfeito ou o softgoal descendente será negado apenas se o softgoal ascendente for 
negado|
|<a href="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/some.svg">|Utilizado quando o sinal da contribuição é conhecido, mas a extensão não é. Em caso 
de dúvidas de se utilizar o HELP ou MAKE por exemplo deve-se utilizar SOME+. O mesmo 
vale para o HURT ou BREAK, porém nesse caso se usa o SOME-| -->


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
            <figcaption>Figura 1: Versão 1.0 - NFR para visão geral do sistema </figcaption>
            <figcaption>Fonte: Autor</figcaption>
        </div>
    </div>
    <div class="row">
        <div class="col">
            <img src="https://raw.githubusercontent.com/Requisitos-de-Software/2021.2-MedSUS/main/docs/assets/nfr/ANFR01.svg">
            <figcaption>Figura 1: Versão 1.0 - ANFR para visão geral do sistema </figcaption>
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

>  NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados, SILVA, Antônio Reinaldo, Universidade Federal de Pernambuco , Brazil, 2019. CD-ROM.

## Histórico de versões

Versão|Data|Alteração|Responsável|Revisão|
:-:|:-:|:-:|:-:|:-:|
0.0.1|07/03/22|Criação|Adrian|Fernando|
0.0.2|08/03/22|NFR 1, 2, 3, 4|Adrian|Fernando|
0.0.3|08/03/22|NFR 5, 6, 7, 8|Adrian|Fernando|
0.0.4|09/03/22|Inserção da Metodologia|Adrian|Fernando|
0.0.5|09/03/22|Adição dos links ANFR|Adrian e Thalisson|Fernando|
0.0.5|09/03/22|Adição legenda|Adrian e Thalisson|Fernando|


<style>
    p {
        text-indent: 20px; 
        text-align: justify;
    }
    figcaption {
        text-align: center;
    }
</style>