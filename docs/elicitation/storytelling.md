# Storytelling (Histórias)

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
As histórias, similarmante aos cenários, são uma forma de elicitar requisitos, criando uma narrativa para que se possa enxergar as formas em que o sistema pode ser utilizado. Conseguimos descrever o que as pessoas fazem, como e quais informações elas usam e geram através das tarefas. São histórias de alto nível que aproximam os projetistas e desenvolvedores das necessidades dos usuários. É muito mais fácil de se identificar com algo através de narrativas [Sommerville, 2019, p. 102](referencias-bibliograficas) , o que facilita o entendimento dos requisitos para a equipe de desenvolvimento.
</p>

<p style="text-indent: 20px; text-align: justify">
Também existe o artefato de Cenários para a elicitação, que funciona de forma similar às histórias. Apesar disso, a estrutura dos cenários é diferente, sendo mais rígida, especificando entradas e saídas.
</p>

<p style="text-indent: 20px; text-align: justify">
A forma escolhida foi o storytelling, pois é boa para estabelecer um panorama geral [Sommerville, 2019, p. 102](referencias-bibliograficas) e poderá ainda auxiliar na criação de cenários para o futuro. 
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
A metodologia utilizada foi notar alguns requisitos básicos através de um brainstorming onde estabelecemos uma persona básica que representa o App. A partir dessa persona, desenvolvemos um storytelling para ela e tentamos identificar mais personas para desenvolver seus storytellings. As histórias desenvolvem detalhes das tarefas e dos objetivos e sentimentos dos usuário. Quanto mais detalhes que sirvam a narrativa, melhor será.
</p>

## 3. Storytelling

### 3.1. Pesquisa de medicação durante consulta

<p style="text-indent: 20px; text-align: justify">
Em seu consultório, Dr. Gilherme teve um dia duro de atendimentos. Ele já tem uma certa idade (60 anos) e fica muito cansado em um dia de trabalho atribulado. Ele é um médico  pediatra e em sua última consulta do dia, atendeu à Dona Nenê e seu filho João.  
</p>

<p style="text-indent: 20px; text-align: justify">
Após o diagnóstico dos sintomas de João, Dr. Guilherme passou uma receita para que a Dona Nenê possa pegar a medicação na farmácia do hospital. Dona Nenê, porém, preocupada com a saúde de seu fiho, pergunta se há algum efeito colateral significativo. O Dr. então, por toda a sua condição, não consegue lembrar imediatamente desses efeitos pelo medicamento, pois é um medicamento que ele passou a receitar recentemente. Em pesquisas passadas, comparando as medicações, ele achou essa melhor para certos casos de doenças.
</p>

<p style="text-indent: 20px; text-align: justify">
Ele pega o celular para fazer uma pesquisa rápida, apesar de suas vistas cansadas. O App MedSus acaba sendo uma melhor opção pois é uma ambiente focado em medicações e com fontes confiáveis. Ele rapidamente pega o celular, abre o app e começa a rolar em direção a letra inicial da medicação que receitou. Logo ele lembra que é possível buscar diretamente a medicação. Muito rapidamente, então, ele consegue achar o medicamento após a busca. Ao clicar, ele lê a bula e repassa, enfim, os efeitos colaterais comuns para a mãe devidamente preocupada.
</p>

### 3.2. Compartilhamento de medicações em Telemedicina

<p style="text-indent: 20px; text-align: justify">
Juliana está em uma consulta virtual com sua psiquiatra Dra. Fernanda. Ela está em sua primeira consulta e ainda não se encontra muito confiante sobre o tratamento e sobre como funcionam as medicações. Pede então para sua médica algumas informações sobre o medicamento o qual a médica, em breve, irá receitar. A médica, então, para ajudar sua paciente, envia, além da receita, a bula da medicação, através do compartilhamento do app medSus. O aplicativo envia um arquivo PDF, pois, não necessariamente, a pessoa que irá receber as informações tem acesso ao App. O arquivo é enviado através de um aplicativo de mensagens, daqueles que a maioria das pessoas já utilizam.
</p>

<p style="text-indent: 20px; text-align: justify">
Juliana fica feliz com a agilidade do compartilhamento e logo abre o documento. Após ficar um pouco perdida com a quantidade de informações, ela acha as informações que mais a interessavam, como os objetivos principais do tratamento com essa medicação, seus efeitos colaterais e o modo de uso.
</p>

### 3.3. Relembrar medicações

<p style="text-indent: 20px; text-align: justify">
Por conta das diversas medicações que toma, sra. Dercy, que troca de médico muitas vezes já que mora com seu filho, Pedro, que muda de moradia constantemente por conta de seu trabalho como o representante comercial de uma empresa multinacional. Ela gosta de saber as medicações que ela já utilizou e as que melhor funcionaram, para poder discutir com seu médico. Porém, sua memória já não é mais como em seus tempos áureos (apesar dela não querer admitir) e por isso precisa de uma ajudinha. Seu filho, então, instalou em seu celular, o app do MedSus e favoritou os remédios que a sua mãe usou, para que ela possa mostrar para seu médico e evitar o esquecimento dos nomes.
</p>
<p style="text-indent: 20px; text-align: justify">
Apesar de não ser tão ligada nessas questões de tecnologia, sra. Dercy usa costumeiramente seu celular, principalmente os aplicativos de mensagem mais comuns. Ela achou muito "supimpa" pois conseguiu localizar facilmente os medicamentos salvos atravé do ícone de "estrela".
</p>

## 4. Conclusão

O objetivo das histórias é chegar em alguns objetivos e ter uma boa ideia geral do funcionamento da aplicação e sobre o que os usuários esperam. Os requisitos identificados seguem a seguir:

### 4.1. Requisitos

**Legenda:**
  - ST: Requisitos de Storytelling

|Identificador|Descrição|
|:-:|:-|
|ST01|O app precisa mostrar os efeitos colaterais das medicações|
|ST02|O app deve ser otimizado para a experiência mobile|
|ST03|O app deve usar uma base de dados confiáveis|
|ST04|O app deve disponibilizar busca|
|ST05|A ferramenta de busca é a principal e deve ser diponibilizada ao abrir o app|
|ST06|O app deve fornecer a lista ordenada de remédios|
|ST07|A busca de medicamentos deve retornar rapidamente os resultados|
|ST08|O app deve gerar arquivos para compartilhar com qualquer outra pessoa|
|ST09|O app deve utilizar as APIs disponíveis para compartilhamento através dos aplicativos de comunicação mais comuns (E-mail e mensagens)|
|ST10|O documento gerado pela aplicação deve ter um índice com links para as seções da bula|
|ST11|A bula disponibilizada deve conter as indicações e contra-indicações do remédio|
|ST12|A bula disponibilizada deve conter o modo de uso da medicação|
|ST13|A aplicação deve fornecer opções de acessibilidade para quem tem visão ruim|
|ST14|Deve ser possível favoritar as medicações|
|ST15|O app deve conseguir marcas (favoritar) medicações vinculadas ao usuário e não só ao dispositivo|
|ST16|A aplicação deve utilizar ícones comuns ao domínio mobile (mais utilizado)|

## Referências bibliográficas

> Sommerville, I., Engenharia de software, 10ª ed., Editora Pearson, 2019.
> Santos, V. G., Daher N., UTILIZAÇÃO DE STORYTELLING COMO FERRAMENTA DE AQUISIÇÃO DE REQUISITOS EM PROCESSO DE DESENVOLVIMENTO DE SOFTWARE APOIADOS EM MODELOS ÁGEIS: O USO APOIADO NO EXTREME PROGRAMMING, Belo Horizonte, 2008. 14 p., Artigo (Análise de Sistemas), e-tec UNI-BH

## Histórico de versões

Versão|Data|Alteração|Responsável|Revisão|
:-:|:-:|:-:|:-:|:-:|
0.0.1|17/02/22|Criação|Adrian e João Durso||
0.0.2|18/02/22|Introdução e História 1|Adrian||
0.0.3|19/02/22|Históia 2 e Requisitos Levantados|Adrian||
