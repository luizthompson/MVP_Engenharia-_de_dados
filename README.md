## MVP Engenharia de dados
## Autor: Luiz Guilherme Thompson Vaz

# 1. Objetivo
Objetivo do Trabalho:

Analisar o desempenho dos estudantes em exames com base em variáveis socioeconômicas e educacionais.

1. Qual é a distribuição do desempenho dos estudantes em diferentes matérias (matemática, leitura, escrita)?
2. Como as variáveis socioeconômicas (como nível de educação dos pais, tipo de almoço) influenciam o desempenho dos estudantes?
3. Quais medidas podem ser adotadas para melhorar o desempenho dos estudantes com baixo desempenho?

# 2. Coleta

Descrição da Coleta:

Neste passo, vou coletar os dados do desempenho dos estudantes a partir do Kaggle e carregá-los na plataforma de nuvem Databricks. Utilizando um arquivo CSV disponível publicamente para isso.

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/7c0d9f0f-d93d-4932-8d83-6bccbe301540)
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/e2dc632e-195d-44dc-94eb-19d94ae1c5f4)

# 3. Modelagem

Neste passo, vou realizar a modelagem dos dados. Renomeando as colunas para remover caracteres especiais e selecionar colunas numéricas para análise descritiva. Também criarei um catálogo de dados detalhando os dados utilizados.

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/5c83c141-6052-47e2-9231-42163c7d9710)

## Catálogo de Dados
- **gender:** Gênero dos estudantes, tipo String
- **race/ethnicity:** Raça/etnia dos estudantes, tipo String
- **parental_level_of_education:** Nível de educação dos pais, tipo String
- **lunch:** Tipo de almoço dos estudantes (standard/reduced), tipo String
- **test_preparation_course:** Participação em curso de preparação para o teste, tipo String
- **math_score:** Pontuação em matemática, tipo Integer
- **reading_score:** Pontuação em leitura, tipo Integer
- **writing_score:** Pontuação em escrita, tipo Integer

# 4. Carga

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/038c2792-f08b-4535-a94d-64512cf4215c)
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/63fd609b-31ea-4e87-8a4e-2b7494be80ca)

# 5. Análise

Neste passo, vou analisar a qualidade dos dados e responder às perguntas de negócio definidas no objetivo. Isso inclui a análise descritiva dos dados e a criação de visualizações para ilustrar as descobertas.

# 5.1 Análise de Qualidade dos Dados

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/de6e58fe-805b-4e33-81a8-61f766fc8403)

# 5.2 Análise das Perguntas de Negócio

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/9d07e573-7ef0-42d6-8634-19be1832ad50)
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/1739643c-0481-446f-a394-08ad859207e1)

# 6. Medidas para Melhorar o Desempenho dos Estudantes

Com base na análise, proponho algumas medidas que podem ser adotadas para melhorar o desempenho dos estudantes com baixo desempenho.

## Medidas para Melhorar o Desempenho dos Estudantes

1. **Programas de Tutoria:** Implementar programas de tutoria para ajudar estudantes com baixo desempenho.
   - **Justificativa:** A tutoria pode oferecer suporte individualizado e ajudar os estudantes a melhorar suas habilidades.

2. **Engajamento dos Pais:** Incentivar a participação dos pais na educação dos filhos.
   - **Justificativa:** Pais mais engajados podem oferecer um ambiente de apoio ao aprendizado em casa.

3. **Cursos de Preparação para Testes:** Oferecer cursos de preparação para testes a todos os estudantes.
   - **Justificativa:** Cursos de preparação podem ajudar os estudantes a se familiarizarem com o formato dos exames e melhorar seu desempenho.

4. **Refeições Escolares Nutritivas:** Garantir que todos os estudantes tenham acesso a refeições escolares nutritivas.
   - **Justificativa:** A nutrição adequada é essencial para o bom desempenho cognitivo e acadêmico.

# 7. Autoavaliação

Eu consegui atingir os objetivos delineados no início do trabalho. Consegui responder às perguntas de negócio propostas e realizei uma análise detalhada dos dados. As principais dificuldades encontradas foram relacionadas à manipulação e transformação dos dados, mas consegui superá-las com o uso das ferramentas do Databricks. No futuro, gostaria de aprofundar a análise incluindo mais variáveis e explorando técnicas de machine learning para prever o impacto das variáveis socioeconômicas no desempenho dos estudantes.

# 8. Conclusão

Este trabalho apresentou uma análise detalhada do impacto das variáveis socioeconômicas no desempenho educacional dos estudantes, utilizando o Databricks para coleta, modelagem, carga e análise dos dados. As respostas às perguntas de negócio foram bem fundamentadas e apresentadas com base nos dados analisados.

Os principais insights obtidos incluem:
- Distribuição do desempenho dos estudantes em diferentes matérias.
- Entendimento de como variáveis socioeconômicas, como o nível de educação dos pais, influenciam o desempenho escolar.
- Propostas de medidas para melhorar o desempenho dos estudantes com baixo desempenho.

A execução deste trabalho no Databricks permitiu uma gestão eficiente dos dados e facilitou a implementação de processos de ETL, análises exploratórias e visualizações. O uso de tabelas Delta garantiu a persistência e integridade dos dados ao longo do processo.

Para trabalhos futuros, sugere-se a inclusão de mais variáveis e a aplicação de técnicas de machine learning para prever o impacto das variáveis socioeconômicas no desempenho dos estudantes, possibilitando um planejamento mais robusto e proativo para o setor educacional.


## Referências
- Dados de desempenho dos estudantes: [Students Performance in Exams - Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams)

