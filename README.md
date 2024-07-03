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

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/421b8619-ea9a-434e-bef6-b4189e8f020f)
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/4b8f1f84-af81-431c-87ff-ce48ec605ea6)

## b. Solução do Problema

Nesta sub-etapa, eu responderei a algumas perguntas de negócio específicas utilizando consultas SQL.

Exemplo de perguntas de negócio:

1. Quantos passageiros sobreviveram e quantos não sobreviveram?.

2. Qual a taxa de sobrevivência por classe?

3. Qual a taxa de sobrevivência por sexo?

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/d62f5fba-1553-4a93-8a8c-435e1d4ab3d2)

# Autoavaliação
Na seção de autoavaliação, eu devo refletir sobre o trabalho realizado, abordando os seguintes pontos:

1. Quais foram os objetivos do projeto e como foram atingidos?

2. Quais desafios enfrentei durante o desenvolvimento do projeto e como os superei?

3. O que poderia ser melhorado no projeto?

4. Quais foram as principais lições aprendidas?

### Objetivos do Projeto

O objetivo principal deste projeto foi analisar os dados dos passageiros do Titanic para identificar os fatores que influenciaram a sobrevivência. Eu queria entender como variáveis como classe, sexo, idade e local de embarque afetaram as taxas de sobrevivência. Para atingir esses objetivos, eu segui uma abordagem estruturada que envolveu a coleta, modelagem, carga e análise dos dados.

### Desafios Enfrentados

Durante o desenvolvimento do projeto, enfrentei vários desafios. Um dos principais foi garantir a qualidade dos dados. Identifiquei e tratei valores nulos e inconsistências nos dados. Outro desafio foi a criação de um modelo de dados eficiente. Optei por um esquema estrela para facilitar as análises, mas tive que garantir que todas as dimensões estavam bem definidas.

### Melhorias Futuras

Para futuras melhorias, considero que poderia expandir a análise incorporando técnicas de aprendizado de máquina para prever a sobrevivência dos passageiros com base em novos dados. Além disso, incluir variáveis adicionais, como a profissão dos passageiros ou o motivo da viagem, poderia fornecer insights ainda mais detalhados.

### Lições Aprendidas

A principal lição aprendida foi a importância de uma abordagem estruturada para a análise de dados. Começar com uma coleta de dados robusta e garantir a qualidade dos dados é fundamental. A modelagem correta dos dados facilita análises posteriores e garante resultados mais precisos. Também aprendi a importância da documentação detalhada em cada etapa do processo, o que ajuda na replicabilidade e na clareza do trabalho.

### Conclusão

Com este projeto, consegui entender melhor os fatores que influenciaram a sobrevivência dos passageiros do Titanic. Respondi às perguntas de negócio definidas inicialmente e obtive insights valiosos sobre como variáveis como classe, sexo e local de embarque impactaram as chances de sobrevivência. Esta análise pode servir como base para estudos futuros e para a aplicação de técnicas de análise de dados em outros conjuntos de dados complexos.
