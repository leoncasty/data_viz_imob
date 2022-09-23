# Mercado Imobiliario Capitais

  Status do Projeto (Em progresso)

# Objetivo do Projeto

  Esse projeto tem como objetivo estudar os imóveis localizados em grandes brasileiras e verificar se os imoveis em suas periferias tem seu preço subvalorizado.
  
# Tableau Links

- https://public.tableau.com/app/profile/leonardo.castilho5433/viz/data_viz_imob_atual/analiseexploratoria?publish=yes
(incluir analise na apresentação)
  
# Tecnologias 

  - Python
  - Sklearn
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
  - Inferencia Estatistica
  - Regressão Multipla
  - Dataviz com Tableu
  
# Criação Dataset

  - O dataset cru foi construido da pagina de vendas de Imoveis do site Loft (https://loft.com.br) realizando WebScreaping mesclando o BeautifulSoup e o Selenium para algumas funções que pretendia executar dentro do Url.
  - Notei que indepente de quantos imóveis o site diga ter disponiveis, apenas consegui coletar aproximadamente 5000 unidades de cada capital, salvo paginas que estavam quebradas ou que por algum mistério não trouxeram informações relevantes. 
  - O que resultou em um dataset cru final com 19982 linhas e 10 colunas.
  
# Limpeza Dataset

  - Para iniciar a limpeza importei os arquivos de CSV criados para cada capital e concatenei todos eles em um único DataFrame.
  - Iniciei as manipulações com Regex para limpar as colunas e criar algumas novas como o Bairro e Metro quadrado.
  - Os ajustes finos de que não foram possiveis de ser feitos com regex ou realocação de algums informações eu realizei no Excel e Tableau.

# Analise Exploratoria Matplot / Tableau

  - Preciso incluir a análise na apresentação com as comparações entre as diferenças de imóveis mais baratos e mais caros de cada cidade e linkar isso
  com a renda familiar média de cada cidade
  - Entender quantos meses de trabalho de uma familia média seriam necessários para comprar os imóveis mais caros de cada cidade
  - Entender problemas de infraestrutura dos Bairros mais baratos. 

# Analise estatistica

 - Pretendo realizar uma regressão multipla para verificar o impacto de cada variavel no preço final do Imóvel

# Conclusão

O projeto ainda não possui conclusão dada a Fase exploratoria dos dados e pesquisas ainda sendo realizadas.

# Proximos Passos

Criar modelo de Regressões para entender a precificação dos imoveis e classifica-los em subvalorizados ou não dado ao que seria seu preço "esperado".
Aprofundar pesquisas sobre habitação e relacionar com a renda das familais.
Novo Dashboard contendo todas as analises será apresentado. 


  
