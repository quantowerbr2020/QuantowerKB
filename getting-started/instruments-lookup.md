---
description: >-
  Symbols lookup manager allowing to search and select any available symbol from
  active connections
---

# Buscando os ativos por símbolos

Gerenciador de pesquisa de símbolos - é uma tela especial, permitindo pesquisar e selecionar qualquer símbolo disponível nas conexões ativas. Existem vários painéis no terminal Quantower, que exigem a configuração de um parâmetro Symbol \(Watchlist, Chart, Symbol info etc.\). Dependendo dos requisitos, a pesquisa de símbolos pode permitir a seleção de um ou vários símbolos.

Sempre que você se conectar com êxito a alguma integração, você obterá uma lista de seus símbolos na tela do Gerenciador de pesquisa de símbolos. Como o Quantower permite uma conexão de múltiplas integrações, você pode ter vários símbolos semelhantes com os dados, que podem variar um pouco. Isso é normal porque fornecedores diferentes podem nos fornecer dados de cotações diferentes.

## Campo de pesquisa

A tela de pesquisa de símbolos geralmente é chamada a partir de um campo de pesquisa. Este campo consiste em duas partes que permitem abrir a tela de pesquisa:

* Nome do símbolo \(com nome da conexão\)
* Ícone "Pesquisa" na forma de três pontos verticais

![Campo de pesquisa](../.gitbook/assets/lookupfield.png)

Se você clicar no nome do símbolo, verá que a tela Pesquisa será exibida e os símbolos inseridos por você serão aplicados como filtro na lista Símbolos.

Se você clicar no ícone "**Pesquisa**", você verá a tela Pesquisa exibida sem nenhuma filtragem aplicada à lista de símbolos.

![Symbol Lookup screen](../.gitbook/assets/symbol-lookup-screen.png)

De qualquer forma, você terá a tela Pesquisa pronta para a seleção de símbolos. A tela de pesquisa consiste em três elementos::

* Barra de ferramentas com campo de pesquisa e filtro
* A lista de conexões e seus símbolos
* Seção de rodapé

Se você quiser fechá-lo, clique fora dele.

## Pesquisa e filtragem

Geralmente, cada conexão fornece uma lista numerosa de símbolos de negociação para você escolher. Se você souber o nome, poderá começar a digitá-lo no "**campo de pesquisa**" e a lista abaixo será filtrada instantaneamente para os itens que contêm a frase inserida.

![Symbol lookup filtering](../.gitbook/assets/lookupfiltered.png)

A propósito, você pode aplicar uma filtragem mais geral à lista; basta clicar no ícone "**Filtro**" no lado direito do campo de pesquisa e você verá o segundo nível de filtragem de símbolos..

![General filtering of trading Symbols](../.gitbook/assets/lookupfilter2.png)

Aqui você poderá filtrar a lista por três parâmetros::

* Conexão \(conexões atualmente ativas\)
* Tipo de símbolo \(FOREX, CFD, Opções etc.\)
* Exchange \(Off-Exchange, NYSE, NASDAQ etc.\)

Depois de selecionar alguns itens entre os parâmetros de filtragem, a lista é filtrada apenas para os valores selecionados.

{% hint style="warning" %}
Seja cuidadoso. Enquanto o campo de pesquisa é redefinido a cada tela de pesquisa, os filtros de segundo nível permanecem como foram configurados da última vez. Portanto, se você não encontrar o tipo de símbolo necessário, verifique se esse tipo está ativado.
{% endhint %}

## Lista de símbolos

A lista de símbolos é resultado da filtragem na tela Pesquisa. Aqui você pode ver a árvore aninhada de símbolos, agrupada na seguinte ordem:

* Connection
* Exchange
* Type
* Subtypes

Os tipos de símbolo são marcados com ícones adicionais para ajudar a identificar o necessário mais rapidamente. A linha do item Symbol consiste em Nome e descrição..

Para selecionar o símbolo - clique nele; Para aplicar o símbolo ao painel necessário, basta clicar duas vezes nele. Esta ação fecha a tela de pesquisa

## Seleção de vários símbolos

Em alguns casos, quando o painel pode aceitar mais de um item de símbolo da pesquisa \(como a Watchlist\), você pode selecionar vários itens mantendo pressionada a tecla "Ctrl" e clicando na lista. Quando estiver pronto para aplicar vários itens - pressione o "ícone de círculo azul" no canto inferior direito da lista. Você também pode selecionar qualquer item de nível de categoria para aplicar todo o seu conteúdo ao painel necessário.

![Multiple Symbols select](../.gitbook/assets/lookupmultiple.png)

## List footer

Para ajudá-lo a lidar com as grandes listas de símbolos, há uma barra de ferramentas de rodapé com um conjunto de ações em massa. Permite::

* Recolher todos os nós
* Expandir nós principais \(nós de nível superior, geralmente Conexões\)
* Expandir nós filhos de primeiro nível

![Managing of multiple nodes in the Lookup Screen](../.gitbook/assets/collapsing.gif)

As outras informações úteis são colocadas no lado direito da barra de ferramentas do rodapé - os itens contam. Pode mostrar a quantidade total de símbolos disponíveis \(após a aplicação da filtragem\) e o valor 3/235 \(3 de 235\), indicando que você selecionou vários itens entre os disponíveis.

