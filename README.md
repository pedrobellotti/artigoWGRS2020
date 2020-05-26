# WGRS 2020

## Balanceamento Dinâmico de Carga para Funções Virtuais sobre Comutadores OpenFlow Heterogêneos
_João Victor G. de Oliveira, Pedro C. P. Bellotti, Rafael G. Motta, Roberto M. de Oliveira, Alex B. Vieira, Luciano J. Chaves_

Neste repositório você encontra os códigos e saídas do artigo.

## Organização das pastas
* Códigos: códigos usados nos computadores cliente, servidor e controlador, bem como o notebook Jupyter usado para gerar os gráficos.
* Saídas: todas as saídas geradas pelo controlador, comutadores, cliente e servidor durante a execução

## Nomeação dos arquivos de saída
As saídas estão nomeadas de forma testeX_YZ, onde:
* X - Número da execução, bem como sua seed (seed = x*10)
* Y - Política utilizada no teste (pi = Política Estática, sw = Política Dinâmica)
* Z - Carga utilizada na execução (010 = carga alta, 020 = carga média, 030 = carga baixa)
