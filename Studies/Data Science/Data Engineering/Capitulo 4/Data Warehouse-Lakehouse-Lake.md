
# Data Warehouse
Um Data Warehouse é um tipo de banco de dados projetado especificamente para consultas e análises eficientes de grandes quantidades de dados.

Ele é normalmente usado para armazenar e gerenciar dados de várias fontes, como bancos de dados transacionais ou arquivos de log.

Warehouse pode ser feito com qualquer formato de armazenamento, pois é um conceito. SQL, NoSQL ou formato colunar ou baseado em linha.

Existem vários motivos pelos quais você pode optar por usar um Data Warehouse.

1. Grande volume de dados: Se a empresa possui um grande volume de dados que precisam ser armazenados e analisado, um Data Warehouse pode ser uma solução eficiente.
2. Necessidade de desempenho de consulta analítica: Os DW são projetados especificamente para desempenho de consultar, o que pode ser importante se você precisar recuperar e analisar grandes quantidades de dados de maneira rápida.
3. Necessidade de integrar dados de várias fontes: Se você tiver dados de várias fontes que precisa integrar e analisar em conjunto, um Data Warehouse pode ser uma ferramenta útil.
4. Necessidade de oferecer suporte à inteligência de negócios (BI) e relatórios: Os DW costumam ser usados como base para inteligência de negócios e sistemas de relatórios, pois permitem consultas e análises de dados rápidas e eficientes.
5. Necessidade de dados históricos: Os DW são frequentemente usados para armazenar dados históricos, pois permitem consultas e análises de dados ao longo do tempo.

# Data Lake
Um DW requer que os dados sejam limpos e organizados antes do armazenamento. O Data Lake permite o armazenamento dos dados no seu formato bruto para posterior processamento e organização.

DW -> Limpa e organiza, depois carrega.
DL -> Carrega, depois limpa e organiza.

Um Data Lake é um repositório centralizado que permite armazenar e processar grandes quantidades de dados estruturados e não estruturados em escala. Ele foi projetado para lidar com uma ampla variedade de tipos de dados e pode armazenar dados em sua forma bruta e não estruturada, permitindo que você armazene e processe dados de maneira mais flexível e escalável do que um banco de dados tradicional.
Assim como o DW, o Data Lake é um **conceito**. Mas por definição um banco de dados SQL não seria o ideal, uma vez que a ideia é carregar primeiro e limpar e organizar os dados depois. Podemos usar bancos de dados NoSQL ou tecnologias de armazenamento distribuído para construir Data Lakes, localmente ou na nuvem.
Existem vários motivos pelos quais você pode optar por usar um Data Lake.
1. Necessidade de armazenar e processar dados em sua forma bruta: Os Data Lakes permitem que você armazene processe dados em sua forma bruta e não estruturada, o que pode ser útil se você precisar preservar os dados originais ou se quiser manter a flexibilidade na forma como processa e analisa os dados.
2. Necessidade de armazenar e processar grandes volumes de dados: Se você possui um grande volume de dados que precisam ser armazenados e processados, um Data Lake pode ser uma solução eficiente.
3. Necessidade de armazenar e processar dados estruturados e não estruturados: Os DL são adequados para armazenar e processar dados estruturados e não estruturados tornando-os uma boa escolha se você tiver uma variedade diversificada de tipos de dados.
4. Necessidade de escalabilidade: Os DL são projetados para serem escaláveis, permitindo que você armazene e processe facilmente grandes quantidades de dados à medida que suas necessidades aumentam.
5. Necessidade de um repositório de dados centralizado: Se você tiver dados de várias fontes que precisa armazenar e processar em um local centralizado, um DL pode ser uma ferramenta útil.


# Data Lakehouse
Um Data Lakehouse pode ser definido como uma plataforma de dados modernas construída am partir de uma combinação de um Data Lake e um Data Warehouse.
Mais Específicamente, um Data Lakehouse une o armazenamento flexível de dados não estruturados de um Data Lake e os recursos e ferramentas de gerenciamento de Data Warehouses e os implementa estrategicamente como um sistema maior.
Essa integração de duas ferramentas exclusivas traz o melhor dos dois mundos para os usuários. DLH implementam estruturas de dados e recursos de gerenciamento de dados semelhantes aos de um DW diretamente sobre o armazenamento em nuvem de baixo custo em formatos aberto e, normalmente, distribuídos.
O DOLH traz o princípio:
**From BI to AI**
A questão é que nem todas as empresas estão usando AI (Artificial Intelligence).
Ou ainda, tudo que a empresa precisa é de um relatório de BI ou apenas de um sistema de armazenamentos de dados no formato bruto.
**Vantagens:**
- Escalabilidade
- Flexibilidade
- Desempenho de Consulta
- Repositório Centralizado
**Desvantagens:**
- Complexidade
- Uso intensivo de Recursos
- Desafios Adicionais de Governança de Dados
- Desafios Adicionais de Integração de Dados