# Cenários

## 1. Introdução
<p style="text-indent: 20px; text-align: justify">
Cenário é que uma cena que ilustra a interação entre ambientes e um sistema proposto. Ademais, é uma ferramenta extremamente utilizada durante a análise de requerimentos para descrever o uso de um sistema. Os cenários capturam o sistema, visto de fora, por exemplo, por um usuário, usando exemplo específicos. Para isso, faz uso de algumas abstrações, como título, objetivos, contexto, ator(es), recursos, exceções, episódios e restrições.
</p>


## 2. Metodologia
<p style="text-indent: 20px; text-align: justify">
A partir do Brainstorming realizado em uma reunião com todos os membros do grupo, conseguimos levantar alguns requisitos básicos. A partir desses requisitos, buscamos escrever e detalhar os cenários do sistema. Esta técnica descreve os requisitos numa linguagem mais fácil de entender e validar. Além disso, facilitam a criação dos casos de uso posteriormente.
</p>

## 3. Cenários

### Cenário 001
**-> Pesquisar medicamentos por nome <-**

**Objetivo** 
Buscar por medicamento específico para facilitar achá-lo.
**Contexto** 
Local: Tela inicial.
Tempo: A qualquer momento.
Pré-condição: Não se aplica.
**Atores** 
Usuário.
**Recursos** 
Não se aplica.
**Episódios**
Usuário entra na tela inicial.
Usuário clica no ícone de pesquisa, no canto superior direito.
Usuário pesquisa o medicamento desejado.
**Restrições**
Errar o nome do medicamento.
**Exceções**
Usuário não sabe o nome do medicamento.

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
Não se aplica.
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
Não se aplica.
**Episódios**
Usuário entra na tela inicial.
Usuário procura pelo medicamento desejado.
Usuário clica no ícone de favoritar - atrás do nome do medicamento.
**Restrições**
Nenhuma restrição foi encontrada.
**Exceções**
Medicamento não existe no sistema.

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
Não se aplica.
**Episódios**
Usuário entra na tela inicial.
Usuário clica no ícone de filtragem, acima do canto inferior direito.
Usuário clica na(s) categoria(s) do GPA que o medicamento desejado pode se encaixar.
**Restrições**
Usuário escolhe a categoria errada do GPA.
**Exceções**
Usuário não conhece o Grupo Anatômico Principal.

### Cenário 004
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
Não se aplica.
**Episódios**
Usuário entra na tela inicial.
Usuário clica no ícone de filtragem, acima do canto inferior direito.
Usuário clica na(s) categoria(s) do anexo da RENAME que o medicamento desejado se encaixa.
**Restrições**
Usuário escolhe a categoria errada do anexo da RENAME.
**Exceções**
Usuário não conhece o anexo da RENAME.

### Cenário 005
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
Não se aplica.
**Episódios**
Usuário entra na tela inicial.
Usuário clica no ícone de filtragem, acima do canto inferior direito.
Usuário clica na(s) categoria(s) do controle especial que o medicamento desejado se encaixa.
**Restrições**
Usuário escolhe a categoria errada do controle especial.
**Exceções**
Usuário desconhece o controle especial.

### Cenário 006
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
Não se aplica.
**Episódios**
Usuário entra na tela inicial.
Usuário clica no ícone de filtragem, acima do canto inferior direito.
Usuário clica na opção 'Sim', se possui genérico e 'Não', caso não possua.
**Restrições**
Usuário possui dúvida quanto à existência da versão genérica.
**Exceções**
Rede do usuário cai.


### Cenário 007
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
Não se aplica.
**Episódios**
Usuário entra no aplicativo.
Usuário clica no medicamento desejado.
Usuário seleciona o seu perfil (profissional da saúde ou usuário comum), na aba superior do aplicativo.
**Restrições**
(preencher... app off-line)
**Exceções**
(preencher... app off-line)

### Cenário 008
**-> Notificar a adição de um medicamento <-** 

**Objetivo** 
Notificar ao usuário a adição de um medicamento no aplicativo, a fim de deixá-lo sempre atualizado.
**Contexto** 
Local: Em qualquer tela do celular.
Tempo: A qualquer momento.
Pré-condição: Possuir as notificações do aplicativo ligadas e estar conectado a internet.
**Atores** 
Usuário.
**Recursos** 
Não se aplica.
**Episódios**
Usuário recebe a notificação na tela do celular.
Usuário entra no aplicativo.
Usuário clica no ícone do meio, da aba inferior do aplicativo.
Usuário clica no meio da aba superior do aplicativo (Inclusão).
**Restrições**
O usuário desligou as notificações.
**Exceções**
Nenhum medicamento foi adicionado.

## Referências bibliográficas

> SERRANO, Milene; SERRANO, Maurício. Requisitos (Aula 10): Elicitação, Modelagem e Análise. 2022. Apresentação de Power Point. 35 slides. color. Disponível em: https://aprender3.unb.br/pluginfile.php/1668162/mod_resource/content/1/Aula%2010.pdf. Acesso em: 04 mar. 2022.

## Histórico de versões

Versão|Data|Alteração|Responsável|Revisão|
:-:|:-:|:-:|:-:|:-:|
0.0.1|04/03/22|Criação|João Durso|Adrian|
0.0.2|05/03/22|Cenários (001 a 008)|João Durso|Gabriel Costa|
0.0.3|05/03/22|Adição de restrições e exceções nos cenários (001 a 008)|João Durso|Gabriel Costa|


