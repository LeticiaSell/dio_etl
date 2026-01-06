# Santander 2025 - Ciência de Dados com Python
 
## Projeto de ETL - (extract, transform, load)
ETL (Extração, Transformação e Carregamento) é um processo fundamental de integração de dados que coleta informações de diversas fontes, as limpa e padroniza (transforma) e as move para um local centralizado, como um data warehouse, para análise e relatórios, sendo crucial para a tomada de decisões de negócios e Business Intelligence. Ele envolve três etapas sequenciais: Extração de dados brutos de origens variadas, Transformação para limpar, validar e agregar, e Carregamento no sistema de destino

## Informações Gerais
O projeto está considerando um arquivo .csv com a relação de candidatos para realizarem matrícula em alguns cursos. Através desse arquivo são extraídos os dados utilizados na etapa de transformação, onde utilizei a API do ChatGPT para criar mensagens de matrícula personalizadas para cada candidado, levando em conta o curso escolhido. As mensagens são acrescentadas ao data frame, e por fim é feito o carregamento desses dados atualizados em um novo arquivo .csv.

