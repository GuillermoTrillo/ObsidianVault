Um Data Store é um repositório para armazenar e gerenciar dados.

Técnicamente podemos dividir os Data Stores em 7 categorias:

1. Bancos de Dados relacionais (SQL - Normalmente usados em Warehouses)
2. Bancos de Dados Não Relacionais (NoSQL - Podem ser usados em Warehouses ou em Lakes)
3. Sistemas de Arquivos (Distribuídos ou não, são usados em Lakes e Lakehouses)
4. Armazenamento Key-Value
5. Full-Text Search Engine
6. Fila de Mensagens
7. In-Memory Data Store

Do 3 ao 7, são as categorias que realmente entram na categoria de Data Store propriamente dito.

### Sistemas de Arquivos
- Podem ser local ou em rede (NTFS, FAT, NAS, SAN)
- Podem ser distribuídos (HDFS - Hadoop Distributed File System, Object Storage)
- Podem ser na nuvem (Amazon S3, Azure Blob Storage, Google Storage Delta Lake)
- O objetivo é armazenar dados em qualquer formato de arquivo (CVS, JSON, PARQUET, AVRO, ORC, etc..)
- Em geral têm baixo custo.

### Key-Value
Outra maneira de armazenar dados não relacionais é um armazenamento chave-valor.
Um armazenamento de chave-valor é basicamente um hashmap em escala de produção: um mapa de chaves para valores. Não há esquemas sofisticados ou relacionamentos entre os dados. Nenhuma tabela ou outro grupo lógico de dados do mesmo tipo. Apenas chaves e valores, é isso.
Exemplos: Redis e Memcached.

### Full-Text Search Engine (mecanismo de pesquisa de texto)
Os mecanismo de pesquisa são um tipo especial de armazenamento de dados projetados para um caso de uso muito específico: pesquisar documentos de texto.
Você envia documentos semiestruturados para o mecanismo de pesquisa mas em vez de armazená-los como estão e usar analisadores XML ou JSON para extrair informações, o mecanismo de pesquisa divide o conteúdo do documento em um novo formato otimizado para pesquisa com base em substrings de campos de texto
Elasticsearch é o principal representante desta categoria.

### Fila de Mensagens
Um Data Store bastante útil é o tipo fila de mensagem, agindo como um middleware.
Você pode se surpreender ao ver as filas de mensagens nesta lista porque elas são consideradas mais uma ferramente de transferência de dados do que uma ferramenta de de armazenamento, mas as filas de mensagem armazenam seus dados com tanta confiabilidade e ainda mais persistência do que algumas das outras ferramentas que listamos anteriormente.
O Apache Kafka é o principal Representante desta categoria.

### In-Memory Data Store
In-Memory Data Stores são sistemas que armazenam, leem, gravam e acessam dados na memória de acesso aleatório (RAM) em vez de na memória somente leitura (ROM).
Os In-Memory Data Stores usam RAM para recuperar dados rapidamente, fazendo réplicas constantemente atualizadas de registros de dados e são definidos elo local em que mantêm os dados, não necessariamente pelo tipo da estrutura de dados.
Redis, VoltDB e SAP Hana são os principais representantes desta categoria.