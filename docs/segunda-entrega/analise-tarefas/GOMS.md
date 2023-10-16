# GOMS (Goals, Operators, Methods and Selection Rules)

# Introdução

A abordagem GOMS descreve como o usuário interage com o sistema, dividindo a interação em metas(Goals), operadores (operators), métodos(methods) e regras de seleção (selection rules).

A abordagem GOMS é recomendada a utilização do modelo GOMS para:

- **Comparação de Alternativas de desing:** é possivel utilizar o modelo em diferentes alternativas de desing e verificar qual oferece melhor eficiencia.

- **Avaliação de protótipos e simulação:** o modelo é util para verificar prototipos utilizando simulações a fim de economizar tempo e recursos no desenvolvimento.

- **Identificação de ineficiencias:** ao descrever as metas, operadores, métodos e regras é possivel identificar possiveis ineficiencias no sistema e descobrir áreas que precisam de melhora.

- **Mensurar o desempenho do usuário:** por setratar de um modelo que proporciona a análise de uma tarefa específica executada pelo usuário é possivel estimar quanto tempo o usuário levará para realizar a tarefa.

# Motivo da escolha

Decidimos pelo modelo GOMS pelo fato dele proporcionar a análise especifica da ação do usuário em determinada tarefa no site, proporcionando uma melhor visão do caminho que o usuário pode seguir para realizar a sua tarefa bem como os erros ou dificuldades que podem dificultar a realização da tarefa.

# Análise de tarefas

## Submeter problema

Nesta tarefa o objetivo do usuário é submeter um algoritimo para ser julgado

- Goal 0: Acessar a aba **_Quick Submit_**
  - Operador 1: Hoaming
  - Operador 2: Click
  - Método 1: Mover o cursor do mouse para a aba **_Quick Submit_**
  - Método 2: Clicar na aba para abri-la
    - Goal 1: Digitar o codigo do problema (Problem ID)
      - Operador 1: Hoaming
      - Operador 2: Click
      - Operador 3: Data Input
        - Método 1: Mover o cursor do mouse para o campo Problem ID
        - Método 2: Clicar no campo para selecioná-lo
        - Método 3: Digitar o Id do problema a ser submetido
    - Goal 2: Selecionar a linguagem de programação desejada
      - Operador 1: Hoaming
      - Operador 2: Click
        - Método 1: Mover o cursor do mouse para a linguagem desejada
        - Método 2: Clicar na bolinha de seleção para selecionar a linguagem
    - Goal 3: Enviar o seu código:
      - Goal 3.1: Copiar o codigo na área de texto:
        - Operador 1: Hoaming
        - Operador 2: Click
        - Operador 3: Data Input
          - Método 1: mover o cursor até a área de texto para colocar o codigo
          - Método 2: Clicar na área de texto para selecioná-la
          - Método 3: Digitar ou colar o codigo na área de texto
          - Método 4: Clicar no botão **Submit**
      - Goal 3.2: Escolher o arquivo que contém o codigo:
        - Operador 1: Hoaming
        - Operador 2: Click
          - Método 1: Mover o curso ate a área **Escolher arquivo**
          - Método 2: clicar no botão **Escolher arquivo**
          - Método 3: selecionar o arquivo desejado
          - Método 4: Clicar no botão **Submit**

<center><b>Fonte:</b> <a href="https://github.com/suzaneduarte">Suzane Duarte</a>, <a href="https://github.com/PabloGJBS">Pablo Guilherme</a></center>

## Procurar um problema

Nesta tarefa o objetivo do usuário é buscar um novo problema para solucionar dentro do site

- Goal 0: Acessar a aba **_Browse Problems_**
  - Operador 1: Hoaming
  - Operador 2: Click
  - Método 1: Mover o cursor do mouse para a aba **_Browse Problems_**
  - Método 2: Clicar na aba para abri-la
    - Goal 1: Navegar pelas pastas de problemas
      - Operador 1: Hoaming
      - Operador 2: Click
      - Método 1: Mover o cursor do mouse para a pasta alvo
      - Método 2: Clica na pasta para abri-la
    - Goal 2: Selecionar o problema alvo
      - Operador 1: Hoaming
      - Operador 2: Click
      - Método 1: Mover o cursor do mouse para o problema alvo
      - Método 2: Clicar no problema para abri-lo

<center><b>Fonte:</b> <a href="https://github.com/suzaneduarte">Suzane Duarte</a>, <a href="https://github.com/PabloGJBS">Pablo Guilherme</a></center>
<br><br>

## Visualizar minhas submissões

Nesta tarefa o objetivo é acessar a aba que permite ver todas as submissões.

- Goal 0: Acessar a aba **_My Submissions_**
  - Operador 1: Hoaming
  - Operador 2: Click
  - Método 1: Mover o cursor para aba de **_My Submissions_**
  - Método 2: Clicar na aba **_My Submissions_**
    Goal 1: Visualizar uma submissão especifica
    - Operador 1: Hoaming
    - Operador 2: Click
    - Método 1: Mover o cursor até a submissão especica
    - Método 2: Clicar na submissão desejada

<center><b>Fonte:</b> <a href="https://github.com/suzaneduarte">Suzane Duarte</a>, <a href="https://github.com/PabloGJBS">Pablo Guilherme</a>, <a href="https://github.com/henriqtorresl">Henrique Torres</a></center>
## Contatar colaboradores

Nesta tarefa o objetivo do usuário é contatar colaboradores do site

- Goal 0: Acessar a aba **_Contact Us_**
  - Operador 1: Hoaming
  - Operador 2: Click
  - Método 1: Mover o cursor do mouse para a aba **_Contact Us_**
  - Método 2: Clicar na aba para abri-la
    - Goal 1: Navegar pelos campos de inserção
      - Operador 1: Hoaming
      - Operador 2: Click
      - Método 1: Mover o cursor do mouse para o campo nome
      - Método 2: Inserir o nome
      - Método 3: Inserir email do colaborador desejado
      - Método 4: Inserir mensagem
    - Goal 2: Enviar
      - Operador 1: Hoaming
      - Operador 2: Click
      - Método 1: Mover o cursor do mouse para o botão **_Send_**
      - Método 2: Clicar no botão para enviar

<center><b>Fonte:</b> <a href="https://github.com/Ericcs10">Eric Camargo</a></center>

## Acessar o Contest System

Nesta tarefa o objetivo é acessar a aba de *Contest System*

- Goal 0: Acessar a aba **_Contest System_**
  - Operador 1: Hoaming
  - Operador 2: Click
  - Método 1: Mover o cursor do mouse para a aba **_Contest System_**
  - Método 2: Clicar na aba para abri-la
    - Goal 1: Acessar a aba **_Running contests_**
      - Operador 1: Hoaming
      - Operador 2: Click
      - Método 1: Mover o cursor do mouse para a aba **_Running contests_**
      - Método 2: Clicar na aba para abri-la
    - Goal 2: Acessar a aba **_Comming contests_**
      - Operador 1: Hoaming
      - Operador 2: Click
      - Método 1: Mover o cursor do mouse para a aba **_Comming contests_**
      - Método 2: Clicar na aba para abri-la
    - Goal 3: Acessar a aba **_Past Contests_**
      - Operador 1: Hoaming
      - Operador 2: Click
      - Método 1: Mover o cursor do mouse para a aba **_Past Contests_**
      - Método 2: Clicar na aba para abri-la
      - Goal 3.1: Acessar algum contest passado
        - Operador 1: Hoaming
        - Operador 2: Click
        - Método 1: Mover o cursor do mouse para o contest desejado
        - Método 2: Clicar no contest especifico para acessá-lo
    - Goal 4: Acessar a aba **_Contest Ranking_**
      - Operador 1: Hoaming
      - Operador 2: Click
      - Método 1: Mover o cursor do mouse para a aba **_Contest Ranking_**
      - Método 2: Clicar na aba para abri-la

<center><b>Fonte:</b> <a href="https://github.com/esteerlino">Ester Flores</a>, <a href="https://github.com/PabloGJBS">Pablo Guilherme</a></center>
<br><br>

## My account (edit user)

Nesta tarefa o objetivo do usuário é alterar as informações de sua conta

- Goal 0: Acessar a aba _My account_
  - Operador 1: Hoaming
  - Operador 2: Click
  - Método 1: Mover o cursor do mouse para a aba _My account_
  - Método 2: Clicar na aba para abri-la
  - Goal 1: acessar a aba de edição do perfil
    - Operador 1: Hoaming
    - Operador 2: Click
    - Método 1: Mover o cursor do mouse para o botão _Edit_
      - Goal 1.1: Selecionar _Update Your Image_
        - Operador 1: Hoaming
        - Operador 2: Click
        - Método 1: Mover o cursor do mouse para o botão _Update Your Image_
        - Goal 1.1.1: Enviar uma imagem do computador:
          - Operador 1: Hoaming
          - Operador 2: Click
          - Método 1: Mover o cursor do mouse para o botão _Escolher Arquivo_
          - Método 2: Selecionar o arquivo desejado
          - Método 3: Clicar no botão _Confirm choice_
        - Goal 1.1.2: Escolher um icone próprio do site
          - Operador 1: Hoaming
          - Operador 2: Click
          - Método 1: mover o cursor para a parte dos icones
          - Método 2: selecionar 1 icone que o site oferece
          - Método 3: Cliclar no botão _Confirm choice_
      - Goal 1.2: Selecionar _Update Your Profile_
        - Goal 1.2.1: Selecionar _Upload profile Image_
        - Operador 1: Hoaming
        - Operador 2: Click
        - Método 1: Mover o cursor do mouse para a opção _Upload profile Image_
        - Goal 1.2.1.1: Enviar uma imagem do computador:
          - Operador 1: Hoaming
          - Operador 2: Click
          - Método 1: Mover o cursor do mouse para o botão _Escolher Arquivo_
          - Método 2: Selecionar o arquivo desejado
          - Método 3: Clicar no botão _Update_
        - Goal 1.2.1.2: Escolher um icone próprio do site
          - Operador 1: Hoaming
          - Operador 2: Click
          - Método 1: mover o cursor para a opção _Select image from gallery_
          - Método 2: selecionar 1 icone que o site oferece
          - Método 3: Cliclar no botão _Update_
        - Goal 1.2.2: Alterar Contact Info
          - Operador 1: Hoaming
          - Operador 2: Click
          - Operador 3: Data Input
          - Método 1: Mover o cursor para o campo desejado
          - Método 2: clicar para selecionar o campo desejado
          - Método 3: Alterar os dados
          - Método 4: Clicar no botão update
        - Goal 1.2.3: Alterar Geocoding
          - Operador 1: Hoaming
          - Operador 2: Click
          - Operador 3: Data Input
          - Método 1: Mover o cursor para o campo desejado
          - Método 2: clicar para selecionar o campo desejado
          - Método 3: Alterar os dados
          - Método 4: Clicar no botão update

<center><b>Fonte:</b> <a href="https://github.com/luanatorress">Luana Torres</a>, <a href="https://github.com/PabloGJBS">Pablo Guilherme</a></center>
<br><br>


# Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

# Histórico de versão

| Versão |    Data    |                         Descrição                          |                                             Responsáveis                                             |                     Revisor                      |
| :----: | :--------: | :--------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :----------------------------------------------: |
|  1.0   | 01/10/2023 |              Introdução a Análise de Tarefas               |  [Suzane Duarte](https://github.com/suzaneduarte), [Pablo Guilherme](https://github.com/PabloGJBS)   | [Kallyne Macedo](https://github.com/kalipassos)  |
|  1.1   | 16/10/2023 |     Adicionando análise de tarefa Procurar um problema     |  [Suzane Duarte](https://github.com/suzaneduarte), [Pablo Guilherme](https://github.com/PabloGJBS)   | [Kallyne Macedo](https://github.com/kalipassos)  |
|  1.2   | 16/10/2023 | Adicionando análise de tarefa Visualizar minhas submissões | [Pablo Guilherme](https://github.com/PabloGJBS), [Henrique Torres](https://github.com/henriqtorresl) | [Suzane Duarte](https://github.com/suzaneduarte) |
|  1.3   | 16/10/2023 | Adicionando análise de tarefa acessar Contest System | [Pablo Guilherme](https://github.com/PabloGJBS), [Ester Lino](https://github.com/esteerlino) | [Suzane Duarte](https://github.com/suzaneduarte) |
|  1.4   | 16/10/2023 | Adicionando análise de tarefa acessar Contest System | [Pablo Guilherme](https://github.com/PabloGJBS), [Luana Torres](https://github.com/luanatorress) | [Suzane Duarte](https://github.com/suzaneduarte) |
