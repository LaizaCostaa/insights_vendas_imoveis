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

*1. Grades das casas:* A maioria das casas possui uma classificação de grade média (7), Com relação à construção e design.

*2. Renovação:* A maioria das casas não passou por renovação (yr_renovated), mas as que foram renovadas tendem a ter um valor de venda mais alto.

*3. Faixa de preço:* A maioria dos imóveis vendidos se encontram na faixa de 250.000 a 500.000 dólares.

*4. Localização:* Algumas áreas, como Beaux Arts Village, Clyde Hill, Hunts Point, Medina e Yarrow Point, possuem preços mais altos, indicando alto padrão e valorização. Áreas como Algona, Auburn, Burien, Des Moines e Seatac possuem preços relativamente mais baixos e acessíveis.

*5. Tendência:* Não há tanta oscilação na quantidade de vendas mensal, mas há uma leve diminuição nas vendas entre novembro e janeiro, voltando a aumentar a partir de fevereiro, com pico de vendas em abril.

*6. Alta correlação com o preço:*

*   Grade (avaliação):* Casas com uma classificação mais alta tendem a ter preços mais altos.

*   Área:* Características como o número de quartos, banheiros e espaço interior (sqft_living), área acima do nível do solo (sqft_above) e área interna das 15 casas mais próximas (sqft_living15) também influenciam positivamente o preço dos imóveis.

*   Localização:* Áreas mais centrais possuem preços mais altos.

*8. Pouca correlação com o preço:* A condição da casa (condition), beira-mar (waterfront), número de andares (floors) e a vista do imóvel (view) não possuem uma influência significativa no preço de venda.

**RESPONDENDO ÀS PERGUNTAS DE NEGÓCIO**

**Quais casas o CEO da House Rocket deveria comprar e por qual preço de compra?**

Como a estratégia da empresa é investir na compra e venda de imóveis com preços mais altos, para obter mais lucro, o ideal é investir nos que possuem melhor localização, maior área e melhor qualidade da construção e design.

**Uma vez a casa em posse da empresa, qual o melhor momento para vendê-las e qual seria o preço da venda?**

O melhor momento para comprar é entre novembro e janeiro, e o melhor momento para vender é entre fevereiro e maio. 

**A House Rocket deveria fazer uma reforma para aumentar o preço da venda? Quais seriam as sugestões de mudanças?**

A decisão de fazer uma reforma deve ser baseada em uma análise cuidadosa dos custos em relação ao aumento esperado no preço. Caso valha a pena investir em uma reforma, o preço do imóvel geralmente aumenta em cerca de 33.92%. Sugestões de mudanças incluem melhorias na qualidade da construção e design, como atualização de acabamentos, renovação de banheiros e cozinha, e expansão da área interna, caso seja viável financeiramento.
