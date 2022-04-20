# First Things First

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
O First Things First é uma técnica de priorização de requisitos que visa definir as tarefas que devem ser feitas primeiro (mais importantes) e as que devem ser feitas posteriormente (menos importantes).
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
Para a elaboração do First Things First, uma lista com todos os requisitos é feita e os requisitos que estão logicamente ligados são retirados da lista. Em seguida, com valores entre 1 e 9, o benefício que cada recurso oferece ao cliente/negócio é estimado. Depois, a penalidade que o negócio sofreria, caso o recurso não seja incluído é estimada. Assim, a coluna de valor total é preenchida, sendo a soma do benefício e da penalidade, junto aos pesos. Depois disso, o custo de implementação com base na complexidade de implementação é estimado. Em sequência, o grau de risco com base na viabilidade, conhecimento, uso de tecnologias desconhecidas é estimado. A prioridade (p) é calculada por:
</p>

<table style="border:1px solid black;margin-left:auto;margin-right:auto;border-spacing:20px;">
    <tr>
        <td><b>valor(%) / (custo(%) * peso do custo relativo + risco(%) * peso do risco relativo)</b></td>
    </tr>
</table>

<p style="text-indent: 20px; text-align: justify">
Por fim, a lista é ordenada em ordem decrescente prioridade. É importante saber que as funcionalidades no topo da lista têm o melhor equilíbrio entre valor, custo e risco e devem ser priorizadas. 
</p>
<p style="text-indent: 20px; text-align: justify">
Este documento foi baseado nas <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/personas/">personas</a> e nos <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/storytelling/">storytellings</a>. Não houve o envolvimento de um usuário.
</p>

## 3. First Things First

<html> 
    <div class="center-card">
        <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQ2hc31LfJ5FOE2kgoR9VZ_wrh2LwFYKkpgEMaUnmBqzviNdgsc8qxXeL2uqeSoAS_v9tTi4RJdhl4f/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" width="600" height="480" frameborder="0"></iframe>                 
        <figcaption>Tabela 1: Versão 1.0 - Checklist</figcaption>
        <figcaption>Fonte: Autor</figcaption>
    </div>
</html>

## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 7): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 50 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668148/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf. Acesso em: 19 abr. 2022.

## Histórico de versões

| Versão |   Data   |                 Alteração                  | Responsável |  Revisão  |
| :----: | :------: | :----------------------------------------: | :---------: | :-------: |
| 0.0.1  | 19/04/22 |                  Criação                   | João Durso  | Thalisson |
| 0.0.2  | 19/04/22 | Adição de Introdução, metodologia e tabela | João Durso  | Thalisson |
| 0.0.2  | 20/04/22 |             Adição do artefato             | João Durso  | Thalisson |
