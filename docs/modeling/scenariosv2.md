# Cenários

## 1. Introdução

<p style="text-indent: 20px; text-align: justify">
Cenário é uma cena que ilustra a interação entre ambientes e um sistema proposto. Ademais, é uma ferramenta extremamente utilizada durante a análise de requerimentos para descrever o uso de um sistema. Os cenários capturam o sistema, visto de fora, por exemplo, por um usuário, usando exemplo específicos. Para isso, faz uso de algumas abstrações, como título, objetivos, contexto, ator(es), recursos, exceções, episódios e restrições.
</p>

## 2. Metodologia

<p style="text-indent: 20px; text-align: justify">
A partir do <a href="https://requisitos-de-software.github.io/2021.2-MedSUS/elicitation/brainstorm/">Brainstorm</a> realizado em uma reunião com todos os membros do grupo, conseguimos levantar alguns requisitos básicos. A partir desses requisitos, buscamos escrever e detalhar os cenários do sistema. Esta técnica descreve os requisitos numa linguagem mais fácil de entender e validar. Além disso, facilitam a criação dos casos de uso posteriormente.
</p>

## 3. Cenários

<div class="container">
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 001</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Pesquisar medicamentos por nome</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Buscar por medicamento específico para o encontrar mais facilmente.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Tela inicial.<br>Tempo: A qualquer momento.<br>Pré-condição: Não se aplica. 
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra na tela inicial.<br>Usuário clica no ícone de pesquisa, no canto superior direito.<br>Usuário pesquisa o medicamento desejado.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item"> Smartphone incapaz de executar o aplicativo corretamente.<br>Falha na conexão com a internet.<br>Usuário não sabe o nome do medicamento.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário faz uma pesquisa ineficiente (Ex.: erra o nome do medicamento)</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 002</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Compartilhar medicamentos</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Compartilhar medicamentos para outras pessoas.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela de qualquer medicamento.<br>Tempo: A qualquer momento.<br>Pré-condição: Não se aplica. 
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra na tela inicial.<br>Usuário procura pelo medicamento desejado.<br>Usuário clica no ícone do meio, na aba inferior.<br>Usuário escolhe onde irá compartilhar as informações.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Só é possível compartilhar em um outro aplicativo por vez.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Destinatário não possui nenhum aplicativo para receber o compartilhamento.</li>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 003</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Favoritar medicamentos</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Favoritar medicamentos para guardar os medicamentos que possuem preferência.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela inicial ou na tela de qualquer medicamento.<br>Tempo: A qualquer momento.<br>Pré-condição: Não se aplica. 
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra na tela inicial.<br>Usuário procura pelo medicamento desejado.<br>Usuário clica no ícone de favoritar - atrás do nome do medicamento.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Medicamento não existe no sistema.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Nenhuma exceção foi encontrada.</li>
                    </ul>
                </div>
            </div>
        </div>
            <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 004</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Filtrar medicamento por GAP</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Filtrar medicamentos por Grupo Anatômico Principal, para diminuir as opções e facilitar a busca.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela inicial.<br>Tempo: A qualquer momento.<br>Pré-condição: Saber a que categoria do GPA o remédio desejado pertence. 
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra na tela inicial.<br>Usuário clica no ícone de filtragem, acima do canto inferior direito.<br>Usuário clica na(s) categoria(s) do GPA que o medicamento desejado pode se encaixar.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário escolhe a categoria errada do GPA.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário não conhece o Grupo Anatômico Principal.</li>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 005</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Filtrar medicamento por anexo da RENAME</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Filtrar medicamentos por anexo da RENAME, para diminuir as opções e facilitar a busca.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela inicial.<br>Tempo: A qualquer momento.<br>Pré-condição: Saber a que categoria do anexo da RENAME o remédio desejado pertence.
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra na tela inicial.<br>Usuário clica no ícone de filtragem, acima do canto inferior direito.<br>Usuário clica na(s) categoria(s) do anexo da RENAME que o medicamento desejado se encaixa.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário escolhe a categoria errada do anexo da RENAME.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário não conhece o anexo da RENAME.</li>
                    </ul>
                </div>
            </div>
        </div>
            <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 006</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Filtrar medicamento por controle especial</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Filtrar medicamentos por controle especial, para diminuir as opções e facilitar a busca.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela inicial.<br>Tempo: A qualquer momento.<br>Pré-condição: Saber a que categoria do controle especial o remédio desejado pertence. 
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra na tela inicial.<br>Usuário clica no ícone de filtragem, acima do canto inferior direito.<br>Usuário clica na(s) categoria(s) do controle especial que o medicamento desejado se encaixa.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário escolhe a categoria errada do controle especial.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário desconhece o controle especial.</li>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 007</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Filtrar medicamento por existência de genérico</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Filtrar medicamentos por existência (ou não) de genérico, para diminuir as opções e facilitar a busca.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela inicial.<br>Tempo: A qualquer momento.<br>Pré-condição: Saber se o remédio possui versão genérica ou não.
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra na tela inicial.<br>Usuário clica no ícone de filtragem, acima do canto inferior direito.<br>Usuário clica na opção 'Sim', se possui genérico e 'Não', caso não possua.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário possui dúvida quanto à existência da versão genérica.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Rede do usuário cai.</li>
                    </ul>
                </div>
            </div>
        </div>
            <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 008</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Filtrar medicamento por controle especial</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Filtrar medicamentos por controle especial, para diminuir as opções e facilitar a busca.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela inicial.<br>Tempo: A qualquer momento.<br>Pré-condição: Saber a que categoria do controle especial o remédio desejado pertence. 
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra na tela inicial.<br>Usuário clica no ícone de filtragem, acima do canto inferior direito.<br>Usuário clica na(s) categoria(s) do controle especial que o medicamento desejado se encaixa.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário escolhe a categoria errada do controle especial.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário desconhece o controle especial.</li>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 009</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Notificar a adição de um medicamento</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Notificar ao usuário a adição de um medicamento no aplicativo, a fim de deixá-lo sempre atualizado.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Em qualquer tela do celular.<br>Tempo: A qualquer momento.<br>Pré-condição: Possuir as notificações do aplicativo ligadas e estar conectado à internet.
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário recebe a notificação na tela do celular.<br>Usuário entra no aplicativo.<br>Usuário clica no ícone do meio, da aba inferior do aplicativo.<br>Usuário clica no meio da aba superior do aplicativo (Inclusão).</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário desligou as notificações.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Nenhum medicamento foi adicionado.</li>
                    </ul>
                </div>
            </div>
        </div>
            <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 010</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Notificar a remoção de um medicamento</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Notificar ao usuário a remoção de um medicamento no aplicativo, a fim de deixá-lo sempre atualizado.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Em qualquer tela do celular. <br>Tempo: A qualquer momento.<br>Pré-condição: Possuir as notificações do aplicativo ligadas e estar conectado à internet.
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário recebe a notificação na tela do celular.<br>Usuário entra no aplicativo.<br>Usuário clica no ícone do meio, da aba inferior do aplicativo.<br>Usuário clica no meio da aba superior do aplicativo (Exclusão).</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário desligou as notificações.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Nenhum medicamento foi removido.</li>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 011</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Notificar a alteração de um medicamento</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Notificar ao usuário a alteração de um medicamento no aplicativo, a fim de deixá-lo sempre atualizado.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Em qualquer tela do celular.<br>Tempo: A qualquer momento.<br>Pré-condição: Possuir as notificações do aplicativo ligadas e estar conectado à internet.
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário recebe a notificação na tela do celular.<br>Usuário entra no aplicativo.<br>Usuário clica no ícone do meio, da aba inferior do aplicativo.<br>Usuário clica no meio da aba superior do aplicativo (Alteração).</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário desligou as notificações.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Nenhum medicamento foi alterado.</li>
                    </ul>
                </div>
            </div>
        </div>
            <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 012</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Pesquisar palavras-chave no texto das monografias</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Buscar palavras-chave no texto, para facilitar a leitura.<p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela de qualquer medicamento.<br>Tempo: A qualquer momento.<br>Pré-condição: Não achar o local de leitura desejado.
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra no aplicativo.<br>Usuário clica no medicamento desejado.<br>Usuário clica na aba de texto, na parte superior da tela.<br>Usuário digita a palavra-chave que deseja procurar no texto.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário digitou errado a palavra-chave.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">A palavra-chave não existe no texto.</li>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 013</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Visualizar o índice das informações de um medicamento</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Buscar o texto por meio do uso de um sumário, no qual os títulos mais importantes estão expostos por índice.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela inicial.<br>Tempo: A qualquer momento.<br>Pré-condição: Não se aplica.
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra no aplicativo.<br>Usuário clica no medicamento desejado.<br>Usuário clica no ícone de lista, no canto inferior esquerdo.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário clicou no título errado.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O título que o usuário procura não existe no texto.</li>
                    </ul>
                </div>
            </div>
        </div>
            <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 014</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Saber os medicamentos de prioridade para o SUS/RENAME</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Todos os medicamentos listados no aplicativo MedSUS são aprovados e listados pela RENAME, por isso o usuário possui confiabiliadade quanto ao uso das substâncias.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela inicial.<br>Tempo: A qualquer momento.<br>Pré-condição: não se aplica.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra no aplicativo e consegue ver todos os medicamentos.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário mudou de tela ao entrar no aplicativo.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário não possui o aplicativo.</li>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 015</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Deixar o aplicativo intuitivo para o usuário leigo</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Configurar o aplicativo para que um usuário sem/com pouco conhecimento na área da saúde possa utilizá-lo sem dificuldade.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Em qualquer tela da aplicação.<br>Tempo: A qualquer momento.<br>Pré-condição: Não se aplica.
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Desenvolvedores e usuários.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Conhecimento em Angular (Ionic 2).</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Desenvolvedor facilita a utilização da aplicação.<br>Usuário entra no aplicativo.<br>Usuário reconhece todos os ícones e funcionalidades do aplicativo.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O desenvolvedor não simplifica a aplicação.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário desinstala a aplicação pela dificuldade no conhecimento das funcionalidades.</li>
                    </ul>
                </div>
            </div>
        </div>
            <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 016</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Linkar as referências das informações</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Ao final de cada monografia dos medicamentos, deve haver uma referência bibliográfica, para que os usuários saibam de onde vem a informação disponível ali na aplicação.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela de qualquer medicamento.<br>Tempo: A qualquer momento.<br>Pré-condição: Possuir um link para referenciamento.
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Desenvolvedores.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Conhecimento em Angular (Ionic 2) e deter de um link para referenciamento das informações.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Desenvolvedor disponibiliza a monografia.<br>Ao final do texto, desenvolvedor referencia a informação.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Informações precisam ser atualizadas.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O link está quebrado, por alterações do autor da informação referenciada.</li>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6 d-flex align-items-stretch">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Cenário 017</h4>
                    <h5 class="card-title text-white text-center m-1 font-weight-bold">Alterar o tamanho da fonte do texto</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Objetivo</h5>
                    <p class="list-group-item">Alterar o tamanho da fonte do texto das monografias para facilitar a leitura para usuários com dificuldades de visão e/ou que preferem outros tamanhos de fonte.</p>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Contexto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local: Na tela de qualquer medicamento.<br>Tempo: A qualquer momento.<br>Pré-condição: Problemas de visão ou preferências de tamanho.
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Atores</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Recursos</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Um smartphone com o aplicativo instalado e com acesso à internet.</li>
                    </ul>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Episódios</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário entra no aplicativo.<br>Usuário clica em qualquer medicamento.<br>Usuário clica no ícone de texto, no canto inferior da tela.</li>
                    </ul>
                </div>  
                <div class="card-footer p-2">
                    <h5 class="card-text">Restrições</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário escolheu uma fonte que não condiz com sua dificuldade visual.</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Exceções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">O usuário não possui dificuldades visuais.</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

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
|  1.0.0  | 22/04/22 |                      Novo template                       |  João Durso   | Gabriel Costa |
