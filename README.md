<p align="center">
  <img src="https://portalarquivos.saude.gov.br/campanhas/pni/img/pni_destaque.jpg" width = 70%>
</p>


# Projeto: Análise do Programa Nacional de Imunizações
### Aluno:André Vieira
---
Este repositório apresenta a o projeto desenvolvido para o Módulo 02 do Segundo Bootcamp de Ciência de Dados da Alura. Serão feitas análises em cima dos dados obtidos na fonte de dados abertos do DATASUS pelo serviço TABNET. Será realizada uma análise exploratória dos dados obtidos com uma explanação. Posteriormente, serão elaboradas hipóteses a serem confirmadas ou refutadas com a utilização de visualização de dados e conceitos de estatística.

# Dos Dados
---
Os dados trabalhados neste projeto são oriundos da fonte de dados abertos <a href="http://tabnet.datasus.gov.br/cgi/tabcgi.exe?pni/cnv/cpniuf.def">DATASUS</a>, com a utilização do serviço TABNET. A obtenção dos dados para essa análise foi realizada com a utilização da ferramenta TabNet (http://tabnet.datasus.gov.br/cgi/tabcgi.exe?pni/cnv/cpniuf.def) provida pelo DATASUS, descrita anteriormente. A base de dados utilizada foi do Programa Nacional de Imunizações (PNI), apresentando a cobertura vacinal no território brasileiro.

Para a construção da base, foram utilizados os seguintes parâmetros:
- Linha: Unidade da Federação
- Coluna: Ano
- Conteúdo: Coberturas Vacinais
- Períodos Disponíveis: 1994 a 2019

Durante o desenvolvimento das análises, outras bases de dados secundárias foram utilizadas sob demanda. Dentre estas, se encontram bases de dados do serviço de Atlas Geográfico, IBGE e wikipédia.

# Do Objetivo
---
O objetivo dessa análise é a realização de uma exploração dos dados históricos da cobertura vacinal do PNI. Para tanto, foram obtidas séries históricas dos dados que compõem as coberturas vacinais, separadas por unidade da federação. Será possível uma análise comparativa da evolução histórica dos estados perante a aplicação das vacinas. Assim como, analisar a dificuldade de se fazer uma maior cobertuda levando em consideração tamanho da população e densidade demográfica de cada unidade federativa.

# Da Metodologia Utilizada
---
Precedendo as análises dos dados, foi necessária um pré-processamento das bases de dados, realizando cortes temporais e outros tratamentos dos dados. Foram criadas tabelas e gráficos de proporcionalidade e correlação com linhas de tendências para a avalização da influência de uma base na outra. Foram elaboradas 4 perguntas de pesquisa a serem respondidas durante as análises:
  - Pergunta 1: A evolução da cobertura vacinal seguiu uma tendência crescente durante os anos, mostrando um desenvolvimento da saúde do país?
  - Pergunta 2: Estados com maiores Índices de Desenvolvimento Humano (IDH) possuem uma cobertura vacinal maior?
  - Pergunta 3: Estados com uma maior população tendem a possuir uma cobertura vacinal menor por necessitar maiores campanhas de vacinação e um maior número de doses a serem aplicadas?
  - Pergunta 4: Estados menos populosos, nos quais os habitantes ficam mais isolados, possuem uma cobertura vacinal menor?

# Respostas
---
  - Resposta 1: Há uma tendência de estabilidade na cobertura vacinal nas unidades da federação em torno de 70 a 80%. Logo, o dado analisado apresenta uma estabilidade e não um crescimento.
  - Resposta 2: Pode-se concluir que quanto maior o IDHM de uma unidade da federação, há uma tendência de se ter uma maior cobertura vacinal. No entanto, foram obtidos apenas 4 anos para fins de comparação e a nuvem de pontos se encontra ligeiramente espalhada, possuindo em sua maioria, uma linha de tendência crescente.Isto posto, se faz necessário uma nova comparação com um maior número de anos para afirmações mais precisas, mas a princípio, devido ao espalhamento dos pontos, a dúvida permanece.
  - Resposta 3: Pode-se concluir que as séries históricas das coberturas vacianais das unidades da federação de maior população e de menor população são semelhantes. Inclusive, há determinados anos que o estado de maior população possui uma melhor cobertura vacinal e outros que possui uma pior. Isto posto, conclui-se que o tamanho da população de um estado não influi diretamente na sua cobertura vacinal.
  - Resposta 4: Há uma forma de se induzir o leitor médio a uma conclusão errada. Nesta, os estados menos populosos são mais fáceis de se obter uma cobertura vacinal melhor. No entanto, comparando as séries históricas de coberturas vacinais dos estados mais e menos populosos, pode-se concluir que estas são muito semelhantes, de modo que a populosidade dos mesmos pouco influencia nas coberturas vacinais.

# Conclusão
---
Após todas as análises efetuadas sobre as séries históricas de coberturas vacinais, populações e a área geográfica das unidades da federação, pode-se afirmar que o Brasil não possui um problema na logística de distribuição de suas vacinas. Desse modo, a cobertura vacinal de sua população se dá de modo semelhante tanto em estados contendo um maior número de habitantes, como para estados com um menor número. A mesma conclusão se aplica á densidade demográfica dos estados. Tanto estados mais populosos, assim como os menos populosos, possuem coberturas vacinais semelhantes.
