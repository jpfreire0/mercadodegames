# Mercado de games

*Esse projeto foi desenvolvido como conclusão do curso de certificação de Data Analytics do Google. A visualização produzida pode ser acessada [aqui](https://public.tableau.com/app/profile/jpfreire/viz/Mercadodegames). As informações a seguir são explicações de como foram feitas as etapas para chegar no resultado.*

## Introdução

A indústria de jogos eletrônicos tem demonstrado crescimento nos últimos anos. Com isso, foram feitos alguns questionamentos para um melhor entendimento das vendas desse setor. 

- Qual gênero mais popular entre os anos de 2000 e 2010?
- Jogos multiplataforma venderam mais que jogos lançados apenas em uma plataforma?
- Quais empresas mais venderam jogos?
- Qual ano com a maior quantidade de jogos vendidos?
- Quais outras observações podem ser extraídas?

Foi utilizado o conjunto de dados disponível no [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales) a partir de informações obtidas do site [VGChartz](https://www.vgchartz.com/) entre os anos de 1980 e 2020. O dataset contém jogos que tiveram mais de 100.000 unidades vendidas.

As ferramentas utilizadas foram o **Google Sheets** e **Tableau**.

Observações:

- O dataset não considera jogos de celular
## Análise

Para a análise foram produzidas tabelas dinâmicas com os cálculos necessários para obter as respostas. O primeiro ponto observado é que existe correlação entre o número de jogos lançados e o número de unidades vendidas. 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5a092e8d-8b38-4372-964e-b63fe48dd4d0/Untitled.png)

O gênero que mais aparece entre os anos de 2000 e 2010 é o de Ação.

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c5d89f02-aaac-4b03-9eba-9e618e7c9176/Untitled.png)

Foi necessário identificar quais eram os jogos que apareceram mais de uma vez e os que apareceram apenas uma. Com isso foi adicionado uma coluna para identificar a quantidade de vezes que um jogo aparece na lista.

Uma descoberta é que jogos multiplataforma aparecem em menor quantidade, mas venderam mais do que os que foram lançados apenas em uma plataforma. Isso não necessariamente significa que jogos que aparecem 1 vez na lista não tiveram outras versões que podem ter vendido menos unidades e não computado para a lista. 

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/b8e16bad-18b2-4f7f-b96c-ac0b3562ddb5/Untitled.png)

A empresa que aparece com a maior quantidade de unidades vendidas é a Nintendo

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d32dbb9a-7170-4b67-9abd-31c7442d1759/Untitled.png)

2008 foi o ano com a maior quantidade de vendas

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/bce04ad7-89d9-433b-969f-2aef0cb28087/Untitled.png)

A região da América do Norte representa 49,3% das vendas

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/efa1df32-61d5-484c-abfb-f372190cab1c/Untitled.png)

## Conclusão
