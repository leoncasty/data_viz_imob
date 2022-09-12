# Mercado Imobiliario Capitais

  Status do Projeto (Em progresso)

# Objetivo do Projeto

  Esse projeto tem como objetivo estudar se os imóveis localizados nas prefirerias das principais capitais brasileiras tem seu preço subvalorizado.
  
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
  
# Descrição do Projeto

  - O dataset cru foi construido realizando WebScreaping da pagina de vendas de Imoveis de São paulo do site Loft: https://loft.com.br na data de 08/09/2022. Possuia 12 Colunas e 4978 linhas, removi apenas as linhas que retornaram nulas após o WS.
  - Para realizar o WS utilizei uma lista de links da home criada com BeautifulSoup e depois para coletar os elementos em cada link criei uma função de coleta com o Selenium - Xpath.
  - Dado a criação do Dataset cru, os informações foram incluidas em um Pandas DataFrame e trabalhadas com Regex para limpar a base de quaisquer sujeiras.
  - O ajuste fino para a base e algumas transformações foram realizadas no Excel antes de subir a base limpa para o Tableu

# Conclusão

O projeto ainda não possui conclusão dada a Fase exploratoria dos dados.

# Proximos Passos

Para continuar a analise um dataset maior será criado incluindo as cidades de Rio de Janeiro, Porto Alegre e Minas Gerais. 
Após está inclusão e nova limpeza, um banco de dados será criado para armazenar as informaçõese facilitar seu acesso para futuras consultas. 
Um modelo de Regressões será criado para entender a precificação dos imoveis e classifica-los em subvalorizados ou não dado ao que seria seu preço "real".
Novo Dashboard contendo todas as analises será apresentado. 


  
