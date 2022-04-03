# Especificação Suplementar

## 1. Introdução

### 1.1 Propósito

Capturar os requisitos do sistema que não são facilmente definidos pela modelagem de casos de uso. De modo que a Especificação Suplementar em conjunto com a [modelagem de Casos de Uso](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/usecase) definem todos os requisitos do sistema.

### 1.2 Escopo

Essa Especificação Suplementar se aplica à versão 2.1.5 do aplicativo MedSUS disponibilizado pelo ministério da saúde.
Essa especificação cobre todos os requisitos não funcionais do sistema, como os requisitos de usabilidade, confiabilidade, desempenho e suportabilidade.

## 2. Metodologia

Os requisitos neste documento foram definidos com base no sistema FURPS+. 

Esse sistema visa classificar os requisitos de acordo com os atributos de qualidade de software. O acrônimo representa as possíveis categorias para os requisitos, são elas:

- Funcionalidade: Capacidade (generalidade do conjunto de recursos), reutilização (compatibilidade, interoperabilidade, portabilidade), segurança e explorabilidade;
- Usabilidade: Resposividade, documentação, consistência, estética, fatores humanos em geral; 
- Confiabilidade: Disponibilidade(Frequência de Falhas(Robustez/Durabilidade/Responsividade), Extensão e Duração da Falha(Recuperabilidade/Sobrevivênvia)), Previsibilidade/Establidade;
- Desempenho: Velocidade, Eficiência, Consumo de Recurso, Rendimento, Capacidade, Escalabilidadae;
- Suportabilidade: Manutenabulidade, Testabilidade, Flexibilidade, Instabilidade, Localizabilidade.
- Design: Restringe o design do sistema com, padrões de design, uso de ferramentas de desenvolvimento, etc.
- implementação: Restringe o código ou a construção do sistema como, limites de recurso, sistemas operativos, etc.
- Interface: Restringe as funcionalidades referentes às interface dos diferentes componentes.
- Físico: Restringe o hardware na qual o sistema será suportado.

## 3. Especificação Suplementar

### 3.1 Funcionalidades

- Os requisitos funcionais estão definidos através dos Casos de Uso. É possível encontrá-los [aqui](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/usecase)

### 3.2 Usabilidade

- O aplicativo não exigirá treinamento prévio por parte do usuário. <sup>[IR7](../elicitation/introspective.md#4resultado)</sup>
- Design simples e familiar que facilite a memorização <sup>[R12](../elicitation/brainstorm.md#requisitos-levantados) [IR6](../elicitation/introspective.md#4resultado)</sup>
- As informações devem ser apresentadas de modo que facilite a busca e o acesso a informação. <sup>[ST06](../elicitation/storytelling.md#41-requisitos)</sup>
- As informações apresentadas no aplicativo devem ser de fácil entendimento. <sup>[IR11](../elicitation/introspective.md#4resultado)</sup>
- O aplicativo deve fornecer opções de tamanhos diferentes para as fontes utilizadas. <sup>[ST19 ST13](../elicitation/storytelling.md#41-requisitos)</sup>

### 3.3 Confiabilidade

- As informações presentes no aplicativo devem ser provenientes de fontes de dados confiáveis. <sup>[ST03](../elicitation/storytelling.md#41-requisitos)</sup>
- As informações a respeito dos medicamentos devem estar sempre atualizadas. <sup>[ST03](../elicitation/storytelling.md#41-requisitos)</sup>
- As monografias salvas como favoritas devem estar disponíveis mesmo após queda de internet.

### 3.4 Desempenho

- O aplicativo não deve consumir muitos recursos. <sup>[ST02](../elicitation/storytelling.md#41-requisitos)</sup>
- As buscas não devem demorar mais de 1 segundo para serem concluídas. <sup>[IR8](../elicitation/introspective.md#4resultado)</sup>

### 3.5 Suportabilidade

- Deve ser disponibilizado nas lojas oficiais dos dispositivos móveis. <sup>[R14](../elicitation/brainstorm.md#requisitos-levantados)</sup>
- Tempo médio máximo de reparação dos servidores deve ser de 4 horas.
- O aplicativo deve suportar 300 mil usuários simultâneos.

### 3.6 Design

- O aplicativo deve seguir uma palheta de cores fixa.
- Os ícones utilizados no aplicativo devem ser coerentes com a funcionalidade que eles representam.

### 3.7 Implementação

- O aplicativo deve ser compatível com o sistema Android e IOS. <sup>[R14](../elicitation/brainstorm.md#requisitos-levantados)</sup>
- O aplicativo não deve usar mais de 50 MegaBytes de memória interna.

### 3.8 Interface

- A interface dos diferentes componentes devem sequir o mesmo padrão para não confundir o usuário.

### 3.9 Físico

- O dispositivel Android deve estar em uma versão 4.4 ou superior.
- O dispositivel IOS deve estar em uma versão 10.0 ou superior.

## Referências bibliográficas

> http://home.iscte-iul.pt/~hro/RUPSmallProjects/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html
> https://csis.pace.edu/~marchese/SE616_New/Samples/Example%20%20Supplementary%20Specification.htm
> https://qualidadebr.wordpress.com/2008/07/10/furps/

## Histórico de versões

Versão|Data|Alteração|Responsável|Revisão|
:---:|:---:|:---:|:---:|:---:|
0.0.1|03/03/2022|Criação|Thalisson e Fernando| Adrian |
0.0.2|03/03/2022|Introdução (Propósito e Escopo)|Thalisson e Fernando| Adrian |
0.0.3|04/03/2022|Metodologia|Thalisson|Adrian|
0.0.4|04/03/2022|Especificação Suplementar|Thalisson|Adrian|
0.0.5|05/03/2022|Adição de requisitos|Thalisson|Adrian|
0.0.6|03/04/2022|Adição dos requisitos adicionais do FURPS+|Thalisson|Adrian|
