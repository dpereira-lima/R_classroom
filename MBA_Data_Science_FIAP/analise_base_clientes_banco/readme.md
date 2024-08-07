## Explicação em Português

Neste diretório realizo uma análise exploratória sobre os dados gerados de uma junção de duas bases de dados (cadastral e transacional) de clientes de um banco de varejo.

As técnicas utilizadas nesta analise foram aprendidas na disciplina Working with R do MBA Data Science da FIAP.

  - Primeiro importo a base cadastral de clientes (arquivo XLSX);
    - Analiso algumas variáveis desta base e crio a variável Faixa salaria (fx_salario) com a função CUT.
  - Importo a base transacional de clientes;
  - E crio um novo dataset com a união das duas bases, utilizando a função MERGE e a variável ID para relacionar os dados;
  - Crio a variável Comprometimento da Renda, com resultado da divisão dos valores das variáveis ValorEmprestimo e Salario;
  - Comparo a quantidade de filhos por sexo (Masculino ou Feminino);
  - Faço uma análise gráfica das variáveis Sexo e Classificação;
  - E por fim aplico 4 vezes o algoritmo de Machine Learning "Decision tree" sobre o dataset, alternando as variáveis preditoras para comparar os resultados.


## Explanation in English

In this directory I carry out an exploratory analysis on the data generated from a combination of two databases (registration and transactional) of customers of a retail bank.

The techniques used in this analysis were learned in the Working with R discipline of FIAP's MBA Data Science.

 - First I import the customer registration base (XLSX file);
 - I analyze some variables from this base and create the variable Salary range (fx_salario) with the CUT function.
 - Import the transactional customer base;
 - And I create a new dataset with the union of the two bases, using the MERGE function and the ID variable to relate the data;
 - I create the Income Commitment variable, with the result of dividing the values of the ValueLoan and Salary variables;
 - Compare the number of children by sex (Male or Female);
 - I perform a graphical analysis of the Sex and Classification variables;
 - And finally, I apply the "Decision tree" Machine Learning algorithm 4 times on the dataset, alternating the predictor variables to compare the results.
