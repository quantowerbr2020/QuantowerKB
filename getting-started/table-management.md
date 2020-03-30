---
description: >-
  Saiba como adicionar ou remover colunas da tabela, classificar e filtrar
  dados, definir alertas e ações
---

# Informações organizadas

## Painéis de dados

Os painéis da dados são representados como uma classe separada - todos eles têm pelo menos 99% de funcionalidade com base na visualização da tabela. Usamos o componente de tabela comum para todos esses painéis, para que o comportamento e os recursos sejam basicamente os mesmos.

![Table panels example](../.gitbook/assets/tablepanels.png)

Alguns painéis de dados possuem uma barra de ferramentas especial que pode ser usada para filtragem em massa ou ações rápidas. Outros painéis de tabela não podem ter cabeçalhos de coluna porque não precisam realmente entender os dados; portanto, foram ocultados para economizar espaço; isso desativa a capacidade de filtrar os dados das colunas nesses painéis.

Os dados nos painéis da tabela são organizados em linhas e colunas, onde os parâmetros de cada item \(linha\) são exibidos em colunas. Nem todas as colunas disponíveis são exibidas por padrão em cada painel da tabela. Selecionamos os mais populares e vitais por painel e modificamos as colunas definidas conforme desejado.

![Modify table columns set as you like](../.gitbook/assets/tablecolumns.png)

Clique com o botão direito do mouse em qualquer cabeçalho de coluna para ver o menu de contexto "Conjunto de colunas". Em seguida, clique em qualquer item deste menu para mudar a visibilidade da coluna. Você pode desativar até 1 coluna no mínimo; a última coluna visível não estará disponível para ocultar.

Outros recursos úteis do gerenciamento de colunas estão classificando e redimensionando. Cada coluna pode ser arrastada pelo cabeçalho entre outras colunas dentro da tabela para definir a sequência necessária. Você também pode arrastar as bordas verticais entre duas colunas para redimensioná-las..

## Filtering

The set of rows in the table can be filtered by some data value in their column. There are two ways to apply the filtering:

* Quick table filter
* Advanced table filter

{% hint style="success" %}
Quick table filter is just another point of access to advanced filtering option, allowing to apply simple filters in several clicks.
{% endhint %}

Quick table filter can be accessed by clicking the “_**Filter**_” icon in any table column’s header.

![Quick filtering per column](../.gitbook/assets/tablequickfilter.png)

Dependendo do tipo de dados em uma coluna, o filtro Rápido fornecerá o formulário correspondente para entrada; atualmente, os filtros "String", "Date / time" e "Number" são suportados. Depois de selecionar alguma opção - as linhas da tabela serão filtradas para aquelas, contendo o valor selecionado. O filtro rápido pode ser cancelado pressionando a opção "Cancelar filtragem".

## Advanced table filter

Caso deseje aplicar uma filtragem mais complexa \(filtragem múltipla\), você pode abrir um filtro avançado no menu de contexto do painel, opção "Ações de configuração". Essa tela possui duas guias no lado esquerdo, onde a primeira é um filtro Avançado.

{% hint style="success" %}
Você verá seus filtros aqui se tiver aplicado alguns anteriormente no modo Rápido.
{% endhint %}

![Table advanced filter screen](../.gitbook/assets/tableadvancedfiltering.png)

Essa tela permite ativar / desativar a filtragem, bem como configurar as condições de filtragem. Essas condições são configuradas como::

$$
IF (condition1 AND condition2 ...) OR (conditionN...) …
$$

Você pode configurar quantas condições desejar. Devido à possível lógica complexa de filtragem, você deve aplicar as alterações depois de concluir a configuração do filtro..

{% hint style="info" %}
Observe que nem todos os aplicados através das condições avançadas de filtro podem ser acessados no filtro Rápido..
{% endhint %}

## Ordenação

Cada tabela pode ser classificada pelo valor da coluna. Para classificar a tabela, clique no cabeçalho da coluna; você verá um ícone "Classificação". O próximo clique neste cabeçalho reverterá a classificação por esta coluna. Você pode classificar sua tabela apenas por uma coluna simultaneamente.

## Agrupamento

Se você deseja organizar suas linhas com mais precisão, use o recurso "Agrupamento de linhas". Permite separar todos os itens da tabela em grupos, feitos a partir de dados de alguma coluna. Atualmente, apenas as colunas de dados "String" são suportadas para agrupamento.

![Table grouped by &#x201C;Side&#x201D; value](../.gitbook/assets/tablegrouping.png)

Para aplicar o agrupamento, basta clicar com o botão direito do mouse no corpo da tabela e encontrar a opção "Agrupar por"; o segundo nível do menu de contexto conterá todas as colunas disponíveis que podem ser agrupadas. Você pode agrupar por apenas uma coluna. Para cancelar o agrupamento - siga as etapas anteriores e desmarque a coluna.

## Table actions

Esse recurso permite configurar determinado comportamento em algumas alterações de dados na tabela. Atualmente, as tabelas Quantower suportam quatro tipos de ações::

* Mostrar mensagem
* Tocar som
* Cores da coluna row
* Cores do campo

![Table actions per any Quantower table-based panel](../.gitbook/assets/tableactions.png)

A funcionalidade de ações da tabela pode ser encontrada na opção do menu de contexto do painel "Ações de configuração" e, uma vez iniciada, abre uma "tela de ações", na qual você pode gerenciar suas ações. O processo de criação da ação não é complicado.

1. Create an Action item 
2. Set conditions \(“OR” & “AND”\) 
3. Set tasks \(Show message, Play sound, Color row, Color cell\) 
4. Save Action 
5. Enable Action

## Table actions conditions

Conditions setup for Table Actions is similar to [Filtering conditions, mentioned earlier](table-management.md#advanced-table-filter).

## Table actions tasks

Once some condition is met, action will execute the corresponding tasks. Each task will be executed as many times, as the condition was met.

| **Show message** | Displays a popup box with the user-specified message |
| :--- | :--- |
| **Play sound** | Plays some user selected sound file |
| **Color row** | Changes the styling of the whole row, where the condition was met. Allows changing the background and/or text colors. |
| **Color cell** | Changes the styling of the specified cell\(s\) of the row, where the condition was met. Allows changing the background and/or text colors. |

{% hint style="warning" %}
Be careful with the frequently occurring conditions. Some may be met several times per second, so tasks like “_Play sound_” can become disturbing. The “_Show message_” task, fired several times, will be shown as one message box.
{% endhint %}

