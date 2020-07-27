# Ocupações urbana e rural no Brasil


## O que é
 - Mapas temáticos explorando as ocupações urbana e rural no Brasil.
 - Ocupação urbana: nuvens de pontos indicando concentração populacional + gradação de cores das densidades nas cidades (acima de 25 hab/ha)
 - Ocupação rural: gradação de cores das densidades no campo (abaixo de 1 hab/ha)
 
## Por que
 - 
 
## Método
 - A partir dos dados do Censo 2010 agregados por setor censitário, calculei a densidade populacional para cada setor em hab/ha (habitantes por hectare)
 - Além disso, para o caso das nuvens de pontos da ocupação urbana, gerei um ponto a cada 100 pessoas em cada setor (random points in polygon no QGIS) e selecionei a visualização heatmap com raio de 5
