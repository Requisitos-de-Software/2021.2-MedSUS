# Caso de uso

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
A modelagem de caso de uso é uma abstração do sistema baseado em ações do usuário, ou seja, mostram como o sistema
deve se comportar com um determinado conjunto de ações.  Deste modo, os casos de uso que tem como objetivo não só ajudar
a extrair os requisitos, como também documentar o sistema. 

Isso significa que, durante o processo de elicitação essa modelagem pode ser usada com foco de discussão com os stakeholders, 
desta forma, deve possuir uma linguagem simples, natural e intuitiva. 

Além disso, durante a fase de projeto, são usados para descrever o sistema para os engenheiros que o implementam. 
</p>

## 2. Metodologia
<p style="text-indent: 20px; text-align: justify">
Para a criação de desse artefato escolhemos a abordagem tradicional, ou seja, representar os casos de uso através um diagrama UML.
A ferramenta escolhida para criar essa representação foi o creately. Além disso, o grupo teve como referência o resultado da elicitação e os 
cenários para a criação desse artefato.  
</p>

## 3. Casos de Uso
### UC00 - título
|UC00|Descrição|
|       :-:                   |--|
|Descrição        |Uma breve descrição |
|Ator             |São entidades externas ao sistema que participam de um ou mais casos de uso normalmente ou fornecem eventos de entrada ou recebem alguma resposta do sistema.|
|Pré-condições    |é o estado do sistema e de seus arredores que é necessário para que o caso de uso possa ser iniciado|
|Fluxo Principal  |descreve a funcionalidade principal do caso de uso, quando nenhum desvio é tomado   |
|Fluxo Alternativo|especificam interações alternativas com a mesma meta.|
|Pós-condições    |As Pós-Condições são os estados que o sistema pode ficar depois do caso de uso terminar   |

#### Legenda


| relacionamentos          | descrição |
| --------      | -------- |
| Generalização | Uma generalização entre um caso de uso C e um caso de uso D indica que C é umaespecialização de D. Este relacionamento é representado por uma seta de generalização partindo de D para C.   |
|  << include >>  |permitir a reutilização de um determinado comportamento de umcaso de uso por outros casos de uso |
|  << extend >>  | Um relacionamento de "extend" é usado para mostrar: comportamento opcional, comportamento que somente é executado sobre determinadas condições|


<!-- link dos para ediar os casos https://app.creately.com/d/Qv2g5exxYgb/edit -->
### Caso de Uso - Geral
 <p align="center">
  <img src="../assets/usecase000.png" alt="MedSus"/>
</p>

### UC01 - Pesquisa de Medicamento

 <p align="center">
  <img src="../assets/usecase001.png" alt="MedSus"/>
</p>

|UC01|Descrição|
|       :-:                   |--|
|Descrição        |O usuário pesquisa por um medicamento   |
|Ator             |todos|
|Pré-condições    |Celular com acesso à internet e com o aplicativo instalado   |
|Fluxo Principal  | >  O usuário entra na secção de pesquisa <br> > Seleciona ou não alguns filtros para a sua pesquisa   <br> > Digita um nome de medicamento <br> > Confirma a pesquisa |
|Fluxo Alternativo|Caso nenhum remédio seja encontrado o sistema avisa que a busca não obteve resultado  |
|Pós-condições    |O aplicativo continua na tela de pesquisa ou entre na página de um medicamento se algum for selecionado|


### UC02 - Visualizar Medicamento

 <p align="center">
  <img src="../assets/usecase002.png" alt="MedSus"/>
</p>


|UC02|Descrição|
|       :-:                   |--|
|Descrição        | O usuário escolhe as informações que deseja visualizar |
|Ator             |todos|
|Pré-condições    | Pesquisar o medicamento |
|Fluxo Principal  | > Entrar na página do medicamento <br> >  escolher o tipo de informação ( para leigos ou para usuários avançados )|
|Fluxo Alternativo| não se aplica |
|Pós-condições    | O aplicativo continua na página de visualização do medicamento |


### UC03 - Compartilhar Medicamento

 <p align="center">
  <img src="../assets/usecase003.png" alt="MedSus"/>
</p>

|UC03|Descrição|
|       :-:                   |--|
|Descrição        | O usuário compartilha um medicamento em formato PDF|
|Ator             |todos|
|Pré-condições    | Pesquisar o medicamento |
|Fluxo Principal  | > Entrar na página do medicamento <br> > Escolher um aplicativo para exportar o PDF   |
|Fluxo Alternativo| não se aplica |
|Pós-condições    | O aplicativo continua na página de visualização do medicamento |

## Referências bibliográficas

https://www.cin.ufpe.br/~rls2/processo_tg/Metodologia%20S&B/guidances/concepts/use_case_8F95459C.html#:~:text=Uma%20precondi%C3%A7%C3%A3o%20%C3%A9%20o%20estado,do%20caso%20de%20uso%20terminar.

## Histórico de versões

| Versão  |   Data   |                        Alteração                         | Responsável   |    Revisão    |
| :-----: | :------: | :------------------------------------------------------: | :---------:   | :-----------: |
|  0.0.1  | 05/03/22 |                         Criação                          | Gabriel Costa |         |
