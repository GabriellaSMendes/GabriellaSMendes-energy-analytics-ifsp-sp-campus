# 🔌 Análise Energética - IFSP Campus São Paulo

*README provisório para entender a estrutura das pastas*

## Estrutura das pastas

### src/
Esta pasta tem como objetivo armazenar os códigos. Basicamente, arquivos de extensão ```.py``` ficarão aqui. 

A estrutura está dividida seguindo os conceitos de **ETL (Extract, Transform, Load)**

#### extract/
Funções para extrair os sites

#### transform/ 
Funções de limpeza dos dados extraídos

#### load/
Final do ETL, funções para salvar os arquivos

#### pipeline/
Código principal, chama todas as funções e cria todo o fluxo ETL como um só

### data/

Essa é a pasta dos **arquivos**, os arquivos serão salvos aqui após o processo de ETL

### raw/
Dados brutos, sem limpeza

### processed/
Dados limpos e processados