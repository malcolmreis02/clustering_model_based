## Resumo

Este trabalho se propõe a agrupar jovens residentes em Campinas que se alistaram para o serviço militar obrigatório, visando a prática segura de esportes coletivos na Escola Preparatória de Cadetes do Exército (EsPCex). Utilizando dados abertos fornecidos pelo Exército Brasileiro, foram extraídas informações de peso e altura dos jovens para realizar uma clusterização baseada em modelos. O método adotado envolveu o uso do algoritmo de *Expectation-Maximization* (EM) e o critério Bayesiano de Informação (BIC) para determinar o número ideal de clusters. Como resultado, foram identificados quatro grupos distintos, permitindo uma distribuição mais equilibrada dos jovens durante a prática esportiva, minimizando a possibilidade de lesões devido a diferenças de porte físico.

## Ferramentas Utilizadas

- **R**: Linguagem de programação utilizada para todo o processamento e análise dos dados.
- **readr**: Biblioteca para leitura de arquivos CSV.
- **dplyr**: Biblioteca para manipulação e transformação dos dados.
- **ggplot2**: Biblioteca para criação de gráficos.
- **magrittr**: Biblioteca para uso de pipes (%>%).
- **tidyr**: Biblioteca para manipulação de dados faltantes.
- **GGally**: Biblioteca para criação de gráficos de pares (ggpairs).
- **mclust**: Biblioteca para realização de clusterização baseada em modelos.

### Links Úteis

- [Dados utilizados](https://dadosabertos.eb.mil.br/arquivos/sermil/sermil2022.csv)
- [Projeto no GitHub](https://github.com/malcolmreis02/clustering_model_based)

### Tabelas e Gráficos

- **Tabela de Medidas de Dispersão**: Mostra as medidas de dispersão (mínimo, quartis, mediana, média, máximo) das variáveis peso e altura.
- **Gráfico de Pares**: Visualização das variáveis peso e altura e sua possível correlação.
- **Gráfico BIC por Número de Clusters**: Ajuda a determinar o número ideal de clusters.
- **Gráfico de Dispersão dos Dados Agrupados**: Mostra os dados agrupados conforme o modelo escolhido.

### Referências

1. Ludwig, Guilherme. Slides apresentados em aula na Universidade Estadual de Campinas em 2024.
2. Projeto do GitHub de Malcolm dos Reis sobre clusterização no serviço militar.
3. Bouveyron C, Celeux G, Murphy TB, Raftery AE. Model-Based Clustering and Classification for Data Science: With Applications in R. Cambridge University Press; 2019.
