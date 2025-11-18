## ESTRUTURA DA PASTA

Esta pasta tem como objetivo armazenar os códigos. Basicamente, arquivos de extensão ```.py``` ficarão aqui. 

A estrutura está dividida seguindo os conceitos de **ETL (Extract, Transform, Load)**

### extract/
Funções para extrair os sites

### transform/ 
Funções de limpeza dos dados extraídos

### load/
Final do ETL, funções para salvar os arquivos

### pipeline/
Código principal, chama todas as funções e cria todo o fluxo ETL como um só