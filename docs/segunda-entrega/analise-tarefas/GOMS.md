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

## Procurar um problema

Nesta tarefa o objetivo do usuário é buscar um novo problema para solucionar dentro do site

- Goal 0: Acessar a aba **_Browse Problems_**
  - Operador 1: Hoaming
  - Operador 2: Click
  - Metodo 1: Mover o cursor do mouse para a aba **_Browse Problems_**
  - Método 2: Clicar na aba para abri-la
    - Goal 1: Navegar pelas pastas de problemas
      - Operador 1: Hoaming
      - Operador 2: Click
      - Metodo 1: Mover o cursor do mouse para a pasta alvo
      - Método 2: Clica na pasta para abri-la
    - Goal 2: Selecionar o problema alvo
      - Operador 1: Hoaming
      - Operador 2: Click
      - Metodo 1: Mover o cursor do mouse para o problema alvo
      - Método 2: Clicar no problema para abri-lo

<center><b>Fonte:</b> <a href="https://github.com/suzaneduarte">Suzane Duarte</a>, <a href="https://github.com/PabloGJBS">Pablo Guilherme</a></center>

# Bibliografia

> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

# Histórico de versão

| Versão |    Data    |            Descrição            |                                           Responsáveis                                            |                     Revisor                     |
| :----: | :--------: | :-----------------------------: | :-----------------------------------------------------------------------------------------------: | :---------------------------------------------: |
|  1.0   | 01/10/2023 | Introdução a Análise de Tarefas | [Suzane Duarte](https://github.com/suzaneduarte), [Pablo Guilherme](https://github.com/PabloGJBS) | [Kallyne Macedo](https://github.com/kalipassos) |
