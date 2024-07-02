## MVP Engenharia de dados

# 1. Objetivo
Objetivo do Trabalho:

O objetivo deste trabalho é analisar o desempenho dos alunos em exames de matemática, leitura e escrita para identificar padrões e fatores que influenciam suas notas. As perguntas de negócio a serem respondidas são:

1. Existe uma diferença significativa no desempenho entre gêneros?
2. Quais fatores estão associados a um desempenho superior em matemática?
3. Como a preparação para o teste e o apoio dos pais afetam as notas dos alunos?

# 2. Coleta

Descrição da Coleta

Os dados utilizados neste projeto foram obtidos do Kaggle, especificamente do dataset "Students Performance in Exams". Este conjunto de dados contém informações sobre o desempenho dos alunos em três áreas: matemática, leitura e escrita, bem como dados demográficos e de preparação para o teste.

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/3a5e21d2-dd09-4e5f-a6ba-1f05d59d11a7)
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/29e218cd-b11d-4ada-b6aa-34a4682ec3f4)

# 3. Modelagem
Modelagem dos Dados

Os dados foram carregados no Databricks a partir do arquivo CSV. As colunas foram renomeadas para remover caracteres especiais e espaços, facilitando a manipulação dos dados.

## Catálogo de Dados
- **gender:** Gênero do aluno (male, female)
- **race/ethnicity:** Grupo racial/étnico do aluno
- **parental_level_of_education:** Nível de educação dos pais
- **lunch:** Tipo de nível (standard, free/reduced)
- **test_preparation_course:** Curso de preparação para o teste (none, completed)
- **math_score:** Nota em matemática
- **reading_score:** Nota em leitura
- **writing_score:** Nota em escrita


![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/9b4e1da1-77fc-4f1f-b43b-8253e9c090be)
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/08d7a622-0ddc-435b-8745-75a2a78cfa91)

# 4. Carga
Descrição da Carga

Os dados foram carregados no Databricks a partir de um arquivo CSV. O DataFrame resultante foi salvo como uma tabela chamada students_performance para permitir consultas SQL.

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/20b417d7-a640-4f44-8d8d-1e1da4229191)
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/adc8968b-fd07-4b35-bf9a-51ea53b35f27)

# 5. Análise
Análise de Qualidade dos Dados e Solução do Problema

1. Diferenças de Gênero:
![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/93bcbb56-c9ef-47c1-95ec-7bcffc9c1004)

Interpretação: Este código calcula a média dos scores de matemática, leitura e escrita, agrupados por gênero, para identificar possíveis diferenças significativas no desempenho entre gêneros.

2. Correlação entre Scores:

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/f689ee35-7517-44d6-905c-7ff3880d9417)

Interpretação: Este código calcula a correlação entre os scores de matemática, leitura e escrita para identificar a relação entre esses desempenhos.

3. Impacto da Preparação para o Teste:

![image](https://github.com/luizthompson/MVP_Engenharia-_de_dados/assets/165716819/821d0049-8d99-409e-aa81-33fa7cd1c9aa)

# 6. Autoavaliação

Autoavaliação:

O objetivo principal de analisar o desempenho dos alunos foi alcançado. Identificamos diferenças significativas no desempenho entre gêneros e avaliamos o impacto da preparação para o teste nos scores dos alunos. As análises forneceram insights valiosos para responder às perguntas de negócio. A modelagem e a carga dos dados foram realizadas com sucesso, garantindo a integridade e a persistência dos dados na plataforma de nuvem.











