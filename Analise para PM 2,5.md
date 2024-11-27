## Análise para PM 2,5
Neste repositório, serão apresentados dados provenientes de duas fontes:
- PM2,5_CAMS: Dados obtidos do Copernicus Atmosphere Monitoring Service (CAMS Global Reanalysis), um conjunto de dados de reanálise global da composição atmosférica, disponibilizado pelo ECMWF. Esses dados possuem resolução temporal de três horas e resolução espacial de 14 km. Os mesmos dados estão disponíveis no painel Vigiar [(Vigiar Saúde Ambiental.)](https://www.gov.br/saude/pt-br/composicao/svsa/saude-ambiental/vigiar)


-	PM2,5_EDF: Estimativas de concentração média mensal de PM 2,5, disponibilizadas pelo Grupo de Análise de Composição Atmosférica da Universidade de Washington. Esses dados têm resolução espacial de aproximadamente 1 km (ou ~0,01°) e estão disponíveis globalmente no portal Surface PM2.5, disponível em: <Surface PM2.5 | Atmospheric Composition Analysis Group | Washington University in St. Louis (wustl.edu)>. 

De acordo com as análises, as figuras 1 e 2, apresentadas abaixo, mostram a média de PM 2,5 no ano de 2000 por município. Observa-se um aumento significativo na média da região Norte ao longo dos 12 meses. Esse fenômeno pode ser investigado mais detalhadamente para identificar suas causas.




<img src='https://github.com/repositoriosaudeambienteuff/Dados-de-Saude-e-Meio-Ambiente/blob/02e938f4209ed23b645ad8490f10423251c00ca6/imagens/Mapa%20PM2%2C5%20JAN.png' width=58%></img>

<sub>Figura 1</sub>

<img src='https://github.com/repositoriosaudeambienteuff/Dados-de-Saude-e-Meio-Ambiente/blob/02e938f4209ed23b645ad8490f10423251c00ca6/imagens/Mapa%20PM2%2C5%20DEZ.png' width=58%></img>

<sub>Figura 2</sub>


A figura 3, por sua vez, exibe um boxplot dos valores de PM 2,5 no Brasil em janeiro de 2022. Nota-se que a mediana e os valores mínimos e máximos estão no intervalo [0, 10]. No entanto, há um grande número de outliers, indicando possíveis valores discrepantes. Esses valores podem ser explorados em estudos futuros para entender suas origens, configurando outro exemplo de uso deste repositório.

<img src='https://github.com/repositoriosaudeambienteuff/Dados-de-Saude-e-Meio-Ambiente/blob/0eed68108c029245f13a26db31e829a80297733b/imagens/boxplot%20PM%202%2C5%20Brasil%20em%20janeiro%20de%202022.png' width=58%></img>

<sub>Figura 3</sub>

Por fim, no dashboard interativo, será possível encontrar uma série temporal que ilustra a evolução da média de PM 2,5 ao longo do tempo. A figura 4, por exemplo, apresenta a média ao longo do ano de 2000, com um aumento acelerado dessas partículas a partir de julho, um ponto que merece atenção.

Vale destacar que o dashboard interativo disponibiliza mapas, boxplots e séries temporais para todos os meses entre 2000 e 2022.

<img src='https://github.com/repositoriosaudeambienteuff/Dados-de-Saude-e-Meio-Ambiente/blob/611510b8745f302d3684e5abecf363c7bc84ff6d/imagens/s%C3%A9rie%20temporal%20m%C3%A9dia%20de%20PM%202%2C5%202000.png' width=58%></img>

<sub>Figura 4</sub>
