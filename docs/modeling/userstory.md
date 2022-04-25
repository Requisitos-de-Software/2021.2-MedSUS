# História de Usuário

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
As histórias de usuário são um importante recurso no desenvolvimento Ágil de software. Assim, a característica dessa filosofia de desenvolvimento, é um importante vetor que norteia a construção desse recurso.

Além disso, as histórias são altamente centradas no usuário, isto é, elas são escritas de modo que o sujeito da ação seja o usuário querendo uma solução de um problema que o software está se propondo a resolver. Assim, é possível gerar um produto com um alta confiabilidade para o usuário final, pois ele sempre foi o pivô no desenvolvimento.

</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
A metodologia utilizada foi partir dos <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/lexicos/">Léxicos</a>, da <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/introspective/"> Introspecção</a> e dos <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/scenarios/"> Cenários</a>. Assim, a equipe tabelou os requisitos levantados em Tema, Épico e Feature. Além disso, na mesma tabela, adicionamos o nível de prioridade discutido no <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/priorization/moscow/"> MoscoW</a>. Por fim, no nosso trabalho seguimos modelo formal para a construção das histórias, ou seja, todas são escritas em uma linguagem não técnica. Dessa forma, qualquer ator envolvido no processo de desenvolvimento do software seja eles usuários finais, designs, PO e/ou equipe técnica, são capazes de participar no processo de criação das histórias.

</p>

## 3. História de Usuário

<table>
    <thead>
        <tr style="background-color: #54CCFF">
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Critérios de aceitação</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Pontuação</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <span id="ustory-01"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US01</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">Eu, como <a href="../../modeling/lexicos#usuario-saude">Usuário da Saúde</a>, gostaria de visualizar informações científicas detalhadas das medicações para tirar eventuais dúvidas.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1"><li> Os caracteres impressos devem ser legíveis</li><li>Acessaria somente as informações caso fossem de fontes confiáveis do Ministério da Saúde</li><li>Eu gostaria que fosse suficiente para me guiar prescrição/averiguação de medicamentos</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-02"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US02</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como <a href="../../modeling/lexicos#usuario-leigo">Usuário Leigo</a>, gostaria de visualizar informações reduzidas em uma linguagem mais acessível para facilitar o meu entendimento.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li> Os caracteres impressos devem ser legíveis</li><li>Desejaria que utilizasse linguagem menos técnica</li><li>Gostaria que indicasse a importância da prescrição médica dos medicamentos para evitar a auto medicação</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3    </td>
        </tr>
        <tr>
            <span id="ustory-03"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US03</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de visualizar em forma de índice os principais tópicos de uma monografia para facilitar a busca por informações.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li> Eu gostaria que o índice ficasse no topo e sempre visível </li><li>O índice deve ter links</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-04"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US04</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de conseguir aumentar e reduzir o tamanho da fonte utilizada para facilitar a minha visualização das informações.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li>Eu gostaria de ver uma demonstração de como o aplicativo ficaria com a nova fonte</li><li>Eu gostaria de voltar a configuração original, ou seja, voltar para o tamanho de fonte padrão</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-05"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US05</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de favoritar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> que eu mais utilizo para facilitar a minha busca por eles depois</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li>Eu gostaria que o aplicativo mostrasse os medicamentos favoritados com alguma marcação visual, algo que o destacasse dos medicamentos não favoritados</li><li>Eu gostaria que os medicamentos tivessem um lugar especial para serem facilmente encontrados</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-06"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US06</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria que meus <a href="../../modeling/lexicos#medicamento">medicamentos</a> favoritos fossem atrelados a uma conta para que eu consiga acessá-los em outros dispositivos.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li>Eu gostaria que essa funcionalidade fosse opcional</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won't</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">13</td>
        </tr>
        <tr>
            <div id="ustory-07"></div>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US07</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por suas palavras-chave para que eu consiga encontrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> mesmo sem saber seu nome.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li>Eu gostaria que quando eu estiver digitando uma pesquisa o aplicativo me mostrasse sugestões que completam o que eu estou digitando</li><li> Eu gostaria que quando pesquisasse um remédio de forma ineficiente, com algum erro de digitação, por exemplo, o aplicativo me mostrasse sugestões de pesquisa e não apenas uma mensagem de erro</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-08"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US08</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por Grupo Anatômico Principal para facilitar a minha busca.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">TODO</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-09"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US09</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por anexo da Rename para facilitar a minha busca.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li>Eu desejaria uma busca intuitiva</li><li>Gostaria de uma barra de pesquisa evidente</li><li>Considero importante filtros simples com ícones indicativos</li><li>Gostaria de filtros avançados para usuários experientes </li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-10"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US10</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por controle especial para facilitar a minha busca.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">TODO</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-11"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US11</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por <a href="../../modeling/lexicos#medicamento">medicamentos</a> que possuam genérico ou não para facilitar a minha busca.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">TODO</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
        <tr>
            <span id="ustory-12"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US12</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de ser notificado sempre que um novo <a href="../../modeling/lexicos#medicamento">medicamento</a> for adicionado ao aplicativo para que eu fique sempre atualizado para com as minhas opções</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li>Eu gostaria de receber essa mensagem assim que eu entrasse no aplicativo</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won't</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <span id="ustory-13"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US13</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de ser notificado sempre que um <a href="../../modeling/lexicos#medicamento">medicamento</a> for removido do aplicativo para que eu fique sempre atualizado para com as minhas opções</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li>Eu gostaria de receber essa mensagem assim que eu entrasse no aplicativo</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won't</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>

        <tr>
            <span id="ustory-14"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US14</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de ser notificado sempre que um <a href="../../modeling/lexicos#medicamento">medicamento</a> sofrer alguma alteração para que eu fique sempre atualizado.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">TODO</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won't</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">8</td>
        </tr>
        <tr>
            <span id="ustory-15"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US15</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de compartilhar monografias de <a href="../../modeling/lexicos#medicamento">medicamentos</a> com outras pessoas para promover o uso racional dos <a href="../../modeling/lexicos#medicamento">medicamentos</a>.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><li>Eu gostaria a opção de envio fosse rápida (5s)</li><li>Eu gostaria de ser informado graficamente (0% a 100%) em que parte do processo de envio estou</li><li>Se o processo de envio não for bem sucedido em até (25s) o programa deve solicitar se desejamos tentar novamente</li><li>Eu gostaria que se o serviço de envio não estiver funcionando corretamente ou estiver passando por alguma instabilidade que o aplicativo me avisasse o problema é interrompesse a operação</li></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">21</td>
        </tr>
        <tr>
            <span id="ustory-16"></span>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="1">US16</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de compartilhar informações de <a href="../../modeling/lexicos#medicamento">medicamentos</a> no formato <a href="../../modeling/lexicos#pdf">PDF</a> para outras pessoas tenham acesso à informação mesmo sem possuir o app instalado em seu dispositivo.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">TODO</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won´t</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">3</td>
        </tr>
    </tbody>
</table>

## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 15): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 46 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668185/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 08 mar. 2022.

## Histórico de versões

| Versão |   Data   |                Alteração                |        Responsável         |        Revisão         |
| :----: | :------: | :-------------------------------------: | :------------------------: | :--------------------: |
| 0.0.1  | 09/03/22 |                 Criação                 |       Gabriel Costa        | João Durso e Thalisson |
| 0.0.2  | 09/03/22 |                Conteúdo                 |    Todos os integrantes    |  Todos os integrantes  |
| 0.0.3  | 19/04/22 |            Correção textual             |         João Durso         |         Adrian         |
| 0.0.4  | 25/04/22 | Adição de alguns critérios de aceitação | Gabriel Costa e João Durso |         Adrian         |
