# Characterizing High-Quality Test Methods: A First Empirical Study.

Veloso, Victor, and Andre Hora. "Characterizing High-Quality Test Methods: A First Empirical Study." arXiv preprint arXiv:2203.12085 (2022).. (https://doi.org/10.48550/arXiv.2203.12085) doi: [10.48550/arXiv.2203.12085]

## 1. Fichamento de Conteúdo

O artigo se trata de um estudo empírico sobre qualidade de _software_ e como definir se um teste é capaz de garantir a qualidade de um sistema, pois mesmo que exista uma grande cobertura de linhas de código por meio de suítes de testes criadas pelo desenvolvedor ainda não seria possível afirmar que ele é confiável. Para o estudo foi utilizado o teste de mutação como base para avaliar os métodos de teste utilizados nos 15 repositórios de _JAVA_ mais populares do _github_ que após clonados foi utilizado uma ferramenta de geração de testes mutação que para gerar os resultados foi analisado diversas métricas de qualidade de teste em relação ao _mutation score_ obtido por cada um deles. Por meio da análise dos resultados os autores do artigo conseguiram identificar que a maior diferença entre a qualidade dos métodos de teste mais utilizados é o foco em relação a evitar _Test smells_ onde repositórios com _mutation score_ menores apresentaram um maior número de casos de testes irrelevantes. Os autores do artigo pretendem utilizar mais métricas para melhorar os resultados e garantir um estudo mais confiável para futuras pesquisas.

## 2. Fichamento Bibliográfico

- _Mutation Test_ (Teste de mutação): é um metodo de teste usado para projetar novos testes de software e avaliar a qualidade dos testes de software existente modificando o código fonte de pequenas maneiras (Pagina 1).
- _Mutation Score_ (Pontuação de mutação): resultado obtido pela porcentagem em que os casos de testes conseguiram identificar e eliminar as mudanças realizadas no código (Pagina 2).
- _Test smells_ (Mal cheiro de teste): Maá práticas de casos de teste onde o código não agrega a qualidade geral do produto(Pagina 4).

## 3. Fichamento de Citações

- _"Software testing is a key practice in software development. As a proxy of test quality, one can rely on code coverage or mutation analysis. Coverage measures the percentage of code that is covered by tests and is typically used to assess the test effectiveness."_
- _"However, it presents some limitations. For example, one can have great coverage with no assert. Although test suite mutation testing is ideal for gathering the overall test quality in a system, it has three limitations: the overall system mutation score overshadows the quality of individual test methods; the quality of a contribution can be unnoticed in a large system because its score may be unaffected by small code changes; existing test methods may kill mutants within a contribution and hinder assessing the quality of the contributed tests."_
- _"We collect the top 15 Java repositories from GitHub (in terms of the star metric) and the Apache Commons Lang. Next, for each project, we clone the latest master branch version, manually configure the extended PIT via their build configuration file, and discard the projects accused by PIT of having failing tests."_
- _"After selecting the target projects, we start the mutation testing execution phase. Table 1 summarizes this analysis: in total, PIT detected 18,321 test cases in the five projects. Overall, it generated 55,427 mutants, which resulted in 16,149,383 mutant executions. The mutation scores are overall high, ranging from 73% (Okhttp) to 86% (Commons Lang)."_
- _"We show empirical evidence that there are no major differences between high-quality and low-quality test methods in terms of size, number of asserts, and modifications. Low-quality test methods are overconcentrated on critical test smells, while high-quality test methods are likely to contain less important ones."_
