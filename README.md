# insights_vendas_imoveis
O objetivo deste projeto é ajudar a empresa encontrar as melhores oportunidades de negócio no mercado de imóveis, visando maximizar seus lucros

A principal estratégia é comprar boas casas em ótimas localizações com preços baixos e depois revendê-las posteriormente à preços mais altos. Quanto maior a diferença entre a compra e a venda, maior o lucro da empresa e portanto maior sua receita.


Entretanto, as casas possuem muitos atributos que as tornam mais ou menos atrativas aos compradores e vendedores e a localização e o período do ano também podem influenciar os preços. Portanto, nessa análise, buscaremos responder as seguinte perguntas:


1.	Quais casas o CEO da House Rocket deveria comprar e por qual preço de compra?
2.	Uma vez a casa em posse da empresa, qual o melhor momento para vendê-las e qual seria o preço da venda?
3.	É possível criar um modelo para determinar o valor do imóvel a ser comprado ou vendido com base nas features dadas?



Link para o código no google colab:

https://colab.research.google.com/drive/1UhBuudCS7fvnb5IUFOa4TLcMv-JuPMGe#scrollTo=ZbjijtDN9mkt



**CONCLUSÃO**

**INSIGHTS OBTIDOS:**

*1. Condições das casas:* • A maioria das casas está em condições razoáveis e boas, enquanto há poucas casas em condições ruins e excelentes.

*2. Grades das casas:* • A maioria das casas possui uma classificação de grade média (7), com uma queda acentuada na quantidade de casas à medida que a classificação aumenta. Isso indica que a maioria das casas está em condições médias de construção e design, e há pouquíssimas casas com uma alta qualidade de construção e design.

*2. Renovação:* A maioria das casas não passou por renovação (yr_renovated), mas as que foram renovadas tendem a ter um valor de venda mais alto.

*3. Variação dos preços ao longo dos anos: 
• Os preços das casas mostram uma variação significativa entre as décadas de 1900 e 1961. A partir de 1961, os preços começam a aumentar, indicando uma valorização dos imóveis ao longo do tempo. Casas construídas em décadas mais recentes tendem a ter preços mais altos, indicando que o mercado está valorizando imóveis mais novos.

*4. Faixa de preço: A maioria dos imóveis vendidos se encontram na faixa de 250.000 a 500.000 dólares.

*5. Localização: Algumas áreas, como Beaux Arts Village, Clyde Hill, Hunts Point, Medina e Yarrow Point, possuem preços mais altos, indicando alto padrão e valorização. Áreas como Algona, Auburn, Burien, Des Moines e Seatac possuem preços relativamente mais baixos e acessíveis.

*6. Sazonalidade: Não há tanta oscilação na quantidade de vendas mensal, mas há uma leve diminuição nas vendas entre novembro e janeiro, voltando a aumentar a partir de fevereiro.

*7. Alta correlação com o preço:

*   Grade (avaliação): a nota de avaliação foi um fator importante para determinar o preço dos imóveis. Casas com uma classificação mais alta tendem a ter preços mais altos.

*   Quantidade de banheiros e tamanho das áreas: Características como o número de quartos, banheiros e espaço interior (sqft_living), área acima do nível do solo (sqft_above) e área interna das 15 casas mais próximas (sqft_living15) também influenciam positivamente o preço dos imóveis.

*   Localização: Embora a análise tenha indicado uma correlação baixa entre a localização (devido à incompatibilidade do tipo de dado com o cálculo de correlação), é amplamente reconhecido que a localização desempenha um papel fundamental na determinação dos preços imobiliários, pois diversos fatores, como proximidade de serviços, infraestrutura, comodidades, segurança e atrativos naturais, influenciam a demanda e, consequentemente, o valor das propriedades. É possível identificar isso no mapa geográfico que foi mostrado na análise. As áreas mais centrais possuem preços mais altos, quando comparadas às mais periféricas.

* 8. Pouca correlação com o preço:
A condição da casa (condition), beira-mar (waterfront), número de andares (floors) e a vista do imóvel (view) não possuem uma influência significativa no preço de venda. Casas com boas condições e vistas privilegiadas não apresentam um aumento expressivo no valor.

**RESPONDENDO ÀS PERGUNTAS DE NEGÓCIO

**Quais casas o CEO da House Rocket deveria comprar e por qual preço de compra?

De acordo com os dados, caso a empresa deseje investir na compra e venda de imóveis com preços mais altos, o ideal é investir nos que possuem melhor localização, maior área e melhor qualidade da construção e design.

**Uma vez a casa em posse da empresa, qual o melhor momento para vendê-las e qual seria o preço da venda?

O melhor momento para comprar é entre novembro e janeiro, e o melhor momento para vender é entre fevereiro e maio.

**A House Rocket deveria fazer uma reforma para aumentar o preço da venda? Quais seriam as sugestões de mudanças?

A decisão de fazer uma reforma deve ser baseada em uma análise cuidadosa dos custos em relação ao aumento esperado no preço. Sugestões de mudanças incluem melhorias na qualidade da construção e design, como atualização de acabamentos, renovação de banheiros e cozinha, e expansão da área interna, caso seja viável financeirament
