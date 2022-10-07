# Desigualdade de Propriedade Imobiliaria nas Capitais

  Status do Projeto (Concluido)

# Objetivo do Projeto

  Esse projeto tem como objetivo estudar os imóveis localizados em grandes brasileiras e verificar se os imoveis em suas periferias tem seu preço subvalorizado.
  
# Tableau Links

- https://public.tableau.com/app/profile/leonardo.castilho5433/viz/data_viz_imob_atual/analiseexploratoria?publish=yes
  
# Tecnologias 

  - Python
  - Selenium
  - BeatifulSoup
  - Pandas
  - MS Excel
  - Tableau
  
# Metodos

  Para o projeto utilizei os metodos de:
  - WebScreaping
  - Data Filtering
  - Data Cleaning
  - String Methods
  - Regex
  - Dataviz com Tableu
  
# Criação Dataset

  - O dataset cru foi construido da pagina de vendas de Imoveis do site Loft (https://loft.com.br) realizando WebScreaping mesclando o BeautifulSoup e o Selenium para algumas funções que pretendia executar dentro do Url.
  - Notei que indepente de quantos imóveis o site diga ter disponiveis, apenas consegui coletar aproximadamente 5000 unidades de cada capital, salvo paginas que estavam quebradas ou que por algum mistério não trouxeram informações relevantes. 
  - O que resultou em um dataset cru final com 19982 linhas e 10 colunas.
  
# Limpeza Dataset

  - Para iniciar a limpeza importei os arquivos de CSV criados para cada capital e concatenei todos eles em um único DataFrame.
  - Iniciei as manipulações com Regex para limpar as colunas e criar algumas novas como o Bairro e Metro quadrado.
  - Os ajustes finos de que não foram possiveis de ser feitos com regex ou realocação de algums informações eu realizei no Excel e Tableau.

# Analise Exploratoria Tableau

  - Para entender como os preços se comportavam, a principio criei um histograma dentro do Tableau e identifiquei que os preços possuem uma distribuição gama. O que me levou a pesquisar mais sobre e descobrir que se trata de algum comum para informações financeiras.
  - Também identifiquei a grande disparidade de valor entre os imóveis mais baratos comparados aos mais caros, o que direcionou todo o meu trabalho então. 

# Conclusão

O projeto tinha como proposta inicial estudar a subvalorização dos imóveis das periferias, porém ao longo que fui maturando meu dataset vi que não seria possivel por enquanto realizar este calculo. O que me fez direcionar minha atenção a grande desigualdade de renda exposta por meio da propriedade imobiliaria. 
Trago como uma reflexão ao final deste trabalho a necessidade de politicas publicas para amenizar os problemas habitacionais brasileiros. 

# Proximos Passos

Se houvesse mais tempo para a realização deste projeto eu gostaria de criar um modelo de Regressões para entender a precificação dos imoveis e classifica-los em subvalorizados ou não dado ao que seria seu preço "esperado", segregando por regiões em cada cidade que o modelo rodaria.
Aprofundar as pesquisas sobre habitação e renda das familais.



  
