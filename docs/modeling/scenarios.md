# Cenários

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
Cenário é uma cena que ilustra a interação entre ambientes e um sistema proposto. Ademais, é uma ferramenta extremamente utilizada durante a análise de requerimentos para descrever o uso de um sistema. Os cenários capturam o sistema, visto de fora, por exemplo, por um usuário, usando exemplo específicos. Para isso, faz uso de algumas abstrações, como título, objetivos, contexto, ator(es), recursos, exceções, episódios e restrições.
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
A partir do <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/brainstorm/">Brainstorm</a> realizado em uma reunião com todos os membros do grupo, conseguimos levantar alguns requisitos básicos. A partir desses requisitos, buscamos escrever e detalhar os cenários do sistema. Esta técnica descreve os requisitos numa linguagem mais fácil de entender e validar. Além disso, facilitam a criação dos casos de uso posteriormente.
</p>

### template

**-> Título <-**

**Objetivo**

estabelece a finalidade de um cenário. O cenário deve
descrever de que modo este objetivo deve ser alcançado.

**Contexto**

descreve o estado inicial de um cenário, suas pré-condições, o local (físico) e tempo. Na sua definição podem ser
especificadas restrições sobre estes elementos

**Atores**

Pessoa ou estrutura organizacional que tem um papel no cenário.

**Recursos**

identifica os objetos passivos com os quais lidam os
atores. Na sua definição podem ser especificadas restrições sobre os
objetos a serem lidados pelo cenário.

**Episódios**

Cada episódio representa uma ação realizada por um
ator onde participam outros atores utilizando recursos disponíveis. Um
episódio também pode se referir a outro cenário. Episódios podem
conter restrições e exceções.

**Restrições**

Uma restrição é qualquer imposição que restrinja um episódio de um cenário

**Exceções**

Uma exceção é o tratamento para uma situação excepcional ou de erro

## 3. Cenários

### Cenário 001

**-> Pesquisar medicamentos por nome <-**

**Objetivo**

Buscar por medicamento específico para o encontrar mais facilmente.

**Contexto**

Local: Tela inicial.
Tempo: A qualquer momento.
Pré-condição: Não se aplica.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra na tela inicial.
Usuário clica no ícone de pesquisa, no canto superior direito.
Usuário pesquisa o medicamento desejado.

**Restrições**

_smartphone_ incapaz de executar o aplicativo corretamente.
Falha na conexão com a internet  
Usuário não sabe o nome do medicamento.

**Exceções**

O usuário faz uma pesquisa ineficiente ( Ex. erra o nome do medicamento)

### Cenário 002

**-> Compartilhar medicamentos <-**

**Objetivo**

Compartilhar medicamentos para outras pessoas.

**Contexto**

Local: Na tela de qualquer medicamento.
Tempo: A qualquer momento.
Pré-condição: Não se aplica.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra na tela inicial.
Usuário procura pelo medicamento desejado.
Usuário clica no ícone do meio, na aba inferior.
Usuário escolhe onde irá compartilhar as informações.

**Restrições**

Só é possível compartilhar em um outro aplicativo por vez.

**Exceções**

Destinatário não possui nenhum aplicativo para receber o compartilhamento.

### Cenário 003

**-> Favoritar medicamentos <-**

**Objetivo**

Favoritar medicamentos para guardar os medicamentos que possuem preferência.

**Contexto**

Local: Na tela inicial ou na tela de qualquer medicamento.
Tempo: A qualquer momento.
Pré-condição: Não se aplica.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra na tela inicial.
Usuário procura pelo medicamento desejado.
Usuário clica no ícone de favoritar - atrás do nome do medicamento.

**Restrições**

Medicamento não existe no sistema.

**Exceções**

Nenhuma exceção foi encontrada.

### Cenário 004

**-> Filtrar medicamento por GAP <-**

**Objetivo**

Filtrar medicamentos por Grupo Anatômico Principal, para diminuir as opções e facilitar a busca.

**Contexto**

Local: Na tela inicial.
Tempo: A qualquer momento.
Pré-condição: Saber a que categoria do GPA o remédio desejado pertence.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra na tela inicial.
Usuário clica no ícone de filtragem, acima do canto inferior direito.
Usuário clica na(s) categoria(s) do GPA que o medicamento desejado pode se encaixar.

**Restrições**

Usuário escolhe a categoria errada do GPA.

**Exceções**

Usuário não conhece o Grupo Anatômico Principal.

### Cenário 005

**-> Filtrar medicamento por anexo da RENAME <-**

**Objetivo**

Filtrar medicamentos por anexo da RENAME, para diminuir as opções e facilitar a busca.

**Contexto**

Local: Na tela inicial.
Tempo: A qualquer momento.
Pré-condição: Saber a que categoria do anexo da RENAME o remédio desejado pertence.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra na tela inicial.
Usuário clica no ícone de filtragem, acima do canto inferior direito.
Usuário clica na(s) categoria(s) do anexo da RENAME que o medicamento desejado se encaixa.

**Restrições**

Usuário escolhe a categoria errada do anexo da RENAME.

**Exceções**

Usuário não conhece o anexo da RENAME.

### Cenário 006

**-> Filtrar medicamento por controle especial <-**

**Objetivo**

Filtrar medicamentos por controle especial, para diminuir as opções e facilitar a busca.

**Contexto**

Local: Na tela inicial.
Tempo: A qualquer momento.
Pré-condição: Saber a que categoria do controle especial o remédio desejado pertence.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra na tela inicial.
Usuário clica no ícone de filtragem, acima do canto inferior direito.
Usuário clica na(s) categoria(s) do controle especial que o medicamento desejado se encaixa.

**Restrições**

Usuário escolhe a categoria errada do controle especial.

**Exceções**

Usuário desconhece o controle especial.

### Cenário 007

**-> Filtrar medicamento por existência de genérico <-**

**Objetivo**

Filtrar medicamentos por existência (ou não) de genérico, para diminuir as opções e facilitar a busca.

**Contexto**

Local: Na tela inicial.
Tempo: A qualquer momento.
Pré-condição: Saber se o remédio possui versão genérica ou não.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra na tela inicial.
Usuário clica no ícone de filtragem, acima do canto inferior direito.
Usuário clica na opção 'Sim', se possui genérico e 'Não', caso não possua.

**Restrições**

Usuário possui dúvida quanto à existência da versão genérica.

**Exceções**

Rede do usuário cai.

### Cenário 008

**-> Alterar informações baseado no perfil do usuário <-**

**Objetivo**

Alterar informações baseado no perfil do usuário (profissional da saúde ou usuário comum), para atualizar as informações da monografia.

**Contexto**

Local: Na tela de qualquer medicamento.
Tempo: A qualquer momento.
Pré-condição: Ter conhecimento de alguma alteração a ser feita.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra no aplicativo.
Usuário clica no medicamento desejado.
Usuário seleciona o seu perfil (profissional da saúde ou usuário comum), na aba superior do aplicativo.

**Restrições**

Usuário não perceber a aba de seleção de perfil.

**Exceções**

Aplicativo fora do ar.

### Cenário 009

**-> Notificar a adição de um medicamento <-**

**Objetivo**

Notificar ao usuário a adição de um medicamento no aplicativo, a fim de deixá-lo sempre atualizado.

**Contexto**

Local: Em qualquer tela do celular.
Tempo: A qualquer momento.
Pré-condição: Possuir as notificações do aplicativo ligadas e estar conectado à internet.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário recebe a notificação na tela do celular.
Usuário entra no aplicativo.
Usuário clica no ícone do meio, da aba inferior do aplicativo.
Usuário clica no meio da aba superior do aplicativo (Inclusão).

**Restrições**

O usuário desligou as notificações.

**Exceções**

Nenhum medicamento foi adicionado.

### Cenário 010

**-> Notificar a remoção de um medicamento <-**

**Objetivo**

Notificar ao usuário a remoção de um medicamento no aplicativo, a fim de deixá-lo sempre atualizado.

**Contexto**

Local: Em qualquer tela do celular.
Tempo: A qualquer momento.
Pré-condição: Possuir as notificações do aplicativo ligadas e estar conectado à internet.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário recebe a notificação na tela do celular.
Usuário entra no aplicativo.
Usuário clica no ícone do meio, da aba inferior do aplicativo.
Usuário clica no meio da aba superior do aplicativo (Exclusão).

**Restrições**

O usuário desligou as notificações.

**Exceções**

Nenhum medicamento foi removido.

### Cenário 011

**-> Notificar a alteração de um medicamento <-**

**Objetivo**

Notificar ao usuário a alteração de um medicamento no aplicativo, a fim de deixá-lo sempre atualizado.

**Contexto**

Local: Em qualquer tela do celular.
Tempo: A qualquer momento.
Pré-condição: Possuir as notificações do aplicativo ligadas e estar conectado à internet.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário recebe a notificação na tela do celular.
Usuário entra no aplicativo.
Usuário clica no ícone do meio, da aba inferior do aplicativo.
Usuário clica no meio da aba superior do aplicativo (Alteração).

**Restrições**

O usuário desligou as notificações.

**Exceções**

Nenhum medicamento foi alterado.

### Cenário 012

**-> Pesquisar palavras-chave no texto das monografias <-**

**Objetivo**

Buscar palavras-chave no texto, para facilitar a leitura.

**Contexto**

Local: Na tela de qualquer medicamento.
Tempo: A qualquer momento.
Pré-condição: Não achar o local de leitura desejado.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra no aplicativo.
Usuário clica no medicamento desejado.
Usuário clica na aba de texto, na parte superior da tela.
Usuário digita a palavra-chave que deseja procurar no texto.

**Restrições**

O usuário digitou errado a palavra-chave.

**Exceções**

A palavra-chave não existe no texto.

### Cenário 013

**-> Visualizar o índice das informações de um medicamento <-**

**Objetivo**

Buscar o texto por meio do uso de um sumário, no qual os títulos mais importantes estão expostos por índice.

**Contexto**

Local: Na tela de qualquer medicamento.
Tempo: A qualquer momento.
Pré-condição: Não se aplica.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra no aplicativo.
Usuário clica no medicamento desejado.
Usuário clica no ícone de lista, no canto inferior esquerdo.

**Restrições**

O usuário clicou no título errado.

**Exceções**

O título que o usuário procura não existe no texto.

### Cenário 014

**-> Saber os medicamentos de prioridade para o SUS/RENAME <-**

**Objetivo**

Todos os medicamentos listados no aplicativo MedSUS são aprovados e listados pela RENAME, por isso o usuário possui confiabiliadade quanto ao uso das substâncias.

**Contexto**

Local: Na tela inicial.
Tempo: A qualquer momento.
Pré-condição: Não se aplica.

**Atores**

Usuário.

**Recursos**

Um _smartphone_ com o aplicativo instalado.

**Episódios**

Usuário entra no aplicativo e consegue ver todos os medicamentos.

**Restrições**

O usuário mudou de tela ao entrar no aplicativo.

**Exceções**

O usuário não possui o aplicativo.

### Cenário 015

**-> Deixar o aplicativo intuitivo para o usuário leigo <-**

**Objetivo**

Configurar o aplicativo para que um usuário sem/com pouco conhecimento na área da saúde possa utilizá-lo sem dificuldade.

**Contexto**

Local: Em qualquer tela da aplicação.
Tempo: A qualquer momento.
Pré-condição: Não se aplica.

**Atores**

Desenvolvedores e usuários.

**Recursos**

Conhecimento em Angular (Ionic 2).

**Episódios**

Desenvolvedor facilita a utilização da aplicação.
Usuário entra no aplicativo.
Usuário reconhece todos os ícones e funcionalidades do aplicativo.

**Restrições**

O desenvolvedor não simplifica a aplicação.

**Exceções**

O usuário desinstala a aplicação pela dificuldade no conhecimento das funcionalidades.

### Cenário 016

**-> *Link*ar as referências das informações <-**

**Objetivo**

Ao final de cada monografia dos medicamentos, deve haver uma referência bibliográfica, para que os usuários saibam de onde vem a informação disponível ali na aplicação.

**Contexto**

Local: Na tela de qualquer medicamento.
Tempo: A qualquer momento.
Pré-condição: Possuir um _link_ para referenciamento.

**Atores**

Desenvolvedores.

**Recursos**

Conhecimento em Angular (Ionic 2) e deter de um _link_ para referenciamento das informações.

**Episódios**

Desenvolvedor disponibiliza a monografia.
Ao final do texto, desenvolvedor referencia a informação.

**Restrições**

Informações precisam estar atualizadas.

**Exceções**

O _link_ está quebrado, por alterações do autor da informação referenciada.

### Cenário 017

**-> Alterar o tamanho da fonte do texto <-**

**Objetivo**

Alterar o tamanho da fonte do texto das monografias para facilitar a leitura para usuários com dificuldades de visão e/ou que preferem outros tamanhos de fonte.

**Contexto**

Local: Na tela de qualquer medicamento.
Tempo: A qualquer momento.
Pré-condição: Problemas de visão.

**Atores**

Usuários.

**Recursos**

Um _smartphone_ com o aplicativo instalado e com acesso à internet.

**Episódios**

Usuário entra no aplicativo.
Usuário clica em qualquer medicamento.
Usuário clica no ícone de texto, no canto inferior da tela.

**Restrições**

O usuário escolheu uma fonte que não condiz com sua dificuldade visual.

**Exceções**

O usuário não possui dificuldades visuais.

## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 10): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 35 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668162/mod_resource/content/1/Aula%2010.pdf. Acesso em: 04 mar. 2022.

## Histórico de versões

| Versão  |   Data   |                        Alteração                         |  Responsável  |    Revisão    |
| :-----: | :------: | :------------------------------------------------------: | :-----------: | :-----------: |
|  0.0.1  | 04/03/22 |                         Criação                          |  João Durso   |    Adrian     |
|  0.0.2  | 05/03/22 |                   Cenários (001 a 008)                   |  João Durso   | Gabriel Costa |
|  0.0.3  | 05/03/22 | Adição de restrições e exceções nos cenários (001 a 008) |  João Durso   | Gabriel Costa |
|  0.0.4  | 05/03/22 |                    Correção de texto                     |  João Durso   | Gabriel Costa |
| 0.0.4.1 | 05/03/22 |                    Correção de texto                     |  João Durso   | Gabriel Costa |
| 0.0.4.2 | 05/03/22 |         Correção de texto e criação do template          | Gabriel Costa |  João Durso   |
|  0.0.5  | 05/03/22 |                   Cenários (009 a 018)                   |  João Durso   | Gabriel Costa |
|  0.0.6  | 19/04/22 |                     Correção textual                     |  João Durso   | Gabriel Costa |
|  1.0.0  | 22/04/22 |                 Correções da verificação                 |  João Durso   | Gabriel Costa |
