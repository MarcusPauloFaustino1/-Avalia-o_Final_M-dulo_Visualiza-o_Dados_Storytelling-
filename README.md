www.growdev.com.br

Atividade Prática Complementar

Utilizando os dados do Censo Escolar de 2021, disponibilizados pelo INEP, seguem
as orientações gerais da atividade:
• Realizar uma análise focada das entidades escolares com localização diferenciada
(área de assentamento, terra indígena e áreas remanescentes de quilombos) no
estado Rio Grande do Sul.
• O objetivo principal da investigação é entender a distribuição entre a quantidade
de docentes e a quantidade de matrículas dessas entidades.
• Foi solicitado para que os resultados sejam mostrados em dois gráficos separados
lado a lado considerando o tipo de localização da entidade (Urbana ou Rural).
• As escolas que não estão situadas em áreas de localização diferenciada devem
ser removidas da análise.
• O valor de quantidade de turmas também deve ser utilizado como uma dimensão
adicional para dar mais destaque às entidades que possuem mais turmas.
Para realizar a atividade, será necessário seguir alguns padrões:
1. Gerar os gráficos utilizando Python + Plotly (Google Colab).
2. Baixar a base de dados do Censo escolar 2021, necessária para a realização da
prática (esse material compactado já contém a base de dados em um arquivo
CSV e um dicionário de dados em um arquivo XLSX).
https://download.inep.gov.br/dados_abertos/microdados_censo_escolar_2021.zip
3. Os gráficos devem respeitar o template padrão “ggplot2”
4. O título do gráfico deve ser: “Censo Escolar 2021: Análise de Localização
Diferenciada (RS)”, centralizado, todo em negrito com tamanho de fonte 14.
5. O gráfico deve ser gerado com 600 pixels de altura e 1200 pixels de largura.
6. A legenda deve ser utilizada na orientação horizontal, centralizado e na parte
inferior do gráfico. Também deve apresentar o significado de cada dado,
conforme o dicionário de dados.

Criação de visual utilizando Python + Plotly

www.growdev.com.br

Criação de visual utilizando Python + Plotly

Atividade Prática Complementar

7. O título da legenda de ser alterado para: “Localização Diferenciada”, com
tamanho de fonte igual a 12.
8. Para escolas em área de assentamento, deve ser utilizada a cor “brown”.
9. Para escola em terra indígena, deve ser utilizada a cor “orange”.
10. Para escolas em áreas remanescentes de quilombo, deve ser utilizada a cor
“turquoise”.
11. Os títulos individuais dos subgráficos devem apresentar o significado de cada
tipo de localização, conforme o dicionário de dados.
12. O eixo com a quantidade de matrículas deve ser fixado entre 0 e 500. Deve
também receber o título: “Quantidade de Matrículas”, com fonte tamanho 11.
13. O eixo com a quantidade de docentes deve ser fixado entre 0 e 200. Deve
também receber o título: “Quantidade de Matrículas”, com fonte tamanho 11.
14. Os marcadores devem ter borda da cor preta e opacidade de 75%.
15. Marcadores devem ter seu tamanho máximo igual a 30.
16. No canto superior direito da imagem, deve ser inserida uma anotação com o
texto “Fonte: INEP”, com a cor “dark_gray” e fonte tamanho 12.
17. O visual deve ser exportado no formato HMTL com o nome:
“localizacao_diferenciada_rs.html”

Dicas

www.growdev.com.br

Atividade Prática Complementar

• Não se esquece de avaliar a base de dados e realizar os tratamentos
necessários.
• Funções do plotly.express possuem os parâmetros como o facet_col que facilitam
a criação de gráficos facetados conforme dados do próprio dataframe.
• Anotações presentes nos visuais podem ser acessadas individualmente, caso
enfrente problemas para alterar algum título.
• As funções update_xaxes e update_yaxes permitem a utilização e parâmetros
como row e col para alterar os eixos de somente um dos visuais caso necessário.
