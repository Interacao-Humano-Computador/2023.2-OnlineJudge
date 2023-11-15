# Verificação dos Cenários

## Introdução

Após realizado o [planejamento geral de como serão realizadas as verificações da etapa 2](https://interacao-humano-computador.github.io/2023.2-OnlineJudge/verificacao/grupo_8/etapa_2/planejamento-verificacao/), neste artefato será produzido de fato a Verificação do artefato Cenários.

Dessa forma, inicialmente serão apresentados os objetivos dessa verificação, a metodologia utilizada para sua realização, os responsáveis por realizá-la e as respostas dos checklists apresentados no planejamento da etapa 2. Além disso, será desenvolvida uma análise e posterior levantamento dos problemas identificados após o respectivo checklist. Sendo assim, a partir das principais incoerências encontradas, será possível trazer sugestões e avaliar a necessidade de retrabalho.

## Objetivo

O objetivo deste documento é relatar os resultados das verificações realizadas no que tange o artefato [Cenários](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/analise-de-requisitos/cenarios) da Etapa 2 do [Grupo 8](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/).

## Metodologia

Os resultados da análise deste artefato foram obtidos através da análise dos checklists de verificação preparados na página de planejamento. Dessa forma, o avaliador irá verificar o respectivo artefato do grupo e responder às questões apresentadas nos checklists, utilizando as opções **"Sim", "Não" ou "Incompleto"**, além de também poder registrar comentários em cada questão analisada para detalhar alguma observação pertinente.

## Participantes envolvidos

Conforme explicitado no tópico "Cronograma" do Planejamento da Verificação da Etapa 2, o participante do Grupo 7 responsável por essa verificação foi: [Ester Lino](https://github.com/esteerlino).

## Sumário Dos Dados - Checklists

A Tabela 1 apresenta o Checklist Geral com os dados obtidos a partir da verificação de aspectos gerais que os artefatos devem seguir.

<center>

_Tabela 1_ - Checklist para os Itens Gerais.

|  ID  |  Descrição  |  Avaliação  |  Observações  |
|  --- | ----------- | ----------- | ------------- |
| 1   | O artefato possui introdução? |  SIM  |   |
| 2   | O artefato possui uma bibliografia/referência bibliográfica? | SIM |   |
| 3   | O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores padronizado? | INCOMPLETO |  As versões desse artefato não possuem revisor.  |
| 4   | Todas as tabelas e imagens são chamadas no texto, possuem legenda e fonte? | SIM |    |
| 5   | Todos os textos estão na norma padrão? | SIM |   |
| 6   | Os vídeos produzidos estão na categoria "não listado" no youtube?  |  -  |  O artefato não necessita de vídeos |

Fonte: [Ester Lino](https://github.com/esteerlino), 2023.

</center>

Já a Tabela 2 apresenta o checklist referente aos itens exigidos para o Perfil de Usuário.

<center>

_Tabela 2_ - Checklist para os Cenários

| ID  | Questão                                                                                                                | Resposta | Comentário |
| :-: | :--------------------------------------------------------------------------------------------------------------------- | :------: | :--------: |
|  1  | Existe o artefato Cenários? |     SIM     |            |
|  2  | Os Cenários possuem um título? |     SIM     |            |
|  3  | Os Cenários possuem atores? |     INCOMPLETO     |      Os atores definidos são genéricos.      |
|  4  | Esses atores são as Personas definidas no projeto? |     NÃO     |      Os atores não são as personas.      |
|  5  | Os cenários possuem ambiente ou contexto? |     SIM     |            |
|  6  | Os Cenários possuem objetivo? |     SIM     |            |
|  7  | Os Cenários possuem tarefas? |     SIM     |            |
|  8  | Os Cenários possuem as ações dos atores? |     SIM     |            |
|  9  | Os Cenários possuem os requisitos? |      SIM    |            |
| 10  | Os Cenários possuem a avaliação do ator sobre o problema apresentado? |     NÃO     |            |

Fonte: [Ester Lino](https://github.com/esteerlino), 2023.

</center>

## Problemas encontrados

A partir do preenchimento da tabela 1 e 2, a seguir serão realizadas as considerações acerca dos itens mencionados com "NÃO" ou "INCOMPLETO".

### ID 3 (checklist Geral): O artefato possui um histórico de versões com o id e descrição das versões, data, autores e revisores padronizado?

É possível observar que no histórico de versões do artefato [Cenários](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/analise-de-requisitos/cenarios), as versões não possuem um revisor responsável por verificar o texto.

### ID 3 (checklist Cenários): Os Cenários possuem atores?

O artefato [Cenários](https://interacao-humano-computador.github.io/2023.2-SEI-GDF/#/analise-de-requisitos/cenarios) possui atores para cada cenário. No entanto, esses atores são genéricos e identificados como "um advogado" e "um servidor público". Falta deixar explício quem poderia estar realizando as tarefas de cada cenário.

### ID 4 (checklist Cenários):  Esses atores são as Personas definidas no projeto?

Os atores escolhidos para cada cenário não são baseados nas personas. Isso pode ter ocorrido em parte pela ausência do artefato Personas no projeto em questão. Por esse motivo, é preciso desenvolver as personas, as quais podem ser utilizadas como atores nos cenários construídos pela equipe.

### ID 10 (checklist Cenários):  Os Cenários possuem a avaliação do ator sobre o problema apresentado?

Nos Cenários construídos não é possível afirmar como o ator avalia o problema apresentado e não possui um feedback ao final da execução da tarefa.

## Síntese dos dados encontrados

Dessa forma, a partir das respostas coletas nos checklists acima foi possível sintetizar dados encontrados em formato de gráfico, conforme pode ser visto na Figura 1.

<center>Figura 1 - Gráfico com resultado dos Checklists Geral e Cenários.

![](/../../assets/images/verificacao-cenarios.png)<br>
<b>Fonte:</b> <a href="https://github.com/esteerlino">Ester Lino</a>, 2023.</a></center></center>

## Sugestões de Correções

Por fim, a partir das informações coletas, apresentadas e analisadas acima, sugere-se realizar as seguintes correções:

- Corrigir a tabela de versões;
- Identificar o atores. Se possível, utilizar as personas definidas;
- Adicionar a avaliação do ator sobre cada tarefa de cada cenário, assim como, o feedback.

## Retrabalho

Para a realização do retrabalho é sugerido que os próprios autores do artefato verificado realizem a correção dos problemas apresentados seguindo a lista de sugestão apresentada no tópico anterior.

Se necessário, outros membros do grupo 8 podem realizar as correções propostas, porém, deve-se informar a mudança realizada na Tabela 3 pois selecionou-se exatamente o responsável por essa página de acordo com a tabela do Histórico de Versões.

O responsável do grupo 7 por essa verificação irá realizar uma revisão das correções feitas, verificando se as correções foram executadas com exatidão. Assim que todas as alterações forem implementadas, deve-se alterar o campo "Status" da Tabela 3 apresentada a seguir de "Em análise" para "Finalizado".

<center>

**Tabela 3** - Cronograma de Retrabalho.

| Data de Correção | Descrição                          |                   Responsável(eis)                   |                   Revisor(es)                    |   Status   |
| ---------------- | :--------------------------------- | :--------------------------------------------------: | :----------------------------------------------: | :--------: |
| 17/11/2023       | Realizar os ajustes da verificação dos Cenários | [Felipe de Sousa](https://github.com/fsousac) | [Ester Lino](https://github.com/esteerlino) | Em análise |

Fonte: [Ester Lino](https://github.com/esteerlino), 2023.

</center>

## Bibliografia

> <a id="REF1" href="#anchor_1">1.</a> BARBOSA, S. D. J.; SILVA, B. S. Interação Humano-Computador. Rio de Janeiro: Elsevier, 2011.

## Histórico de Versões

| Versão | Data       | Descrição                            | Autor(es)                                        | Revisor(es)                                     |
| ------ | ---------- | ------------------------------------ | ------------------------------------------------ | ----------------------------------------------- |
| 1.0  | 15/11/2023 | Criação da página Verificação dos Cenários| [Ester Lino](https://github.com/esteerlino) | [Eric Camargo](https://github.com/ericcs10) |
