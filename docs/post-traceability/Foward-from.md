## 1. Intrudução

Foward From é uma técnica de rastreabilidade que tem o objetivo de prover relacionamento entre os requisitos, arquitetura e implementação final. Especificamente, o 
Foward-from (para frente, a partir de) tem o objetivo de ligar os requisitos, artefatos de desenho e implementação.

## 2. Metodologia

Visto os artefatos construidos até agora, é possível contruir uma Matriz de Rastreabilidade para conectar os Requisitos, Épicos, Features, História de Usuário e
Funciolidade.
<br></br>
Como o MedSus não é um softfware de código aberto, não foi possível relacionar o código fontes aos requisitos.

## 3. Matriz de Rastreabilidade

**Legenda:**

* R: Requisito
* ST: Storytelling
* IR: Requisito de Introspecção


| ID | Requisito |
|----|-----------|
| R08 | O usuário deve ser capaz de alterar informações baseado no perfil de usuário (Profissional de saúde/Usuário comum). |
| ST19 | A aplicação deve disponibilizar o aumento (e redução) do tamanho da fonte das monografias. |
| IR3 | Acessar partes específicas da bula através de um índice. |
| R03 | O usuário deve ser capaz de favoritar medicamentos. |
| R12 | O usuário deve conseguir buscar palavras-chave no texto das informações. |
| R04 | O usuário deve ser capaz de filtrar por Grupo Anatômico Principal. |
| R05 | O usuário deve ser capaz de filtrar por anexo da Rename. |
| R06 | O usuário deve ser capaz de filtrar por controle especial. |
| R07 | O usuário deve ser capaz de filtrar por medicamentos que possuem genérico ou não. |
| ST17 | O app deve notificar os usuários acerca das atualizações da monografia dos medicamentos (inclusão, remoção e alteração). |
| ST08 | O app deve gerar arquivos para compartilhar com qualquer outra pessoa. |
| IR10 | Compartilhar informações por PDF. |

### 3.1. Especificações

**R08**

| R08                    | O usuário deve ser capaz de alterar informações baseado no perfil de usuário (Profissional de saúde/Usuário comum). |
| :--------------------: | :---------: |
| Épico                  | Visualização |
| Feature                | Alterar Perfil |
| História de Usuário    | [US01](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**ST19**

| ST19                   | A aplicação deve disponibilizar o aumento (e redução) do tamanho da fonte das monografias |
|:---------------------: | :-------: |
| Épico                  | Visualização |
| Feature                | Alterar tamanho da fonte |
| História de Usuário    | [US03](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**IR3**

| IR3                    |  Acessar partes específicas da bula através de um índice. |
| :--------------------: | :-------: |
| Épico                  | Visualização |
| Feature                | Apresentar índice |
| História de Usuário    | [US04](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**R03**

| R03                    | O usuário deve ser capaz de favoritar medicamentos. |
| :--------------------: | :-------: |
| Épico                  | Filtro |
| Feature                | Favoritar |
| História de Usuário    | [US05](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**R12**

| R12                    | O usuário deve conseguir buscar palavras-chave no texto das informações. |
| :--------------------: | :-------: |
| Épico                  | Filtro |
| Feature                | Filtrar por Palavras-chave |
| História de Usuário    | [US06](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**R04**

| R04                    | O usuário deve ser capaz de filtrar por Grupo Anatômico Principal. |
| :--------------------: | :-------: |
| Épico                  | Filtro |
| Feature                | Filtrar por Atributos do medicamento |
| História de Usuário    | [US07](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**R05**

| R05                    | O usuário deve ser capaz de filtrar por anexo da Rename. |
| :--------------------: | :-------: |
| Épico                  | Visualização |
| Feature                | Alterar Perfil |
| História de Usuário    | [US09](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**R06**

| R06                    | O usuário deve ser capaz de filtrar por controle especial. |
| :--------------------: | :-------: |
| Épico                  | Filtro |
| Feature                | Filtrar por Atributos do medicamento |
| História de Usuário    | [US10](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**R07**

| R07                    | O usuário deve ser capaz de filtrar por medicamentos que possuem genérico ou não. |
| :--------------------: | :-------: |
| Épico                  | Filtro |
| Feature                | Filtrar por Atributos do medicamento |
| História de Usuário    | [US11](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**ST17**

| ST17                   | O app deve notificar os usuários acerca das atualizações da monografia dos medicamentos (inclusão, remoção e alteração). |
| :--------------------: | :-------: |
| Épico                  | Notificação |
| Feature                | Notificar usuários |
| História de Usuário    | [US13](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**ST08**

| ST08                   | O app deve gerar arquivos para compartilhar com qualquer outra pessoa. |
| :--------------------: | :-------: |
| Épico                  | Compartilhar monografias |
| Feature                | Alterar Perfil |
| História de Usuário    | [US15](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

**IR10**

| IR10                   | Compartilhar informações por PDF. |
| :--------------------: | :-------: |
| Épico                  | Compartilhamento |
| Feature                | Compartilhar monografias |
| História de Usuário    | [US16](https://requisitos-de-software.github.io/2021.2-MedSUS/modeling/userstory/) |
| Funcionalidade         |  |

