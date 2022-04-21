# MoScoW

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
    MoScoW é uma das técnicas de Priorização de Requisitos mais simples e mais utilizadas atualmente. O nome da técnica consiste nas letras maiúsculas das quais usamos na priorização: M(Must): Requisitos priotirários/críticos, S(Should): requisitos importantes, mas não necessários para o funcionamento do produto, (C)Could: são os requisitos dejáveis; e W(won't): são os menos críticos, "gostaria, mas não é prioridade agora".
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
    Para fazermos a priorização dos requisitos, nós, integrantes do grupo, nos reunimos pelo Discord e discutimos todos os requisitos elicitados pelas técnicas utilizadas até aqui: Brainstorm, Storytelling e Introspective.
    Então, ao analisar cada requisito, chegamos a um acordo sobre a sua classe de priorização, isto é, em qual classificação o requisito melhor se enquadraria.
</p>
<p style="text-indent: 20px; text-align: justify">
Este documento foi baseado nas <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/personas/">personas</a> e nos <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/storytelling/">storytellings</a>. Não houve o envolvimento de um usuário.
</p>

## 3. MoScoW

### 3.1 Must

| Identificador | Requisito                                                                                                                              |
| :-----------: | :------------------------------------------------------------------------------------------------------------------------------------- |
|     ST01      | O app precisa mostrar os efeitos colaterais das medicações.                                                                            |
|     ST03      | O app deve usar uma base de dados confiáveis (SUS, Rename, Ministério da Saúde, Anvisa).                                               |
|     ST04      | O app deve disponibilizar busca.                                                                                                       |
|     ST08      | O app deve gerar arquivos para compartilhar com qualquer outra pessoa.                                                                 |
|     ST09      | O app deve utilizar as APIs disponíveis para compartilhamento através dos aplicativos de comunicação mais comuns (E-mail e mensagens). |
|     ST11      | A bula disponibilizada deve conter as indicações e contra-indicações do remédio.                                                       |
|     ST12      | A bula disponibilizada deve conter o modo de uso da medicação.                                                                         |
|     ST16      | A aplicação deve utilizar ícones comuns ao domínio mobile (mais utilizado)                                                             |
|      IR1      | Acessar uma forma resumida da bula: efeitos colaterais, as indicações e contra indicações, com menos termos técnicos.                  |
|      IR7      | Boa usabilidade.                                                                                                                       |
|      IR8      | Boa performance.                                                                                                                       |
|      IR9      | Pesquisar medicamentos pelo nome.                                                                                                      |
|     IR10      | Compartilhar informações por PDF.                                                                                                      |
|     IR11      | Boa apresentação da informação pesquisada.                                                                                             |

### 3.2 Should

| Identificador | Requisito                                                                    |
| :-----------: | :--------------------------------------------------------------------------- |
|     ST02      | O app deve ser otimizado para a experiência mobile.                          |
|     ST13      | A aplicação deve fornecer opções de acessibilidade para quem tem visão ruim. |
|     ST14      | Deve ser possível favoritar as medicações.                                   |
|      IR3      | Acessar partes específicas da bula através de um índice.                     |
|      IR6      | Designer familiar e bonito.                                                  |

### 3.3 Could

| Identificador | Requisito                                                                                                                               |
| :-----------: | :-------------------------------------------------------------------------------------------------------------------------------------- |
|     ST05      | A ferramenta de busca é a principal e deve ser diponibilizada ao abrir o app.                                                           |
|     ST06      | O app deve fornecer a lista ordenada de remédios.                                                                                       |
|     ST10      | O documento gerado pela aplicação deve ter um índice com links para as seções da bula.                                                  |
|     ST18      | O app deve possui um link de compartilhamento do próprio aplicativo, para que os usuários possam recomendá-lo e outros possam baixá-lo. |
|      IR2      | Filtrar medicamentos por doenças.                                                                                                       |
|      IR4      | Buscar por palavras-chave e não somente pelos nomes das medicações.                                                                     |

### 3.4 Won't

| Identificador | Requisito                                                                                                                |
| :-----------: | :----------------------------------------------------------------------------------------------------------------------- |
|     ST15      | O app deve conseguir marcar (favoritar) medicações vinculadas ao usuário e não só ao dispositivo.                        |
|     ST17      | O app deve notificar os usuários acerca das atualizações da monografia dos medicamentos (inclusão, remoção e alteração). |
|     ST19      | A aplicação deve disponibilizar o aumento (e redução) do tamanho da fonte das monografias.                               |
|      IR5      | Favoritar medicações atrelado a alguma conta, para acessá-las em outros dispositivos.                                    |
|      IR12      | Visão de cidadão em medicamentos favoritados.                                                                            |

## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668148/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 20 fev. 2022.

## Histórico de versões

| Versão |   Data   |           Alteraçã   o         |          Responsável          |       Revisão        |
| :----: | :------: | :----------------------------: | :---------------------------: | :------------------: |
| 0.0.1  | 20/02/22 |           Criação              | Gabriel Oliveira e João Durso | Thalisson e Fernando |
| 0.0.2  | 20/02/22 |          Priorização           |     Todos os integrantes      | Thalisson e Fernando |
| 0.0.3  | 20/02/22 |     Introdução e Metodologia   |           Fernando            | Thalisson e Fernando |
| 0.0.4  | 20/04/22 | Atualização com novo requisito |           Fernando            | Thalisson e Fernando |
