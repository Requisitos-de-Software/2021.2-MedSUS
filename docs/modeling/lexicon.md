# Léxicos

## 1. Introdução
  
<p class="paragraph">
    O léxico é uma impotante ferramenta para entender o vocabulário dentro do escopo do problema que será solucionado. Com ele, busca-se descrever as principais palavras pertencentes ao universo do usuário e ao uso do sistema, e a relação dessas palavras.   
</p>
<p class="paragraph">
    Considerando que no processo de elicitação, modelagem e análise, como também em todo o desenvolvimento de um software, participam profissionais com diferentes funções e competências, termos técnicos ou de significado diverso do usual podem dar margem a diferentes interpretações para um mesmo termo ou expressão (CONSTRUÇÃO..., 2006, p. 2) . Com o Léxico, consegue-se garantir uma melhor compreensão da pŕopria aplicação para os desenvolvedores e o apoio ao levantamento de requisitos.
</p>
<p class="paragraph">
    Os léxicos poderão ser usados para uma rastrabilidade dos termos quando forem utilizados, através de referências por links internos e externos pelas páginas do nosso projeto.
</p>


## 2. Metodologia

<p class="paragraph">
    Através da utilização do aplicativo e da consulta a fontes do <a href="#sus">SUS</a> e da Anvisa, levantamos significados dos vocábulos e o papel dele dentro do sistema. Os Léxicos podem ser objetos, verbos(ações) ou estados, para todos eles temos as noções e seus impactos no domínio. Podemos resumir suas descrições da seguinte maneira:
</p>

|  Tipo |Noção|Impacto|
|  ---  | --- |  ---  |
|Verbo|Quem Realiza, Quando e Quais os procedimentos|Ações decorrentes e novos estados|
|Objeto|Definição do objeto e objetos relacionados|Ações aplicáveis ao objeto|
|Estado|O que significa e quais ações o geram|Estados decorrentes|

## 3. Léxicos

# Letra A

<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div id="adicionar-medicamento"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Adicionar Medicamento</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Adicionar novos medicamentos que foram agregados ao <a href="#rename">RENAME</a></li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Adição à <a href="#lista-medicamentos">lista de medicamentos</a></li>
                        <li class="m-0 list-group-item">Gera <a href="#lista-medicamentos">notificação</a> aos usuários do sistema</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="col-sm-6">
            <div id="administracao" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Administração</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text"> Noções </h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item ">As formas de uso de um <a href="#medicamento">medicamento</a>
                        </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Consta na <a href="#bula">bula</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6">
            <div id="advertencia" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Advertência</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">
                            Cuidados que se deve ter ao manipular o <a href="#medicamento">medicamento</a>
                        </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Consta na <a href="#bula">bula</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>

# Letra B

<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div id="barra-pesquisa" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Barra de Pesquisa</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Local responsável por uma das formas de <a
                                href="#filtro">filtro</a>
                        </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Realiza a <a href="#busca-medicamento">busca de medicamentos</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="col-sm-6">
            <div id="bula" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Bula</h4>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">
                            Documento legal sanitário que serve para obter informações e orientações sobre <a
                                href="#medicamento">medicamentos</a> necessárias
                            para o uso seguro e <a href="#tratamento">tratamento</a> eficaz.
                        </li>
                        <li class="m-0 list-group-item">
                            Pode ser de dois tipos: <a href="#bula-paciente">Bula para o Paciente</a> e
                            <a href="#bula-profissional-saude">Bula para o Profissional da Saúde</a>.
                        </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">
                            Contém informações sobre a <a href="#prescricao">prescrição</a>, <a
                                href="#preparacao">preparação</a>,
                            <a href="#administracao">administração</a> e <a href="#advertencia">advertência</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="pd-0 col-sm-6">
            <div id="bula-paciente" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Bula para o Paciente</h4>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">
                            <a href="#bula">Bula</a> com informações menos técnicas, para os <a
                                href="#usuario-leigo">usuários leigos</a>
                        </li>
                        <li class="m-0 list-group-item">
                            Disponível em separado da <a href="#bula-profissional-saude">Bula para o Profissional da
                                Saúde</a>.
                        </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Contém Identificação do <a href="#medicamento">medicamento</a>,
                            Informações ao <a href="#paciente">paciente</a> e Dizeres Legais</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="col-sm-6">
            <div id="bula-profissional-saude" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Bula para o Profissional de Saúde
                        </h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Disponível em separado da <a href="#bula-paciente">Bula para o
                                Paciente</a></li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Contém as informações técnicas e legais</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <br>
    <div class="row">
        <div class="col-sm-6">
            <div id="busca-medicamento" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Busca de medicamento</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Realizada pelo <a href="#usuario-saude">
                                usuário da área da saúde</a> ou pelo <a href="#usuario-leigo">usuário leigo</a>
                        </li>
                        <li class="m-0 list-group-item">Podem ser aplicados outros <a href="#filtro">filtros</a></li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">
                            <a href="#lista-medicamentos">lista de medicamentos</a> filtrada com 0 ou muitos resultados
                        </li>
                        <li class="m-0 list-group-item">
                            pode-se acessar a <a href="#bula">bula</a> dos
                            <a href="#medicamentos">medicamentos</a> <a href="#filtro">filtrados</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>

# Letra C

<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div id="compartilhar" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Compartilhar</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Realizado pelo usuário para envio de alguma <a
                                href="#bula">bula</a>
                            específica para qualquer outra pessoa
                        </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Geração de arquivo <a href="#pdf">PDF</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>
<!--
# Letra D
<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">LÉXICO</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">a</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">a</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>
-->

# Letra F

<div class="container">
    <div class="row">
        <div class="pd-0 col-sm-6">
            <div id="filtro" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Filtrar Medicamentos</h4>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Restrição da <a href="#lista-medicamentos">lista de medicamentos</a></li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Configurável para melhor restrição</li>
                        <li class="m-0 list-group-item">Possível recuperar somente <a href="#generico">genéricos</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>

# Letra L

<div class="container">
    <div class="row">
        <div class="pd-0 col-sm-6">
            <div id="lista-medicamentos" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Lista de Medicamentos</h4>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Constantes na <a href="#rename">Relação Nacional de Medicamentos
                                Essenciais (Rename)</a></li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">É possível <a href="#filtrar">filtrar</a></li>
                        <li class="m-0 list-group-item">É possível acessar <a href="#bula">bula</a> do <a href="#medicamento">medicamento</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>

# Letra M

<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div id="medicamento" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Medicamento</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text"> Noções </h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item ">Produto farmacêutico, tecnicamente obtido ou elaborado, com
                            finalidade profilática, curativa, paliativa ou para fins de <a
                                href="#diagnostico">diagnóstico</a> </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Receitado à um <a href="#paciente">paciente</a></li>
                        <li class="m-0 list-group-item">Recuperável na aplicação, caso conste no <a href="#rename">RENAME</a></li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="col-sm-6">
            <div id="medico" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Médico</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Profissional da <a href="#usuario-saude">área da saúde</a> </li>
                        <li class="m-0 list-group-item">Responsável por receitar <a href="#medicamento">medicamentos</a> </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">
                            Deve ser <a href="#notificar-usuario"></a> notificado de novas <a href="#adicionar-medicamento">adições de medicamentos</a>
                            ou <a href="#modificar-bula">modificações na bula</a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
    <br>    
    <div class="row">
        <div class="col-sm-6">
            <div id="modificar-bula"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Modificar bula</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Atualização da bula pelos órgãos públicos responsáveis</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Novas características</li>
                        <li class="m-0 list-group-item">Gera <a href="#lista-medicamentos">notificação</a> aos usuários do sistema</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>
<br>

# Letra P

<div class="container">
    <div id="paciente" class="row">
        <div class="col-sm-6">
            <div id="paciente"class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Paciente</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Interage com o <a href="#medico">médico</a></li>
                        <li class="m-0 list-group-item">Possível <a href="#usuario-leigo">usuário leigo</a></li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Recebe <a href="#diagnostico"></a> diagnóstico</li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="col-sm-6">
            <div id="pdf" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">PDF</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Formato de arquivo para representar documentos independente de plataforma</li>
                        <li class="m-0 list-group-item">Contém <a href="#bula-paciente">bula para o paciente</a> ou <a href="#bula-profissional-saude">bula para o profissional de saúde</a> </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">É possível <a href="#compartilhar"></a> compartilhar PDF</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>

# Letra R

<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div id="rename" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Rename</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text"> Noções </h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item ">
                            Apresenta os <a href="#medicamento">medicamentos</a> oferecidos em todos os níveis de atenção e nas linhas de cuidado do 
                            <a href="#sus">SUS</a>
                        </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Forma a <a href="#lista-medicamentos">lista de medicamentos</a> </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>

# Letra S

<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div id="sus" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">SUS</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text"> Noções </h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item ">Sistema Único de Saúde. um dos maiores e mais complexos sistemas de saúde pública do mundo, garantindo acesso integral, universal e gratuito para toda a população</li>
                        <li class="m-0 list-group-item ">Mantenedor do aplicativo</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Alimenta o <a href="#rename">Rename</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>

# Letra T

<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div id="tratamento" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Tratamento</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text"> Noções </h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item ">
                            Resultado da interação entre <a href="#paciente">paciente</a> e <a href="#medico">médico</a> quando há 
                            <a href="#diagnostico">diagnóstico</a> de alguma doença tratável
                        </li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Possível receita de <a href="#medicamento">medicamentos</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

<br>

# Letra U

<div class="container">
    <div class="row">
        <div class="col-sm-6">
            <div id="usuario-saude" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Usuário da Saúde</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text"> Noções </h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário com conhecimento técnico</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Acessa <a href="#bula-profissional-saude">bula para profissionais de saúde</a> </li>
                    </ul>
                </div>
            </div>
        </div>
        <div class="col-sm-6">
            <div id="usuario-leigo" class="card">
                <div class="card-header p-1 bg-primary">
                    <h4 class="card-title text-white text-center m-1 font-weight-bold">Usuário Leigo</h5>
                </div>
                <div class="card-body p-2">
                    <h5 class="card-text">Noções</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Usuário que não possui conhecimento técnico</li>
                    </ul>
                </div>
                <div class="card-footer p-2">
                    <h5 class="card-text">Impacto</h5>
                    <ul class="m-0 list-group">
                        <li class="m-0 list-group-item">Acessa <a href="#bula-paciente">bula para pacientes e leigos </a> </li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>

## Referências bibliográficas

> CONSTRUÇÃO do léxico de aplicações. Proceedings of the International Joint Conference IBERAMIA/SBIA/SBRN 2006 : 4th Workshop in Information and Human Language Technology, Ribeirão Preto, Brazil, 23 out. 2006. CD-ROM.

> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/1668162/mod_resource/content/1/Aula%2010.pdf). Acesso em: 04 de março de 2022.

> RENAME. [S. l.], 9 mar. 2021. Disponível em: https://www.gov.br/saude/pt-br/assuntos/assistencia-farmaceutica-no-sus/rename. Acesso em: 4 mar. 2022.

> SISTEMA Único de Saúde (SUS): estrutura, princípios e como funciona. [S. l.], 24 nov. 2020. Disponível em: https://www.gov.br/saude/pt-br/assuntos/saude-de-a-a-z/s/sus-estrutura-principios-e-como-funciona. Acesso em: 4 mar. 2022.

> ANVISA. Perguntas e respostas sobre bulas. [S. l.], 1 mar. 2022. Disponível em: http://antigo.anvisa.gov.br/perguntas-e-respostas-sobre-bulas. Acesso em: 5 mar. 2022.

> IDEC - INSTITUTO BRASILEIRO DE DEFESA DO CONSUMIDOR. O que é um medicamento?. [S. l.], 4 maio 2011. Disponível em: https://idec.org.br/consultas/dicas-e-direitos/o-que-e-um-medicamento. Acesso em: 4 mar. 2022.

## Histórico de versões

Versão|Data|Alteração|Responsável|Revisão|
:-:|:-:|:-:|:-:|:-:|
0.0.1|02/03/22|Criação|Adrian|Fernando|
0.0.2|03/03/22|Adição de Léxicos|Adrian|Fernando|
0.0.3|05/03/22|Finalização dos Léxicos|Adrian|Fernando|
0.0.4|06/03/22|Introdução e metodologia|Adrian|Fernando|
0.0.5|06/03/22|Referências|Adrian|Fernando|
0.0.6|09/03/22|Correção das tags de fechamento|Thalisson|---|
