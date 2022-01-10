# grafo_de_bebidas
Grafo de relacionamento de venda entre bebidas

## Dados
Os dados utilizados são dados fictícios de venda de bebbidas alcoólicas. O dataset contém 2 variáveis: transação (que é a transação de cada compra) e compras (contendo as todas as bebidas compradas em cada transação).

## Objetivo 
O objetivo é descobrir o relacionamento entre as bebidas e, assim, verificar qual bebida x é mais vendida em conjunto com a bebida y. Dessa forma, o estelecimento consegue ter uma estratégia de vendas mais efetiva tanto na venda de combos de bebidas, quanto na locação das mercadorias no espaço físico da loja.

## Regra de associação
As regras de associação são uma tarefa da Mineração de Dados que possibilita a identificação de padrões intratransações em uma base de dados, calculando o quanto a presença de um conjunto de atributos nos registros implica na de outro conjunto distinto de atributos. Essa regra possui fator de suporte e fator de confiança como índices de grau de veracidade.

Sendo Antecedente (Y) → Consequente (W):


O suporte é caracterizado como o número de transações incluindo todos os elementos na posição antecedente e consequente da regra.
Suporte (Y → W) = (frequência de Y e W) / (total de T)



A confiança de uma regra é a probabilidade condicional de que uma transação contenha Y, dado que contém W. 
Confiança (Y → W) = suporte (Y U W) / suporte (Y)



Por sua vez, o Lift, outro índice estatístico utilizado para definir o grau de interesse de uma regra de associação, indica quão mais frequente se torna W quando Y ocorre.
Lift (Y → W) = confiança (Y → W) / suporte (W)

## Grafo
O gráfico mostra a relação das bebidas (vértices), sendo que nas ligações (arestas) o peso é o grau de confiança entre as bebidas.

![image](https://user-images.githubusercontent.com/79197619/148706741-b0788551-4f6a-4da4-8038-c9c6e2249f72.png)

Nesse exemplo a vodka tem um grau de 0,5, ou seja, 50% de graud de confiança com a cerveja. Isso significa que a pessoa que compra vodka tem 50% de chance de levar cerveja também na mesma compra.
