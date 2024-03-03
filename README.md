# Dados Meteorológicos Especializados

## Introdução
 O presente projeto tem como propósito a construção e análise de um Banco de Dados Geográficos (BDG) a partir de dados meteorológicos do Instituto Nacional de Meteorologia (INMET). O foco recai sobre a variável da temperatura máxima captada pelas estações meteorológicas do estado do Espírito Santo no período de 2019 a 2023, visando investigar sua tendência temporal e sua possível relação com o fenômeno do aquecimento global.

## Construção do Banco de Dados Geográfico
 Inicialmente, utilizando a OMT-G foi feito um modelo do banco a ser produzido:
 
![image](https://github.com/leticiascofield/BancoDeDados_MeteorologicosEspecializados/assets/125830543/c4632361-aef5-4102-a971-30ed189c8eef)

 Os dados acerca da divisão territorial foram obtidos no IBGE. O Modelo de Elevação Digital foi obtido no INPE.
 O banco foi construído com o PostGIS.

## Visualizações
**Temperatura máxima média com altitude das estações em todos os anos**
- Propósito da visualização: Avaliar a temperatura máxima média de acordo com a altitude.
- Escolha do plano de fundo: Modelo de Elevação Digital como Tesselação, Divisão Territorial.
- Escolha de parâmetros gráficos/visuais: Gradiente da coloração das estações, na qual o azul representa uma temperatura menor e o vermelho, uma temperatura maior.
- Processo de produção: Foi utilizado o PostGIS para calcular a média, QGIS e paint.net para gerar a visualização

![image](https://github.com/leticiascofield/BancoDeDados_MeteorologicosEspecializados/assets/125830543/29bfd50b-2123-47d4-ab62-092f2c47776b)

**Razão entre a temperatura máxima média de 2023 e a de 2019**
- Propósito da visualização: Avaliar o crescimento da temperatura máxima média nos últimos 5 anos.
- Escolha do plano de fundo: Modelo de Elevação Digital como Tesselação, Divisão
Territorial.
- Escolha de parâmetros gráficos/visuais: Gradiente da coloração das estações, na qual o branco representa uma razão menor e o vermelho, uma razão maior.
- Processo de produção: Foi utilizado o PostGIS para calcular a média, QGIS e paint.net para gerar a visualização.

![image](https://github.com/leticiascofield/BancoDeDados_MeteorologicosEspecializados/assets/125830543/b967239b-c003-4abc-87ca-de4b76694210)

Também foi gerado um gráfico para auxiliar a visualização, detalhando a média da temperatura máxima em cada ano, em cada estação.

![image](https://github.com/leticiascofield/BancoDeDados_MeteorologicosEspecializados/assets/125830543/c03dfb0c-3984-4a8a-b3b7-e3e6ef5c82b4)

## Documentação Adicional
 Para informações mais detalhadas sobre os dados e a análise realizada, consulte o arquivo PDF fornecido junto com este repositório.
