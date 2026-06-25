Otimização com PySpark

Nesta etapa final foram aplicadas técnicas de otimização no processamento dos dados do YouTube.

Atividades desenvolvidas

* Leitura dos arquivos Parquet preparados
* Criação de tabelas temporárias
* Join entre vídeos e comentários usando Spark SQL
* Uso de `repartition`
* Uso de `coalesce`
* Análise do plano de execução com `explain`
* Aplicação de filtros antes do join
* Seleção apenas das colunas necessárias
* Salvamento do join otimizado em formato Parquet
