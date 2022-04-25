# Product Backlog

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
O Product Backlog, um dos pilares do desenvolvimento Scrum, é uma lista contendo todas as funcionalidades desejadas para um produto. O conteúdo desta lista é definido pelo Product Owner, o responsável por gerenciar e definir esses itens. Ademais, o Product Backlog não precisa estar completo no início de um projeto, isto é, pode-se começar com tudo aquilo que é mais óbvio em um primeiro momento e com o tempo alterá-lo, a medida que se aprende mais sobre o produto e seus usuários.
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
A metodologia utilizada foi partir dos <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/lexicos/">Léxicos</a>, da <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/introspective/"> Introspecção</a> e dos <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/scenarios/"> Cenários</a>. Assim, a equipe tabelou os requisitos levantados em Tema, Épico e Feature. Além disso, na mesma tabela, adicionamos o nível de prioridade discutido no <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/priorization/moscow/"> MoscoW</a>.
</p>

## 3. Product Backlog

<table>
    <thead>
        <tr style="background-color: #54CCFF">
            <th style="border-style:solid;border-width:1px;text-align:center">Tema</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Épico</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Feature</th>
            <th style="border-style:solid;border-width:1px;text-align:center">ID</th>
            <th style="border-style:solid;border-width:1px;text-align:center">História de Usuário</th>
            <th style="border-style:solid;border-width:1px;text-align:center">Prioridade</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="100%">MedSus</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="4">Visualização</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Alterar perfil</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2"><a href="../../elicitation/brainstorm#brain-08">R08</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como <a href="../../modeling/lexicos#usuario-saude">Usuário da Saúde</a>, gostaria de visualizar informações científicas detalhadas das medicações para tirar eventuais dúvidas.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como <a href="../../modeling/lexicos#usuario-leigo">Usuário Leigo</a>, gostaria de visualizar informações reduzidas em uma linguagem mais acessível para facilitar o meu entendimento.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Alterar tamanho da fonte</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/storytelling#story-19">ST19</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de visualizar em forma de índice os principais tópicos de uma monografia para facilitar a busca por informações.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Apresentar índice</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/introspective#intro-03">IR03</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de conseguir aumentar e reduzir o tamanho da fonte utilizada para facilitar a minha visualização das informações.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="7">Filtro</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Favoritar</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/brainstorm#brain-03">R03</a> <a href="../../elicitation/storytelling#story-14">ST14</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de favoritar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> que eu mais utilizo para facilitar a minha busca por eles depois</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Should</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/introspective#intro-05">IR05</a> <a href="../../elicitation/storytelling#story-15">ST15</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria que meus <a href="../../modeling/lexicos#medicamento">medicamentos</a> favoritos fossem atrelados a uma conta para que eu consiga acessá-los em outros dispositivos.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won't</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Filtrar por Palavras-chave</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/brainstorm#brain-12">R12</a> <a href="../../elicitation/introspective#intro-04">IR04</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por suas palavras-chave para que eu consiga encontrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> mesmo sem saber seu nome.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="4">Filtrar por Atributos do <a href="../../modeling/lexicos#medicamento">medicamento</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/brainstorm#brain-04">R04</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por Grupo Anatômico Principal para facilitar a minha busca.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/brainstorm#brain-05">R05</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por anexo da Rename para facilitar a minha busca.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/brainstorm#brain-06">R06</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por controle especial para facilitar a minha busca.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/brainstorm#brain-07">R07</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de filtrar os <a href="../../modeling/lexicos#medicamento">medicamentos</a> por <a href="../../modeling/lexicos#medicamento">medicamentos</a> que possuam genérico ou não para facilitar a minha busca.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Could</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="3">Notificação</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="3">Notificar usuários</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="3"><a href="../../elicitation/storytelling#story-17">ST17</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de ser notificado sempre que um novo <a href="../../modeling/lexicos#medicamento">medicamento</a> for adicionado ao aplicativo para que eu fique sempre atualizado para com as minhas opções</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won't</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de ser notificado sempre que um <a href="../../modeling/lexicos#medicamento">medicamento</a> for removido do aplicativo para que eu fique sempre atualizado para com as minhas opções</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won't</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de ser notificado sempre que um <a href="../../modeling/lexicos#medicamento">medicamento</a> sofrer alguma alteração para que eu fique sempre atualizado.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Won't</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Compartilhamento</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle" rowspan="2">Compartilhar monografias</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/storytelling#story-08">ST08</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de compartilhar monografias de <a href="../../modeling/lexicos#medicamento">medicamentos</a> com outras pessoas para promover o uso racional dos <a href="../../modeling/lexicos#medicamento">medicamentos</a>.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
        <tr>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle"><a href="../../elicitation/introspective#intro-10">IR10</a></td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Eu, como usuário, gostaria de compartilhar informações de <a href="../../modeling/lexicos#medicamento">medicamentos</a> no formato <a href="../../modeling/lexicos#pdf">pdf</a> para outras pessoas tenham acesso a informação mesmo sem possuir o app instalado em seu dispositivo.</td>
            <td style="border-style:solid;border-width:1px;text-align:center;vertical-align:middle">Must</td>
        </tr>
    </tbody>
</table>

## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 15): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 46 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668185/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf. Acesso em: 08 mar. 2022.

## Histórico de versões

| Versão  |   Data   |                       Alteração                       | Responsável |  Revisão   |
| :-----: | :------: | :---------------------------------------------------: | :---------: | :--------: |
|  0.0.1  | 08/03/22 |                        Criação                        |  Thalisson  | João Durso |
|  0.0.2  | 09/03/22 |                   Adição do Backlog                   |  Thalisson  | João Durso |
|  0.0.3  | 09/03/22 |                    Adição de links                    |  Thalisson  | João Durso |
|  0.0.4  | 09/03/22 | Revisão do texto e adição de introdução e metodologia | João Durso  | Thalisson  |
| 0.0.4.1 | 09/03/22 |                   Revisão do texto                    | João Durso  | Thalisson  |
|  0.0.5  | 19/04/22 |                   Correção textual                    | João Durso  | Thalisson  |
|  0.0.6  | 24/04/22 |            Ajuste nos links dos requisitos            |  Thalisson  | João Durso |
