- Um pipeline de dados é um meio de mover dados de um local (a origem) para um destino (um Data Warehouse ou Data Lake, entre outros). Ao longo do caminho, os dados são transformados e otimizados, chegando a um estado em que podem ser analisados e usados para desenvolver insights de negócios.

Geralmente o Pipeline inclui carregar dados brutos em uma tabela de preparação (área intermediária ou Staging Area) para armazenamento temporário e, em seguida, aterá-los antes de inseri-los no destino.

Pipelines é um **conceito,** e pode ser implementado de muitas formas diferentes.


**Pipeline de Dados VS Pipeline ETL**

Pipeline ETL (**Extract, transform, load**) são um tipo de pipeline de dados, pois eles **movem** os dados de uma origem, **transformam** e em seguida os **carregam** em um destino. Mas ETL é só um subprocesso de um Pipeline de Dados. O termo ETL foi criado em uma época onde o único destino era um Data Warehouse e o processo era bem menos complexo. Atualmente, ETL faz parte de um processo maior de pipelines de dados. 
Como o processo é cada vez mais complexo, e hoje podemos ter inúmeras fontes de dados, inúmeros processamentos e inúmeros destinos.