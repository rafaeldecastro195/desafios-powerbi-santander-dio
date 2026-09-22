# Seja bem vindo(a) ao repositório do desafio do curso 4 do módulo 2!

Nesta documentação, será explicado brevemente sobre o que foi visto no curso, sobre a proposta do desafio e a análise dos dashboards.

## Acesso ao dashboard:
---

Acesso [aqui]() o link para o dashboard no Power Bi Service.

## Sobre o curso:
---

No curso 4 (Primeiros Passos com Power BI) foram estudados conceitos básicos de criação de Dashboards com o Power BI.

Para isso, foi utilizado o Dataset de Diabetes das mulheres índigenas de etnia Pima, para exercícios introdutórios, o dataset de amostra de dados financeiros do próprio Power BI.

Utilizou-se um pouco do PowerQuery, mas o foco foi a *construção básica* de dashboards.

## Sobre o desafio:
---

O desafio utiliza o dataset **Financial Sample** do Power BI e foi dividido em 3 relatórios:

### 1. Criação e análise do "Relatório de Vendas considerando Produtos e Segmento"

![Relatório 1]('.../dashboard/desafio_mod2_curso4_pg1')

Este relatório mostra em três gráficos diferentes as relações de vendas por produto e segmentos.

- O primeiro gráfico apresentado é um gráfico de setor (pizza). Nele, é possível perceber rapidamente qual(is) produtos são mais vendidos nesta amostra de dados, tanto pelo valor total expresso, percentual em relação ao todo, quanto setor, vistos no mesmo gráfico. Dessa forma, os mais vendidos, em ordem decrescente são:
    1. Paseo (27.8%)
    2. VTT (17.28%)
    3. Velo (15.37%)
    4. Amarilla (14.95%)
    5. Montana (12.96%)
    6. Carretera (11.64%)

- O segundo gráfico, é um gráfico de área que mostra o valor médio de venda dos produtos em ordem decrescente. Ele mostra que não necessariamente, ter valor médio menor, é sinônimo de vender mais. Paseo tem sim o menor valor médio e é o mais vendido, entre os produtos da amostra, mas VTT é o segundo mais vendido e possui o maior valor médio. Velo, terceiro mais vendido possui um valor intemediário e Carretera, segundo menor valor médio, é o menos vendido.

- O terceiro gráfico é de colunas clusterizado, que apresenta a evolução de vendas por segmento, entre 09/2013 e 12/2014. É possível ver, claramente que  os segmentos que mais vendem produtos, nesse espaço de tempo são Government e Small Business, sendo que o primeiro ultrapassa o segundo em 10 meses e o segundo ultrapassa o primeiro em 6. O segmento de Enterprise está sempre intermediário e Channel Partners e Midmarket são, visivelmente os menos representativos em todo o período.

O dashboard conta com segmentação de dados, que permite que sejam visualizados anos e meses em separado.

### 2. Criação e análise do "Relatório de Vendas considerando Países e Lucro"

Este relatório mostra as relações entre vendas, lucro e páises em 3 gráficos e 2 cartões.

![Relatório 2]('.../dashboard/desafio_mod2_curso4_pg2')

- Primeiramente, os cartões mostram valores absolutos: o primeiro mostra o valor total de vendas (118.73 milhões)   entre todos os países, e o segundo, o valor de unidades vendidas (1 milhão de unidades).

- A seguir, há um gráfico de setor, que mostra o lucro de cada país da amostra:
    1. França (22.38% do lucro total)
    2. Alemanha (21.79%)
    3. Canadá (20.89%)
    4. EUA (17.73%)
    5. México (17.21%)

- Em seguida, o gráfico de colunas representa a quantidade de lucro por mês. A alta de lucro costumou ser ao final do ano. O mês de outubro foi muito lucrativo tanto em 2013 quanto 2014. O mês que mais rendeu lucro na amostra foi 12/2014. Paralelamente, 06/2014 também foi significativamente lucrativo, mesmo estando na metade do ano.

- Por último, o gráfico de barras mostra o total de vendas por país. A ordem decrescente de vendas é:
    1. EUA
    2. Canadá
    3. França
    4. Alemanha
    5. México.
Este gráfico mostra que uma maior quantidade de vendas não garante um maior lucro: EUA foi o que mais vendeu, mas o segundo que menos lucrou; França foi quem mais lucrou e terceira que menos vendeu; a Alemanha foi a que segunda que menos vendeu e foi a segunda que mais lucrou. Mesmo que as diferenças de vendas e lucro desses países sejam pequenas, é possível concluir que indicadores de vendas e lucro são muito diferentes e podem ter uma correlação menos linear do que se pode pensar no senso comum.

### 3. Criação e análise do relatório "Distribuição de Lucro, Vendas e Unidades Vendidas por País e Segmento"

Este relatório é mais simples e visual.

![Relatório 3]('.../dashboard/desafio_mod2_curso4_pg3')

- O primeiro gráfico é de setor, mostrando o lucro por segmento. É muito claro que o setor de Small Business e, principalmente, Government foram muito mais lucrativos que os demais:
    1. Government (65.04%)
    2. Small Business (23.66%)
    3. Channel Partners (7.52%)
    4. Midmarket (3.77%)
    5. Enterprise (não aparece no gráfico por seu lucro ser muito pouco representativo)
Ainda que tenha se concluído que um maior número de vendas não necessariamente leva a um maior lucro, neste percebe-se que os dois segmentos de maior lucro, também são de maior venda, como visto no gráfico de coluna clusterizada do primeiro relatório.

- Os dois gráficos de mapa a seguir, são muito parecidos: o primeiro expressa total de vendas e unidades vendidas por país e o segundo, o total de lucro por país. Visualizando ambos, é possível perceber que as relações entre vendas, unidades vendidas e lucro, entre os países possa ter uma proporcionalidade mais clara, uma vez que os tamanhos não diferem muito de país pra país.

*Nota: optei por utilizar os gráficos de mapa e não Azure mapas, mesmo que o escolhido este em vias de ser descontinuado, pois este foi utilizado no curso*

Muito obrigado por ter visitado o repositório!
