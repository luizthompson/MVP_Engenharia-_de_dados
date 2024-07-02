## MVP Engenharia de dados
## Autor: Luiz Guilherme Thompson Vaz

# 1. Objetivos do Projeto

O objetivo principal deste projeto é analisar os dados dos passageiros do Titanic para identificar os fatores que influenciaram a sobrevivência. Este projeto seguirá uma abordagem estruturada que envolve as seguintes etapas:

1. **Coleta**: Carregar e armazenar os dados do Titanic na nuvem (Databricks).
2. **Modelagem**: Construir um modelo de dados eficiente em esquema estrela, incluindo tabelas de fatos e dimensões.
3. **Carga**: Persistir os dados no Data Warehouse do Databricks, garantindo a disponibilidade para consultas e análises futuras.
4. **Análise**: Realizar análises detalhadas para responder perguntas de negócio específicas e verificar a qualidade dos dados.

### Perguntas de Negócio

- Quantos passageiros sobreviveram e quantos não sobreviveram?
- Qual a taxa de sobrevivência por classe?
- Qual a taxa de sobrevivência por sexo?
- Quais outros fatores influenciaram a taxa de sobrevivência?

Esses objetivos serão alcançados utilizando as capacidades de processamento de dados do Spark e as funcionalidades de armazenamento e consulta do Databricks.

Configuração Inicial

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/1a609285-6976-49f1-8416-f6e73620de5e)

# 2. Coleta
Nesta etapa, eu vou carregar os dados do Titanic que já estão armazenados na nuvem no Databricks. Vou usar o caminho do arquivo CSV para carregar os dados em um DataFrame do Spark.

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/34892e3f-6a12-4d28-bed4-4f74373adb56)
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/7534a787-4259-404b-a584-9d1390e6be5d)

# 3. Modelagem
Nesta etapa, eu vou criar um modelo de dados. Optei por um esquema estrela que é comumente usado em Data Warehouses. Este modelo inclui uma tabela de fatos (contendo os dados principais) e várias tabelas de dimensões (contendo atributos descritivos).

Modelo de Dados: Vou criar um esquema estrela para o Titanic Dataset.

Fato: Passageiros
Dimensões: Sobrevivência, Classe, Sexo, Embarque

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/527ed191-1078-44b2-a6c6-8f4ca33a2561)


# 4. Carga
Nesta etapa, eu vou salvar os dados no banco de dados do Databricks para persistência, garantindo que os dados estejam prontos para consultas e análises futuras.

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/c8245899-75fd-4e5f-b5ba-d71b4f7ca285)

# 5. Análise

Nesta etapa, eu realizarei uma análise detalhada dos dados para verificar a qualidade e obter insights relevantes para responder às perguntas de negócio.

## a. Qualidade dos Dados

